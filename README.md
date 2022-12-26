# pioadmin

Tool to manage pilvio.com platform.

## Install
### Linux
Download the latest release from github.com:
```bash
wget https://github.com/pilvio-com/pioadmin/releases/download/${RELEASE}/pioadmin_${RELEASE}_${OS}_${ARCH}.tar.gz -O - |tar zx

mv pioadmin_* pioadmin
chmod +x pioadmin
mv pioadmin to /usr/local/bin
```

### Mac OSX

```bash
brew tap pilvio-com/homebrew-tap
brew install pioadmin
```
 ## First run

 You need to have configuration file to use the tool. To create one, run:
 ```bash
 pioadmin config create
 ```