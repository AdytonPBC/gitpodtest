# gitpodtest
Hello world project to test Gitpod

In order to run this project in a Gitpod container, you must be logged into this account then simply install the chrome
Gitpod extension (https://chrome.google.com/webstore/detail/gitpod-online-ide/dodmmooeoklaejobgleioelladacbeki)
or the firefox extension (https://addons.mozilla.org/firefox/addon/gitpod/) and click the Gitpod button.

In order to connect to the container via SSH (in order to open in local VSCode or terminal), you need to install the
local agent on your machine.  Simply run the following commands (OS dependent)

```
  # mac
  curl -OL https://gitpod.io/static/bin/gitpod-local-companion-darwin
  chmod +x ./gitpod-local-companion-*

  # linux
  curl -OL https://gitpod.io/static/bin/gitpod-local-companion-linux
  chmod +x ./gitpod-local-companion-*

  # windows
  curl -OL https://gitpod.io/static/bin/gitpod-local-companion-windows.exe
```

Run the command like any other shell script (`./gitpod-local-companion-<darwin|linux|windows>`) and then run
`ssh -F /tmp/gitpod_ssh_config <your-workspace-id e.g.apricot-harrier-####>` to access the container locally
from a container or use VSCode Container Development Extension and point it to `/tmp/gitpod_ssh_config` to
access the container.

Documentation for the local companion can be found here: https://www.gitpod.io/blog/local-app
Documentation for Gitpod generally is available here: https://www.gitpod.io/docs
