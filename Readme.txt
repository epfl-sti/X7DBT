Please note that KVM-Over-LAN is supported on select SIM IPMI cards. 
Refer to the list below for choosing the correct firmware.

SIM IPMI WITH KVM-Over-LAN Support:
Models: AOC-SIMLP-3+, AOC-SIMLP-B+, AOC-SIMSO+, AOC-SIM1U+, AOC-SIM1U-3B+,
        AOC-SIMLC+
Firmware: ugsim157.bin


SIM IPMI WITHOUT KVM-Over-LAN Support:
Models: AOC-SIMLP-3, AOC-SIMLP-B, AOC-SIMSO, AOC-SIMLC, AOC-SIM1U, AOC-SIM1U-3B   
Firmware: ubsim157.bin        

================================================================================
Supermicro SIM IPMI firmware update notice
================================================================================

1.  Obtain a copy of the new SIM IPMI firmware from a Supermicro SIM IPMI CD or 
    Supermicro FTP site (ftp.supermicro.com/CDR-SIMIPMI_x.xx_for_SIM_IPMI/) and 
    then save it (uxxxxxxx.bin) on your local computer.
2.  Connect to your SIM IPMI card on the remote server from your local computer 
    using a web browser .
3.  Type in your username and password to login
4.  From the Main menu on the left, click on the "Maintenance" and then click 
    on the "Update Firmware" from the submenu.
5.  In the "Firmware Upload" page, click on "Browse" button and then select the 
    new firmware you just saved on your local computer. Once the Firmware File 
    is selected, click on the "Upload" button.
6.  In the "Firmware Update" page, click on the "Update" button to proceed the 
    firmware update process. OR abort the update process by clicking on the 
    "Discard" button.
7.  Wait until the firmware update process is finished (Please be patient, it 
    might take a few minutes to complete!).
================================================================================