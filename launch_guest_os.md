# ゲスト OS のイメージ取得 ~ 起動

## Vagrant Box の用意

* Vagrant Box の用意

```
$ vagrant init centos/7
```

* private network の設定
    * Vagrantfile の private_network のコメントアウトを外す

```Vagrantfile
  # Create a private network, which allows host-only access to the machine
  # using a specific IP.
  config.vm.network "private_network", ip: "192.168.33.10"
```

* 起動

```
$ vagrant up
```

* ログイン

```
$ vagrant ssh
```
