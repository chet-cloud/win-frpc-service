# Port Forward server in windows

1. run frpc as a server
2. checkout https://github.com/fatedier/frp
3. checkout https://github.com/winsw/winsw


# Usage

1. Clone the proejct into c:/

```shell
git clone https://github.com/chet-cloud/win-frp-service.git c:/frp
```

2. Install, start, stop, status, and restart the service

    - open cmd.exe and switch to the directory - c:/frp

    - input the following commands

```shell
    frpc-service install
    frpc-service start
    frpc-service stop
    frpc-service status
    frpc-service restart
```

or You can open the Services (win+run>services.msc) and operate on nginx service after install the service