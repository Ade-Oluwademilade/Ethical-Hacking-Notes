An SMB relay attack **allows us to relay SMB authentication requests to another host, gaining access to an authenticated SMB session if the user has access and network logins are allowed on the target host**. If the user has administrator access in the target host, it is possible to execute arbitrary commands.

![](https://i.imgur.com/uxIHt98.png)

### How does this Attack work

First of all we need to be sure that that SMB signing is disabled, we can do this by using nmap as shown below

![](https://i.imgur.com/OjIsj29.png)

