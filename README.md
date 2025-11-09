# Synapse Killer V2.0 (Updated 2025)
Keep your Razer configs without Synapse's bloatware running in the background.
<br></br>
<img src="https://github.com/NxRoot/SynapseKiller/blob/main/keyboard.gif" width="60%" alt="Alt text" title="Synapse Keyboard">

<img src="https://github.com/NxRoot/SynapseKiller/blob/main/configuration.gif" alt="Loading Image..." width="60%" title="Synapse Configurator"/>


# How to Install

| Exe    | Description | Releases |
| -------- | ------- | ------- |
| <a href="https://github.com/NxRoot/SynapseKiller/releases/download/Latest/SynapseKillerV3.zip"><img style="min-width: 40px;min-height: 40px; width: 40px;" src="https://iili.io/deaPZH7.png"/></a> | Enable or disable all synapse services    | [Download](https://github.com/NxRoot/SynapseKiller/releases/download/Latest/SynapseKillerV3.zip)    |


# How To Use (Auto)
- Run `SynapseKiller - Configurator.exe` to configure settings.
- Run `SynapseKiller.exe` to Enable or Disable Synapse.

# Run on Boot (Manual)

* Press `WIN + R` to open Run Console --> Write `shell:startup` and press OK.
* Move `SynapseKiller.exe` executable into the folder. 

# Configuration (Manual)

* After running `SynapseKiller.exe` you should find the `skconfig.txt` in your documents folder.
* The first line must be pointing to Razer App executable, all the other lines are services.
* The last line is the `time in seconds` to load razer configs before destroying synapse.

##### Synapse 3 (Default)
```
C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Central.exe
C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Updater.exe
C:\Program Files (x86)\Razer\Razer Services\Razer Central\RazerCentralService.exe
C:\Program Files (x86)\Razer\Razer Services\Razer Central\Razer Synapse Service.exe
C:\Program Files (x86)\Razer\Synapse3\UserProcess\Razer Synapse Service Process.exe
C:\Program Files (x86)\Razer\Razer Services\GMS\GameManagerServiceStartup.exe
C:\Program Files (x86)\Razer\Razer Services\GMS\GameManagerService.exe
C:\Program Files (x86)\Razer\Synapse3\WPFUI\Framework\Razer Synapse 3 Host\Razer Synapse 3.exe
30
```

##### Synapse 4 (Not Tested) (The last 3 lines must be your exact razer app version)
```
C:\Program Files\Razer\RazerAppEngine\RazerAppEngine.exe
C:\Program Files (x86)\Razer\Razer Services\GMS3\GameManagerService3.exe
C:\Program Files (x86)\Razer\Razer Services\GMS3\GMSServiceRegister.exe
C:\Program Files\Razer\RazerAppEngine\app-4.0.406\CommonDLL\RzEngineMon.exe
C:\Program Files\Razer\RazerAppEngine\app-4.0.406\CommonDLL\rzNotification.exe
C:\Program Files\Razer\RazerAppEngine\app-4.0.406\CommonDLL\RzPowerTool.exe
30
```

## &nbsp;
⭐ If you find this useful!

