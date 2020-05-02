# vagrant_wireguard
vagrantの中にwireguardをインストールできます。

## How to use
fedora 32以降でないとwireguardが使えないため、システムをアップグレードします。
しばらくお待ちください。
インストールし終わると再起動を行うので、
```
# dnf -y install wireguard-tools
```
と実行してください。

その後はwireguard公式の通りコマンドを打てば進みます。
[Wiregurad quick start](https://www.wireguard.com/quickstart/)
