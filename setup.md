

---
#### X11 connection rejected because of wrong authentication

Anything installed with Snap won't work. So xeyes and xclock might work, but a new install of chromium-browser or firefox on Ubuntu won't.
The workaround is to simply do: export XAUTHORITY=$HOME/.Xauthority before running the remote X11 application.

```
export XAUTHORITY=$HOME/.Xauthority
```
