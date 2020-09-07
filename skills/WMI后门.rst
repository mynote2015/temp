WMI后门
===========================

WMI后门


解析APT29的无文件WMI和PowerShell后门
-----------------

`解析APT29的无文件WMI和PowerShell后门`_

安全公司Mandiant观察到APT29使用了一款名为POSHSPY的后门工具。POSHSPY使用了WMI（Windows Management Intrumentation，Windows管理工具）和PowerShell脚本，这也是该组织经常使用的两种工具。在调查过程中，Mandiant发现APT29将POSHSPY作为辅助后门使用，以便在主后门失效后重新夺回目标控制权。

.. _解析APT29的无文件WMI和PowerShell后门: https://www.anquanke.com/post/id/85851


Abusing Windows Management Instrumentation (WMI) to Build a Persistent, Asyncronous, and Fileless Backdoor
-----------------

`Abusing Windows Management Instrumentation (WMI) to Build a Persistent, Asyncronous, and Fileless Backdoor`_

As technology is introduced and subsequently deprecated over time in the Windows operating system, one powerful technology that has remained consistent since Windows NT 4.01 and Windows 952 is Windows Management Instrumentation (WMI). Present on all Windows operating systems, WMI is comprised of a powerful set of tools used to manage Windows systems both locally and remotely. 

.. _Abusing Windows Management Instrumentation (WMI) to Build a Persistent, Asyncronous, and Fileless Backdoor: https://www.blackhat.com/docs/us-15/materials/us-15-Graeber-Abusing-Windows-Management-Instrumentation-WMI-To-Build-A-Persistent%20Asynchronous-And-Fileless-Backdoor-wp.pdf