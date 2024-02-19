# Windows10 Lab Configuration Files

## Deprecated

This repository is now deprecated and no longer maintained. The files in this repository are now part of the [PSAutoLab](https://github.com/pluralsight/PS-AutoLab-Env) module.

This module is now maintained by Pluralsight. To use, follow these high-level steps:

1. Open an elevated PowerShell prompt
2. Run: `Install-Module PSAutoLab -force -SkipPublisherCheck`
3. Run `Setup-Host`
4. Reboot if you had to install Hyper-V.
5. Change location to C:\Autolab\Configurations\Windows10
6. Run: `Unattend-Lab` and follow onscreen instructions.

You can find detailed setup instructions for the PSAutoLab module at [https://github.com/pluralsight/PS-AutoLab-Env/blob/master/Detailed-Setup-Instructions.md](https://github.com/pluralsight/PS-AutoLab-Env/blob/master/Detailed-Setup-Instructions.md).
