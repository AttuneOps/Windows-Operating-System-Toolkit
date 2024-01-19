



[![Docs](https://img.shields.io/badge/docs-latest-brightgreen.svg)](http://doc.servertribe.com)
[![Discord](https://img.shields.io/discord/844971127703994369)](http://discord.servertribe.com)
[![Docs](https://img.shields.io/badge/videos-watch-brightgreen.svg)](https://www.youtube.com/@servertribe)
[![Generic badge](https://img.shields.io/badge/download-latest-brightgreen.svg)](https://www.servertribe.com/community-edition/)

# Windows OS Toolkit






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



### WIN Connect to Active Directory


### WIN Disable Sleep and Hibernation


### WIN Partition and Format E Drive


### WIN PON Setup ICCP Server NICs


### WIN Reboot


### WIN Set Time Server


### WIN Setup Debug Utilities


### WIN Setup Standard Windows OS


### WIN Setup Useful Utilities

Set up a basic set of useful Windows programs.

### WSUU Install Brave


### Remove Windows Bloatware





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Active Directory Server | Windows Node | `activedirectoryserver` |  |
| AD Full Domain Name | Text | `adfulldomainname` |  |
| DMS Subnet | Network IPv4 Subnet | `dmssubnet` | Make this the same as Target Subnet. |
| ICCP NIC2 | Basic Node | `iccpnic2` |  |
| NTP Servers | Node List | `ntpservers` |  |
| Target Environment Servers | Node List | `targetenvironmentservers` | The servers in this group are added to the hosts file for this server being built |
| Target Server: Browser Home Page | Text | `targetserverbrowserhomepage` |  |
| Target Server: Win | Windows Node | `targetserverwin` |  |
| Target Server: Windows TimeZone | Text | `targetserverwindowstimezone` |  |
| Target Server Win: GeoID | Text | `targetserverwingeoid` | The Settings -> Time & Language -> Region & Language -> Country or Region setting.<br>https://docs.microsoft.com/en-au/windows/win32/intl/table-of-geographical-locations?redirectedfrom=MSDN |
| Target Server Win: LANG | Text | `targetserverwinlang` | This is used to set the windows operating systems LANG,<br>Settings -> Time & Language -> Region & Language -> Language |
| Target Server Win: LANG ID | Text | `targetserverwinlangid` |  |
| Timezone Server | Basic Node | `timezoneserver` |  |
| Windows: AD Admin User | Windows Credential | `windowsadadminuser` |  |
| Windows: Administrator | Windows Credential | `windowsadministrator` | The windows administrator user |




## Files

| Name | Type | Comment |
| ---- | ---- | ------- |
| PON Win Server Hosts File | Version Controlled Files | Root folder=/, Deploys to /C$/ |
| WIN Util 7z | Version Controlled Files | https://www.7-zip.org/download.html<br>(alternative MSI installer) 7-Zip for 64-bit Windows x64 (Intel 64 or AMD64) |
| WIN Util Brave 64bit | Large Archives | For the latest release: https://github.com/brave/brave-browser/releases/latest |
| WIN Util MobaXTerm | Large Archives |  |
| WIN Util Notepad++ | Version Controlled Files | Utilities such as notepad++, 7zip, etc |
| WIN Util PowerToys | Version Controlled Files | https://github.com/microsoft/PowerToys/releases |
| WIN Util Putty | Version Controlled Files |  |
| WIN Util WinSCP | Version Controlled Files |  |
| WIN Util WireShark | Large Archives |  |






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
