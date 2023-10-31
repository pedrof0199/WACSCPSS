# WACSCPSS

@echo off
color 2
echo.
echo.
echo =======================================
echo =======================================
echo =======================================
echo      ___           ___           ___     
echo     /  /\         /  /\         /  /\    
echo    /  /:/_       /  /::\       /  /::\   
echo   /  /:/ /\     /  /:/\:\     /  /:/\:\  
echo  /  /:/ /:/_   /  /::\ \:\   /  /:/  \:\ 
echo /__/:/ /:/ /\ /__/:/\:\_\:\ /__/:/ \  \:\
echo \  \:\/:/ /:/ \__\/  \:\/:/ \  \:\  \__\/
echo  \  \::/ /:/       \__\::/   \  \:\      
echo   \  \:\/:/        /  /:/     \  \:\     
echo    \  \::/        /__/:/       \  \:\    
echo     \__\/         \__\/         \__\/   
echo.
echo.
echo Escolha o numero de acordo com versao do seu Windows! 
echo [1] Home/Core
echo [2] Home/Core(Country Specific)
echo [3] Home/Core (Single Language)
echo [4] Home/Core N
echo [5] Professional(Wind 10 pro)
echo [6] Professional N(Wind 10 pro N
echo [7] Enterprise
echo [8] Enterprise N
echo [9] Education
echo [10] Education N  
echo [11] Enterprise 2015 LTSB	
echo [12] Enterprise 2015 LTSB N
echo [13] Enterprise 2016 LTSB
echo [14] Enterprise 2016 LTSB N
echo [15] Nao sei qual a versao do meu windows.
echo [16] Sair.

echo.
echo.

set /p ativar=Digite a versaos desejada: 

if "%ativar%" == "1" goto op1
if "%ativar%" == "2" goto op2
if "%ativar%" == "3" goto op3
if "%ativar%" == "4" goto op4
if "%ativar%" == "5" goto op5
if "%ativar%" == "6" goto op6
if "%ativar%" == "7" goto op7
if "%ativar%" == "8" goto op8
if "%ativar%" == "9" goto op9
if "%ativar%" == "10" goto op10
if "%ativar%" == "11" goto op11
if "%ativar%" == "12" goto op12
if "%ativar%" == "13" goto op13
if "%ativar%" == "14" goto op14
if "%ativar%" == "15" goto op15
if "%ativar%" == "15" goto op16

set /p sair=Sair

if "%sair%" == exit "1" goto exit1

:op1 
slmgr.vbs /upk
slmgr /ipk TX9XD-98N7V-6WMQ6-BX7FG-H8Q99
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op2 
slmgr.vbs /upk
slmgr /ipk  PVMJN-6DFY6-9CCP6-7BKTT-D3WVR
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op3 
slmgr.vbs /upk
slmgr /ipk 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH  
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op4 
slmgr.vbs /upk
slmgr /ipk  3KHY7-WNT83-DGQKR-F7HPR-844BM  
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op5 
slmgr.vbs /upk
slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX 
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op6 
slmgr.vbs /upk
slmgr /ipk MH37W-N47XK-V7XM9-C7227-GCQG9
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op7 
slmgr.vbs /upk
slmgr /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op8 
slmgr.vbs /upk
slmgr /ipk  DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op0 
slmgr.vbs /upk
slmgr /ipk  NW6C2-QMPVW-D7KKK-3GKT6-VCFB2
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op10 
slmgr.vbs /upk
slmgr /ipk  2WH4N-8QGBV-H22JP-CT43Q-MDWWJ
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op11 
slmgr.vbs /upk
slmgr /ipk WNMTR-4C88C-JK8YV-HQ7T2-76DF9
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op12 
slmgr.vbs /upk
slmgr /ipk 2F77B-TNFGY-69QQF-B8YKP-D69TJ
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op13 
slmgr.vbs /upk
slmgr /ipk DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ 
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op14 
slmgr.vbs /upk
slmgr /ipk  QFFDN-GRT3P-VKWWX-X7T3R-8B639
slmgr /skms kms8.msguides.com
slmgr /ato
exit

:op15
start winver.exe
echo Digite o numero de acordo com a versao do seu windows.

:op16
exit


