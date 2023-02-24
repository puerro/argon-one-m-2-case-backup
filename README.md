# argon-one-m-2-case-backup
Personal Backup Repository

## Script Backup

### How to Install Argon ONE Pi 4 V2 Power Button & Fan Control
1. Connect to the internet.

2. Open "Terminal" in Raspbian.

3. Type the text below in the "Terminal" to initiate installationof **Argon ONE Pi 4** script.

```
curl https://raw.githubusercontent.com/puerro/argon-one-m-2-case-backup/main/argon1.sh | bash
```

4. Reboot

### Argon ONE Pi 4 V2 Power Button Functions
The process above will automatically install the configuration that will activate the **Argon ONE Pi 4** Power Button with the following functions.

| Argon ONE Pi 4 State |        Action       |           Function          |
|:--------------------:|:-------------------:|:---------------------------:|
|          Off         |     Short Press     |           Turn ON           |
|          On          | Long Press (>= 3 s) | Soft Shutdown and Power Cut |
|          On          |  Short Press (<3 s) |           Nothing           |
|          On          |      Double tap     |            Reboot           |
|          On          | Long Press (>= 5 s) |       Forced Shutdown       |

### Argon ONE Pi 4 V2 Fan Speed
Upon installation of the **Argon ONE Pi 4** script by default, the setting of the **Argon ONE Pi 4** cooling system are as follows:

| CPU Temp | Fan Power |
|:--------:|:---------:|
|   55 C   |    10%    |
|   60 C   |    55%    |
|   65 C   |   100%    |

However, you may change or configure the FAN to your destred setting by clicking the **Argon** ONE **Pi 4** Config icon on your Desktop.

Or via "Terminal" by typing and following the specified format:

```
argonone-config
```

### Uninstall Argon ONE Pi 4 V2 Script
To uninstall the **Argon ONE Pi 4** script you may do so by clicking the **Argon ONE Pi 4** Uninstall icon on your Desktop.

You may also remove the script via "Terminal" by typing:

```
argonone-uninstall
```

Always reboot after changing any configuration or uninstallation for the revised settings to take effect.

### Built-in Infrared Receiver
The latest version has a programmable Infrared Receiver installed that can turn ON and OFF the device using the proprietary Argon 40 remote.

To configure the **Infrared Receiver ON/OFF signal of Argon ONE V2 and M.2** type in the Terminal App:

```
argonone-ir
```

Then follow the instructions indicated.

## Localization Modification

### argon1.sh
Edit the URL in the line 501, line 502, line 529.

### argonone-irconfig.sh
Edit the URL in the line 284.

## IR Configuration File
rc_keymap.txt file only for Argon Remote
