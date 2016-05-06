# Rails 開発環境構築

## Ruby のインストール

* rbenv のインストール

```
$ git clone git://github.com/sstephenson/rbenv.git .rbenv
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
$ echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
$ exec $SHELL
$ git clone git://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
```
* ruby のインストール

```
$ rbenv install -l
$ rbenv install 2.3.0
$ rbenv versions
$ rbenv global 2.3.0
$ ruby -v
```

## Rails のインストール

```
$ gem install rails
$ rails -v
```
