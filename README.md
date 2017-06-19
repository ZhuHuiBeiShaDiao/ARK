# ZhuHuiBeiShaDiaoARK
Similar PChunter ano tools, was written on the play, now do you, process that most of them in the application layer. Not so good, perfect in the future.
# Support
Windows7 x64 only (The future will support xp(not vt) to Windows 10 The motherboard must support hardware virtualization)
# function
## 1.Process
ProcessImageName

ProcessPid

Parent ProcessPid

ProcessFullName

EPROCESS

Ring3 Access

File Vendor


ModuleInfo

  >ModuleFullName
  
  >ModuleBase
  
  >ModuleSize
  
  >ModuleFileVendor
  

 UnLinkModule(Remove Vad ,PebList,PeHeader full zero)
 
 UninstallModule

ThreadInfo

 >ThreadId
 
 >ETHREAD
 
 >Teb
 
 >ThreadEntrance
 
 >InModule
 
 >SwitchedNumber
 
 >ThreadStatus
 

TerminateThread

MandatoryTerminateThread

SuspendThread

ResumeThread


HandleInfo

 >HandleType(Name)
 
 >HandleName
 
 >HandleNumber
 
 >HandleObject
 
 >HandleType(Index)
 
 >HandleAccess
 
 >HandleProcess
 
 >CloseHandle
 
 >MandatoryCloseHandle
 


SuspendProcess

ResumeProcess

InjectDll

ProtectProcess ObRegisterCallbacks

ProtectProcess DKOM

TerminateProcess

MandatoryTerminateProcess

## 2.KernelModule

 ModuleName
 
 ModuleBase
 
 ModuleSize
 
 DriverObject
 
 ModuleFullName
 
 ServerName
 
 LoadCount
 
 FileVendor
 
 DelModuleFile
 
 DelModuleFileAndRegister
 
 Look MajorFunction
 
 Remove Irp Hook
 
## 3.Kernel

 SystemCallbacks(Handle ObRegisterCallbacks)
 
 Remove Hook
 
 Remove Hook(VT)
 
 FilterDriver
 
  >Remove
  
 DPCTimers
 
  >Remove
  
 WorkThread
 
 SystemThread
 
 TerminateThread
 
 FileSystem
 
  >Remove
  

KernelHook

 SSDT
 
 >Remove Hook
 >Remove Hook(VT)
 
 ShadowSSDT
 
 >Remove Hook
 
 >Remove Hook(VT)
 
 KernelHook
 
 >Remove Hook
 
 ObjectHook
 
 >Remove Hook
 
 Interrupt Descriptor Table
 
 >Remove Hook
 
## 4.Ring3 Hook

 MessageHook
 
 >Remove Hook
 
 ProcessHook
 
 >Remove Hook
 
 KernelCallbackTable
 
## 5.NetWork

 Port
 
 Tcpip
 
 Tdx
 
 Tdi
 
 Ndis
 
# Design
 VS2015(MFC)+WDK10
 
 IntelVT:https://github.com/tandasat/DdiMon 
 
 IntelVT:https://github.com/ZhuHuiBeiShaDiao/PFHook 
 
 AMDVT:https://github.com/tandasat/SimpleSvm 
 

# Thanks

 My parents
 
 Miss Chen
 
 SatoshiTanda:https://github.com/tandasat 
 
 BlackBone:https://github.com/DarthTon/Blackbone 
 
 XiaoBao:http://bbs.pediy.com/thread-212786.htm 
 
 EP_X0FF:http://www.kernelmode.info/forum 
 
 Mengwuji:http://www.mengwuji.net 
 
 Tesla.Angela:http://www.m5home.com 
 
 Linxer:http://www.xuetr.com 
 
 Winker:http://bbs.pediy.com/thread-166427.htm 
 
 # License
 
Copyright (C) 2017 Anyone

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.


# This project is still in development
 
