The trick here is to make sure the ISO that you want to delete from the ESXi datastore is not currently loaded onto the CD ROMs of any virtual machines.

Change into the PSDrive location of the datasostore of the kickstart ISOs directory.

Then call Remove-Item to delete the ISO.