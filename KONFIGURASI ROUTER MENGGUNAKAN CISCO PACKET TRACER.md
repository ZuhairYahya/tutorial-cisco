# ROUTER CONFIGURATION USING CISCO PACKET TRACER
![Topologi](https://1.bp.blogspot.com/-uzEfR_333Cs/XR70ZiV6whI/AAAAAAAADJo/JRLPpArQ_zUdtpOtKUriSlqkoS1wiO4LACLcBGAs/s1600/topologi.PNG)
Configure router 1 by looking at the interface used. **Make sure not to enter the wrong IP Address used. And notice how many Fast Ethernets you use Fast Ethernet**

Perform configuration

**Router 1**

*Router>enable*
*Router#configure terminal*
*Router(config)#int fa1/0*
*Router(config-if)#ip address 10.10.10.2 255.255.255.252*
*Router(config-if)#no sh*
*Router(config-if)#ex*
*Router(config)#int fa0/0*
*Router(config-if)#ip address 12.12.12.2 255.255.255.252* 
*Router(config-if)#no sh*
*Router(config-if)#ex*
*Router(config)#*

**Router 0**

*Router>enable*
*Router(config)#int fa0/0*
*Router(config-if)#ip address 10.10.10.1 255.255.255.252*
*Router(config-if)#no sh*
*Router(config-if)#ex*
*Router(config)#int fa1/0*
*Router(config-if)#ip address 192.168.1.1 255.255.255.224*
*Router(config-if)#no sh*
*Router(config-if)#ex*
*Router(config)#*

**Router 2**

Router>enable
*Router#configure terminal*
*Router(config)#int fa0/0*
*Router(config-if)#ip address 12.12.12.1 255.255.255.252*
*Router(config-if)#no sh*
*Router(config-if)#ex*
*Router(config)#int fa1/0*
*Router(config-if)#ip address 192.168.2.1 255.255.255.224*
*Router(config-if)#no sh*
*Router(config-if)#ex*
*Router(config)#*

## INFORMATION

**enable** : is a privileged mode so that users can configure.

**configure terminal** : is a global configuration mode where users can configure.

**int fa1/0** 		: because it uses a Fast Ethernet cable, when using the Fast Ethernet configuration on port 1/0.

**no sh**			: no shutdown, is a command to turn on the interface administratively.

**ex** 			: is a command to exit (exit).

**author** : 
**Zuhair Yahya**