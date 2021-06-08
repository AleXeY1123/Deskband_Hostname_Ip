# Deskband_Hostname_Ip

Displaying the hostname and Ip-address on the daskband.

## Original
https://github.com/microsoft/Windows-classic-samples/tree/master/Samples/Win7Samples/winui/shell/shellextensibility/deskbands

## Build

Build Deskband_Hostname_Ip.dll with the provided solution.

## Install

Register the dll by running `regsvr32 Deskband_Hostname_Ip_64.dll` or `regsvr32 Deskband_Hostname_Ip_32.dll` from an elevated command prompt. You need to specify the full path to the dll

## Run

Right-click on the Task Bar, expand "Toolbars" menu option and choose "Deskband Hostname Ip".  You will see the newly created Desk Band show up on the Task Bar.

Note: The sample may not appear until you open the Toolbars menu the second time.

## Uninstall

Unregister the sample by running `regsvr32 /u Deskband_Hostname_Ip_64.dll` or `regsvr32 /u Deskband_Hostname_Ip_32.dll` from an elevated command prompt. You need to specify the full path to the dll
