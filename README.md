# Synapse Killer V2.0 (Updated 2024)
Keep your Razer configs without Synapse's bloatware running in the background.
<br></br>
<img src="https://i.ibb.co/XXBx11G/razer-blackwidow-chroma-gif-5.gif" alt="Alt text" title="Synapse Keyboard">

<img src="https://i.ibb.co/Yh5sHBb/Razer-SServices.png" alt="Loading Image..."  title="Synapse Processes"/>

# How It Works
This Project was made in [C](https://en.wikipedia.org/wiki/C_(programming_language)) and built into multiple executables.

It provides a way to **use your Razer Configs** without any [Razer Synapse Services](https://www.razer.com/synapse-3) running.</br>
`SynapseKiller` **freezes and destroys** all Razer Services **allowing configs to be loaded** first.

It does not keep any active processes, only runs until all services are handled.

**Functionality**
* Listen for processes
* Enable, Disable Processes
* Start or Kill Processes
* Send Notifications
* Runs On Startup (Optional)

# How to Install

| Exe    | Description | Releases |
| -------- | ------- | ------- |
| <a href="https://github.com/NxRoot/SynapseKiller/archive/refs/heads/master.zip"><img style="min-width: 40px;min-height: 40px; width: 40px;" src="https://iili.io/deaPZH7.png"/></a> | Destroy all synapse services    | [Download](https://github.com/NxRoot/SynapseKiller/archive/refs/heads/master.zip)    |
| <a href="https://github.com/NxRoot/SynapseKiller/archive/refs/heads/master.zip"><img style="min-width: 40px;min-height: 40px; width: 40px;" src="https://iili.io/deaPLSS.png"/></a> | Enable all synapse services     | [Download](https://github.com/NxRoot/SynapseKiller/archive/refs/heads/master.zip)    |
| <a href="https://github.com/NxRoot/SynapseKiller/archive/refs/heads/master.zip"><img style="min-width: 40px;min-height: 40px; width: 40px;" src="https://iili.io/deaPtR9.png"/></a> | Start synapse killer on boot    | [Download](https://github.com/NxRoot/SynapseKiller/archive/refs/heads/master.zip)    |


# Run on Boot

* Move `Synapse-Boot` executable into `C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp` 

# Custom Processes

* Create a new `config.txt` file in the same folder as the executable with the following content:
```
C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Central
C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Updater
C:\Program Files (x86)\Razer\Razer Services\Razer Central\RazerCentralService
C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Synapse Service
C:\Program Files (x86)\Razer\Synapse3\UserProcess\Razer Synapse Service Process
C:\Program Files (x86)\Razer\Razer Services\GMS\GameManagerServiceStartup
C:\Program Files (x86)\Razer\Razer Services\GMS\GameManagerService
C:\Program Files (x86)\Razer\Synapse3\WPFUI\Framework\Razer Synapse 3 Host\Razer Synapse 3
```

## &nbsp;
⭐ If you find this useful!

