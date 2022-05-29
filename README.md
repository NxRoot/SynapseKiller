# SynapseKiller V1.0
Razer Synapse Services Destroyer ( Keep your Razer Gaming configs without Synapse's bloatware running in the background )
<br></br>
<img src="https://i.ibb.co/XXBx11G/razer-blackwidow-chroma-gif-5.gif" style="float: right" alt="Alt text" title="Optional title">


<img src="https://i.ibb.co/Yh5sHBb/Razer-SServices.png" alt="Alt text" style="float: left" title="Optional title">


# How Does It Work
This Project was made in [batch  script](https://en.wikipedia.org/wiki/Batch_file) and converted to an installer and executable.

It provides a way to **use your Razer Configs** without any [Razer Synapse Services](https://www.razer.com/synapse-3) running.</br>
`SynapseKiller` **freezes and destroys** all Razer Services **allowing configs to be loaded** first.

It does not keep any active processes, only runs until all services are handled.

**Functionality**
* Listen for processes
* Enable, Disable Processes
* Start or Kill Processes
* Send Notifications
* Runs On Startup (Optional)

**Setup Version**
* Runs On Startup (Handles Synapse Processes)
* Synapse no longer needed on startup

**Portable Version**
* Doesn't run on startup unless you move the executable to `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp`
* Comes with 2 executables, `SynapseKiller.exe` and `SynapseEnabler.exe` to Reset and Re-Enable Razer Synapse

# How to Install
**Setup Version** ( This will run automatically on startup )
* Download [Setup](https://github.com/NxRoot/SynapseKiller/releases/tag/Latest)
* **Uncheck Synapse to Run on Startup** (Razer Central Settings Panel)
* Install `SynapseKillerSetup.exe`

**Portable Version**
* Download [Portable](https://github.com/NxRoot/SynapseKiller/releases/tag/Latest)
* Run `SynapseKiller.exe`

# How to Uninstall
**Setup Version**
* Just run the normal uninstaller that is generated after Setup is completed

**Portable Version**
* Run `SynapseEnabler.exe` to Re-Enable Synapse
* Delete all files

# Compability
* This was only tested on **Razer BlackWidow V3** but its supposed to work with all devices
* Macros need to be tested

# TODO
* Open Synapse Panel without the need to Re-Enable Services
* Handle Chroma and Studio Processes
* Test more devices

