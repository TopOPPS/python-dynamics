Make soap requests with a Dynamics CRM server. On-prem or online!

# NOTE - must escape the password before sending it in
```
password = password.replace('"', "&quot;")
password = password.replace("'", "&apos;")
password = password.replace('<', "&lt;")
password = password.replace('>', "&gt;")
password = password.replace('&', "&amp;")
```

# Installation

`pip install -r requirements.txt`

# Known Issues

We haven't made a package out of this, but if anyone out there uses this, please file an issue to let us know we should make it more installable.
