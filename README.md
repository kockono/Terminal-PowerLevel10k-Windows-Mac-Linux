# Terminal power level10k en Windows y VsCode (BUILD)
Mac
Windows
Linux

## VsCode
![image](https://user-images.githubusercontent.com/55373948/235842143-2ff6dcfc-bf5e-4fa7-8ddf-b50302bd5df2.png)
## Windows
![image](https://user-images.githubusercontent.com/55373948/235842288-68bf5126-f322-4363-94a6-da47d9fb6058.png)

### 1. Descargar Font 
https://www.nerdfonts.com/font-downloads
### 2. Instalar Wsl 
Abrir Terminal `PowerShell`
```sh
wsl --install
```
### 3. Selecionar distro y version 2
```sh
wsl --set-version Ubuntu 2
```
### 5. Instalar Powerlevel10k dentro de la terminal de ubuntu
```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ~/powerlevel10k
echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```
### Instalar Oh My Zh
```sh
git clone --depth=1 https://github.com/romkatv/powerlevel10k.git ${ZSH_CUSTOM:-$HOME/.oh-my-zsh/custom}/themes/powerlevel10k
```

### Instalar PowerLevel10k en Mac
```sh
brew install romkatv/powerlevel10k/powerlevel10k
echo "source $(brew --prefix)/opt/powerlevel10k/powerlevel10k.zsh-theme" >>~/.zshrc
```
### Change font size terminal in VsCode
![image](https://user-images.githubusercontent.com/55373948/235843152-796b2657-96a0-4d12-99fb-81c39742a51f.png)

