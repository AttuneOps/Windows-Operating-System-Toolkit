



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

Clone this project into your own instance of Attune.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-clone-new-project-01.png" alt="clone a new project"/>

---

Paste the GIT repository URL into Attune and Select Clone.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-clone-new-project-02.png" alt="clone a new project"/>

---

**Now that this project is in your Attune instance you can begin creating
Jobs.**

Navigate to the Plan workspace and create a Job from a Blueprint in the
Project you cloned.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-plan-new-job-11.png" alt="plan a new job"/>

---

Configure the Parameters for the Job you created. Create the Values you're
missing in the next step.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-plan-new-job-12.png" alt="plan a new job"/>

---

Create the Values required to fill the Parameters for the Job.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-plan-new-job-13-1.png" alt="plan a new job"/>

---

Run your Job.

<img src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-run-job-01.png" alt="run your job"/>

---

**Congratulations, you’ve run a cloned project.**

If you need further assistance, please explore our help.

<img width=200 src="https://www.servertribe.com/wp-content/uploads/2023/02/Attune-get-help-01.png" alt="get help"/>




## Blueprints

This Project contains the following Blueprints.



### WIN Connect to Active Directory


### WIN Disable Sleep and Hibernation


### WIN Partition and Format E: Drive


### WIN PON Setup ICCP Server NICs


### WIN Reboot


### WIN Remove Default Applications


### WIN Setup Debug Utilities


### WIN Setup Standard Windows OS


### WIN Setup Useful Utilities

Set up a basic set of useful Windows programs.

### WSUU Install Brave





## Parameters


| Name | Type | Script Reference | Comment |
| ---- | ---- | ---------------- | ------- |
| Active Directory Server | Windows Node | `activedirectoryserver` | None |
| AD Full Domain Name | Text | `adfulldomainname` | None |
| DMS Subnet | Network IPv4 Subnet | `dmssubnet` | Make this the same as Target Subnet. |
| ICCP NIC2 | Basic Node | `iccpnic2` | None |
| NTP Servers | Node List | `ntpservers` | None |
| Target Environment Servers | Node List | `targetenvironmentservers` | The servers in this group are added to the hosts file for this server being built |
| Target Server: Browser Home Page | Text | `targetserverbrowserhomepage` | None |
| Target Server: Win | Windows Node | `targetserverwin` | None |
| Target Server: Windows TimeZone | Text | `targetserverwindowstimezone` | None |
| Target Server Win: GeoID | Text | `targetserverwingeoid` | The Settings -> Time & Language -> Region & Language -> Country or Region setting.
https://docs.microsoft.com/en-au/windows/win32/intl/table-of-geographical-locations?redirectedfrom=MSDN |
| Target Server Win: LANG | Text | `targetserverwinlang` | This is used to set the windows operating systems LANG,
Settings -> Time & Language -> Region & Language -> Language |
| Target Server Win: LANG ID | Text | `targetserverwinlangid` | None |
| Windows: AD Admin User | Windows Credential | `windowsadadminuser` | None |
| Windows: Administrator | Windows Credential | `windowsadministrator` | The windows administrator user |




## Files


| Name | Type | Comment |
| ---- | ---- | ------- |
| PON Win Server Hosts File | Version Controlled Files | Root folder=/, Deploys to /C$/ |
| WIN Util 7z | Version Controlled Files | https://www.7-zip.org/download.html
(alternative MSI installer) 7-Zip for 64-bit Windows x64 (Intel 64 or AMD64) |
| WIN Util Brave 64bit | Large Archives | None |
| WIN Util MobaXTerm | Large Archives | None |
| WIN Util Notepad++ | Version Controlled Files | Utilities such as notepad++, 7zip, etc |
| WIN Util PowerToys | Version Controlled Files | https://github.com/microsoft/PowerToys/releases |
| WIN Util Putty | Version Controlled Files | None |
| WIN Util WinSCP | Version Controlled Files | None |
| WIN Util WireShark | Large Archives | None |






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
