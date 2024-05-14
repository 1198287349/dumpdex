
## Usage

CLI arguments base on [frida-tools](https://github.com/frida/frida-tools), you can quickly dump the foreground application like this:

```
frida-dexdump -FU
```

Or specify and spawn app like this:

```
frida-dexdump -U -f com.app.pkgname
```

When using, I suggest using the `-d, --deep-search` option, which may take more time, but the results will be more complete.



## Build and develop

```
make

```
## Build exe
```
pyinstaller --onefile -n frida-dexdump frida_dexdump/__main__.py
```
### Requires

See [requirements.txt](https://github.com/hluwa/FRIDA-DEXDump/blob/master/requirements.txt)


# dumpdex
