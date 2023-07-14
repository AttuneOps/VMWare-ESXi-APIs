



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



### KS ESXi Boot WinPE Recreate Virtual Machine

Recreates the target Windows virtual machine on ESXi.




## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| KS VMWare: Network Name | Text | `ksvmwarenetworkname` |  |
| Target Server | Basic Node | `targetserver` |  |
| KS: VM Ram Size GB | Text | `ksvmramsizegb` |  |
| VMWare: ESXi Server | Basic Node | `vmwareesxiserver` |  |
| VMWare: vCenter User | Basic Credential | `vmwarevcenteruser` |  |
| KS VMWare: Attune Base Dir | Text | `ksvmwareattunebasedir` |  |
| KS VMWare: Guest Type | Text | `ksvmwareguesttype` | https://vdc-download.vmware.com/vmwb-repository/dcr-public/8946c1b6-2861-4c12-a45f-f14ae0d3b1b9/a5b8094c-c222-4307-9399-3b606a04af55/vim.vm.GuestOsDescriptor.GuestOsIdentifier.html<br><br>https://vdc-download.vmware.com/vmwb-repository/dcr-public/da47f910-60ac-438b-8b9b-6122f4d14524/16b7274a-bf8b-4b4c-a05e-746f2aa93c8c/doc/vim.vm.GuestOsDescriptor.GuestOsIdentifier.html |
| KS VMWare: Storage Pool Name | Text | `ksvmwarestoragepoolname` |  |
| KS: VM CPU Count | Text | `ksvmcpucount` |  |
| Attune OS Build Server | Linux/Unix Node | `attuneosbuildserver` | This variable is used in the "Kickstart" build procedures, so the "Attune Server" can be used to build Attune servers. |
| Linux: Attune User | Linux/Unix Credential | `linuxattuneuser` |  |
| VMWare: vCenter Server | Basic Node | `vmwarevcenterserver` |  |
| KS VMWare: Boot ISO Dir | Text | `ksvmwarebootisodir` | The directory of where the kickstart ISOs are copied to. |
| KS: VM Disk Size GB | Text | `ksvmdisksizegb` |  |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |






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
