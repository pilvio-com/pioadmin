# pioadmin

Tool to manage pilvio.com platform.

## Install
### Linux
Download the latest release from github.com:
```bash
export RELEASE="0.1.2"
export OS="linux"
export ARC="amd64"

wget https://github.com/pilvio-com/pioadmin/releases/download/${RELEASE}/pioadmin_${RELEASE}_${OS}_${ARCH}.tar.gz -O - |tar zx

chmod +x pioadmin
mv pioadmin /usr/local/bin
```
Update the exported variables according to you system.

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