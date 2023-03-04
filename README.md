# Clean JupyterLab Workspace in the Could

Click on the below link to launch: 

[![Binder](https://raw.githubusercontent.com/beginnerSC/sandbox-stable/11f641c8f9b95d3df0f0e7df12abf43ea13ae3c2/binder/binder-logo.svg)](https://mybinder.org/v2/gh/beginnerSC/sandbox-lite/master?urlpath=lab)


gc is broken. rewrite with the following: 

```
import rsa

publicKey, privateKey = rsa.newkeys(512)
 
message = "hello geeks"
encrypted = rsa.encrypt(message.encode(), publicKey)
rsa.decrypt(encrypted, privateKey).decode()
```

rename .binder as binder? 
