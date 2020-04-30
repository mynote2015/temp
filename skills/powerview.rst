powerview
===========================

powerview


powerview github
-----------------

`powerview github master`_

`powerview github dev`_

.. _powerview github master: https://github.com/PowerShellMafia/PowerSploit/blob/master/Recon/PowerView.ps1#L13403
.. _powerview github dev: https://github.com/PowerShellMafia/PowerSploit/blob/dev/Recon/PowerView.ps1



powerview command
-----------------
powershell收集域内信息

PS C:\Users\Administrator> Get-ExecutionPolicy
Restricted

PS C:\Users\Administrator> Set-ExecutionPolicy Unrestricted
执行策略更改
执行策略可以防止您执行不信任的脚本。更改执行策略可能会使您面临 about_Execution_Policies
帮助主题中所述的安全风险。是否要更改执行策略?
[Y] 是(Y)  [N] 否(N)  [S] 挂起(S)  [?] 帮助 (默认值为“Y”): y

PS C:\Users\Administrator> Get-ExecutionPolicy
Unrestricted

但是如果我们只有cmd命令下,并且策略无法更改怎么办？？？
powershell -exec bypass "import-module c:\powershell.ps1;Get-NetUser"

PS C:\> import-module .\powerview.ps1

Get-NetDomain	//获取当前的域名称
Get-Netuser	//返回所有域内成员的详细信息
Get-NetDomainController	//获取所有的域内的控制器信息
Get-NetComputer	//获取所有域内机器的名称
Get-Netshare	//获取域内的所有的网络共享
Get-NetRDPSESSION	//获取指定服务的远程连接信息
Get-NetProcess	//获取进程的详细信息
Get-ADObJECT	//获取活动目录的信息
Get-ADTrust	//获取域信任关系
Invoke-ProcessHunter	//Query the process lists of remote machines, searching for processes with a specific name or owned by a specific user.
Invoke-ShareFinder	//This function finds the local domain name for a host using Get-NetDomain,queries the domain for all active machines with Get-NetComputer, then for each server it lists of active shares with Get-NetShare. Non-standard shares can be filtered out with -Exclude* flags.
Invoke-FileFinder	//This function finds the local domain name for a host using Get-NetDomain,queries the domain for all active machines with Get-NetComputer, grabs the readable shares for each server, and recursively searches everyshare for files with specific keywords in the name.If a share list is passed, EVERY share is enumerated regardless of other options.
Get-ADDefaultDomainPasswordPolicy	//查询域密码策略
Get-ObjectAcl	//Returns the ACLs associated with a specific active directory object.
Get-NetOU	//获取域中OU信息
Get-NetGroup	//获取所有域内组和组成员信息
Get-NetFileServer	//根据SPN获取当前域使用的文件服务器
Get-NetSession	//获取在指定服务器存在的Session信息
Get-NetGPO	//获取域所有组策略对象
Get-DomainPolicy	//获取域默认或域控制器策略
Invoke-UserHunter	//搜索网络中域管理员正在使用的主机
Get-NetLocalGroup	//Gets a list of all current users in a specified local group,or returns the names of all local groups with -ListGroups.
Invoke-EnumerateLocalAdmin	//This function queries the domain for all active machines with Get-NetComputer, then for each server it queries the local Administrators with Get-NetLocalGroup.









