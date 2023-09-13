



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# VMWare ESXi APIs






# Attune

[Attune](https://www.servertribe.com/)
automates and orchestrates processes to streamline deployments, scaling,
migrations, and management of your systems. The Attune platform is building a
community of sharable automated and orchestrated processes.

You can leverage the publicly available orchestrated blueprints to increase
your productivity, and accelerate the delivery of your projects. You can
open-source your own work and improve existing community orchestrated projects.

## Get Started with Attune, Download NOW!

The **Attune Community Edition** can be
[downloaded](https://www.servertribe.com/comunity-edition/)
for free from our
[ServerTribe website](https://www.servertribe.com/comunity-edition/).
You can learn more about Attune through
[ServerTribe's YouTube Channel](https://www.youtube.com/@servertribe).







# Clone this Project

To clone this project into your own instance of Attune, follow the
[Clone a GIT Project How To Instructions](https://servertribe-attune.readthedocs.io/en/latest/howto/design_workspace/clone_project.html).




## Blueprints

This Project contains the following Blueprints.



### LIN Deploy VMWare Drivers - Group


### Recreate Windows Virtual Machine on ESXi

Creates a Windows virtual machine from two ISOs.
1. Unaltered Windows ISO.
2. ESXi Drivers ISO.

### ESXi Add New Network Adaptor


### ESXi Add New Virtual Disk


### WIN Setup ESXi Tools
### Build Virtual Machine on ESXi





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| VMWare vCenter User | Basic Credential | `vmwarevcenteruser` | The user to connect to vCenter. |
| VMWare ESXi Host | Basic Node | `vmwareesxihost` | The ESXi Host details. |
| VMWare vCenter Node | Basic Node | `vmwarevcenternode` | The vCenter Node details. |
| Automation Worker Linux User | Linux/Unix Credential | `automationworkerlinuxuser` | non privilege user on the Automation Worker node. |
| Automation Worker Linux Node | Linux/Unix Node | `automationworkerlinuxnode` | The device used to connect to another device or perform tasks. This can be the devices Attune is running on. |
| Automation Worker Base Directory | Text | `automationworkerbasedirectory` | Directory for storing kickstart files, eg: "~/kickstart". |
| VM Network Name | Text | `vmnetworkname` | vSphere VM Network Name. |
| VM Ram Size GB | Text | `vmramsizegb` | VM Ram Size in GB. |
| VM Disk Size GB | Text | `vmdisksizegb` | VM Disk Size in GB. |
| VM Guest Type | Text | `vmguesttype` | vSphere VM Guest Type.<br>https://vdc-download.vmware.com/vmwb-repository/dcr-public/8946c1b6-2861-4c12-a45f-f14ae0d3b1b9/a5b8094c-c222-4307-9399-3b606a04af55/vim.vm.GuestOsDescriptor.GuestOsIdentifier.html<br><br>https://vdc-download.vmware.com/vmwb-repository/dcr-public/da47f910-60ac-438b-8b9b-6122f4d14524/16b7274a-bf8b-4b4c-a05e-746f2aa93c8c/doc/vim.vm.GuestOsDescriptor.GuestOsIdentifier.html |
| VM Storage Pool Name | Text | `vmstoragepoolname` | vSphere VM Storage Pool Name. |
| VMWare Boot ISO Directory | Text | `vmwarebootisodirectory` | The directory of where the ISOs are copied to on vSphere. |
| Virtual Machine Boot Loader Is UEFI | Text | `virtualmachinebootloaderisuefi` |  |
| Virtual Machine Boot Loader Is BIOS | Text | `virtualmachinebootloaderisbios` |  |
| New VM Node | Basic Node | `newvmnode` | The virtual machine being worked on. |
| VM CPU Count | Text | `vmcpucount` | VM CPU Count. |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |
| WIN VMWare Drivers | Large Archives | These drivers are compatible with Windows 10 and Windows Server 2016 Std.<br><br>To obtain the files required for this archive, create a new Windows Server 2016 VM, install the VMWare Tools, and zip up the directory C:\Program Files\Common Files\VMware\Drivers |
| WIN ESXi Tools | Large Archives |  |






# Contribute to this Project

**The collective power of a community of talented individuals working in
concert delivers not only more ideas, but quicker development and
troubleshooting when issues arise.**

If you’d like to contribute and help improve these projects, please fork our
repository, commit your changes in Attune, push you changes, and create a
pull request.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-pull-request-01.png" alt="pull request"/>

---

Please feel free to raise any issues or questions you have.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-02.png" alt="create an issue"/>


---

**Thank you**
