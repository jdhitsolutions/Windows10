# Lab definition

This lab builds the following:

* 1 Workgroup joined Windows 10 Client with RSAT tools installed.

It will also create a local user account with a password of `P@ssw0rd` using same name as the person running the configuration. In other words, it will use the value of `$env:username`.

## To get started:

    To run the full lab setup, which includes Setup-Lab, Run-Lab, Enable-Internet, and Validate-Lab:
    PS> Unattend-Lab
    
    To run the commands individually to setup the lab environment:

    Run the following for initial setup:
    PS> Setup-Lab

    To start the LAb, and apply configurations the first time:
    PS> Run-Lab

    To enable Internet access for the VM's, run:
    PS> Enable-Internet

    To validate when configurations have converged:
    PS> Validate-Lab
   
    Once validation is complete you should connect to the VM, logon as the non-administrator account and let Windows 10 finish setting up. Then restart the computer applying any pending updates. After this you can, and should, snapshot the VM.

## To Stop and snapshot the lab

    To stop the lab VM's:
    PS> Shutdown-lab

    To checkpoint the VM's:
    PS> Snapshot-Lab

    To quickly rebuild the labs from the checkpoint, run:
    PS> Refresh-Lab

## To remove a lab
    
    To destroy the lab to build again:
    PS> Wipe-Lab
