# STM32_HRTIM_Examples

STM32 Atollic tips:

1. Can rename the project, but it will create copy of it. But I cannot find the folder location of it.
2. rename the last folder of the project wont be the same as the project name.
3. deleted EWARM and MDK-ARM, ok.
4. move contents of STM32F3348-Discovery folder (.cproject, .project, and STM32F334C8Tx_FLASH.ld) to main proj folder and delete that folder. >> not possible
5. move contents of SW4STM32 folder to main proj folder. >> same as #4, not possible.
5. .cproject is Atollic Project file, the last folder name of the imported folder will be the project name. but may have problem that some files are not added.

From CubeMX settings:

Resource/Linked Resources:
	ECLIPSE_HOME = same
	PARENT_LOC = same
	PROJECT_LOC = diff
	WORKSPACE_LOC = same

C/C++ Build:
	Environment:
		BUILD_CONFIGURATION = Debug
		CWD = D:\working\Z1_Victor\STM32\00_Projects\STM32F3\DiscoveryStm32F334_Serial2Serial3_printf01\Debug
		GCC_EXCE_PREFIX = <undefined>
		PATH = C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0\ARMTools\bin;C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0\Tools;C:/Program Files (x86)/Atollic/TrueSTUDIO for STM32 9.2.0/ide/jre/bin/client;C:/Program Files (x86)/Atollic/TrueSTUDIO for STM32 9.2.0/ide/jre/bin;C:/Program Files (x86)/Atollic/TrueSTUDIO for STM32 9.2.0/ide/jre/lib/i386;c:\2005mentorgraphics\2005PADS\SDD_HOME\common\win32\bin;c:\2005mentorgraphics\2005PADS\SDD_HOME\common\win32\lib;C:\ProgramData\Oracle\Java\javapath;C:\Program Files (x86)\Intel\iCLS Client\;C:\Program Files\Intel\iCLS Client\;C:\Program Files (x86)\NVIDIA Corporation\PhysX\Common;C:\COSMOS Applications;C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Program Files\Intel\DMIX;C:\Program Files (x86)\QuickTime Alternative\QTSystem;C:\Program Files\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files\Intel\Intel(R) Management Engine Components\IPT;C:\Program Files (x86)\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files (x86)\Intel\Intel(R) Management Engine Components\IPT;C:\CooCox\CoIDE_V2Beta\bin;C:\OrCAD\OrCAD_16.6_Lite\tools\pcb\bin;C:\OrCAD\OrCAD_16.6_Lite\tools\fet\bin;C:\OrCAD\OrCAD_16.6_Lite\OpenAccess\bin\win32\opt;C:\OrCAD\OrCAD_16.6_Lite\tools\bin;C:\OrCAD\OrCAD_16.6_Lite\tools\Capture;C:\OrCAD\OrCAD_16.6_Lite\tools\PSpice;;C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0
		PWD = D:\working\Z1_Victor\STM32\00_Projects\STM32F3\DiscoveryStm32F334_Serial2Serial3_printf01\Debug
		TOOLCHAIN_PATH = C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0\ARMTools\bin

C/C++ General:
	Paths and Symbols:
		Includes:
			GNU C
				INC
				Drivers/CMSIS/Device/ST/STM32F3xx/Include
				Drivers/STM32F3xx_HAL_Driver/Inc
				Drivers/STM32F3xx_HAL_Driver/Inc/Legacy
				Drivers/CMSIS/Include


From Importing Projecs:

Resource/Linked Resources (same):
	ECLIPSE_HOME = same
	PARENT_LOC = same
	PROJECT_LOC = diff
	WORKSPACE_LOC = same

C/C++ Build:
	Environment:
		BUILD_CONFIGURATION = Debug
		CWD = D:\working\Z1_Victor\STM32\STM32Cube_FW_F3_V1.10.0_temp\Projects\STM32F3348-Discovery\Examples\HRTIM\HRTIM_BuckBoost_AN4449\SW4STM32\STM32F3348-Discovery\Debug
		GCC_EXCE_PREFIX = <undefined>
		PATH = C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0\ARMTools\bin;C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0\Tools;C:/Program Files (x86)/Atollic/TrueSTUDIO for STM32 9.2.0/ide/jre/bin/client;C:/Program Files (x86)/Atollic/TrueSTUDIO for STM32 9.2.0/ide/jre/bin;C:/Program Files (x86)/Atollic/TrueSTUDIO for STM32 9.2.0/ide/jre/lib/i386;c:\2005mentorgraphics\2005PADS\SDD_HOME\common\win32\bin;c:\2005mentorgraphics\2005PADS\SDD_HOME\common\win32\lib;C:\ProgramData\Oracle\Java\javapath;C:\Program Files (x86)\Intel\iCLS Client\;C:\Program Files\Intel\iCLS Client\;C:\Program Files (x86)\NVIDIA Corporation\PhysX\Common;C:\COSMOS Applications;C:\Windows\system32;C:\Windows;C:\Windows\System32\Wbem;C:\Windows\System32\WindowsPowerShell\v1.0\;C:\Program Files\Intel\DMIX;C:\Program Files (x86)\QuickTime Alternative\QTSystem;C:\Program Files\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files\Intel\Intel(R) Management Engine Components\IPT;C:\Program Files (x86)\Intel\Intel(R) Management Engine Components\DAL;C:\Program Files (x86)\Intel\Intel(R) Management Engine Components\IPT;C:\CooCox\CoIDE_V2Beta\bin;C:\OrCAD\OrCAD_16.6_Lite\tools\pcb\bin;C:\OrCAD\OrCAD_16.6_Lite\tools\fet\bin;C:\OrCAD\OrCAD_16.6_Lite\OpenAccess\bin\win32\opt;C:\OrCAD\OrCAD_16.6_Lite\tools\bin;C:\OrCAD\OrCAD_16.6_Lite\tools\Capture;C:\OrCAD\OrCAD_16.6_Lite\tools\PSpice;;C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0
		PWD = D:\working\Z1_Victor\STM32\STM32Cube_FW_F3_V1.10.0_temp\Projects\STM32F3348-Discovery\Examples\HRTIM\HRTIM_BuckBoost_AN4449\SW4STM32\STM32F3348-Discovery\Debug
		TOOLCHAIN_PATH = C:\Program Files (x86)\Atollic\TrueSTUDIO for STM32 9.2.0\ARMTools\bin

C/C++ General:
	Paths and Symbols:
		Includes:
			GNU C
				../../Inc
				../../../../../../../Drivers/CMSIS/Device/ST/STM32F3xx/Include
				../../../../../../../Drivers/STM32F3xx_HAL_Driver/Inc
				../../../../../../../Drivers/BSP/STM32F3348-Discovery
				../../../../../../../Drivers/CMSIS/Include
