install erlang version 18 or higher.
You may need to install from source http://www.erlang.org/downloads

Or use [Homebrew](https://brew.sh):
```
brew install erlang
```

*NOTE*: due to a `brew` issue you need to open permission on the erlang
directory. Otherwise builds will fail with `eaccess` errors

```
chmod -R ug+rwX /usr/local/Cellar/erlang/
```

It depends on sed, the stream editor
```
brew install gnu-sed --with-default-names
```

Use git to download the software, then go into the testnet directory
```
git clone https://github.com/aeternity/testnet.git
cd testnet
mkdir data blocks
```
