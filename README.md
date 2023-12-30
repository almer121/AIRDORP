## How to generate wallet?
### Install dependencies
```
sudo apt update && sudo apt list --upgradable && sudo apt upgrade -y
```
```
sudo apt install libfuse2
```
### Download wallet installer
```
wget https://github.com/OwshenNetwork/owshen/releases/download/v0.1.0/Owshen_v0.1.0_x86_64.AppImage
```
```
chmod +x Owshen_v0.1.0_x86_64.AppImage
```

_Make new Wallet_ 
```
./Owshen_v0.1.0_x86_64.AppImage init
```
_Show Recovery_
```
./Owshen_v0.1.0_x86_64.AppImage init --mnemnonic "Your Phrase Wallet"
```

_to view wallet information_
```
./Owshen_v0.1.0_x86_64.AppImage info
```
