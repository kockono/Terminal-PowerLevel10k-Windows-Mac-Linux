# Terminal power-level10k  Windows, Mac and VsCode (BUILD)
1. Mac
2. Windows
3. Linux
4. Cmder Windows

## VsCode
![image](https://user-images.githubusercontent.com/55373948/235842143-2ff6dcfc-bf5e-4fa7-8ddf-b50302bd5df2.png)
## Windows
![image](https://user-images.githubusercontent.com/55373948/235842288-68bf5126-f322-4363-94a6-da47d9fb6058.png)

### 1. Descargar Fonts
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
### Change font-size and font terminal in VsCode
![image](https://user-images.githubusercontent.com/55373948/235843152-796b2657-96a0-4d12-99fb-81c39742a51f.png)

### Permite tener cmd globalmente 
```sh
cd C:\cmder
```

```sh
.\cmder.exe /REGISTER ALL
```
![image](https://github.com/kockono/Terminal-PowerLevel10k-Windows-Mac-Linux/assets/55373948/4c39f5bb-6fc5-424a-af20-dd07aa22b23a)

### Agregar Cmder en vscode Settings.json
```json
"terminal.integrated.profiles.windows": {
  "cmder": {
    "path": "C:\\WINDOWS\\System32\\cmd.exe",
    "args": ["/K", "C:\\cmder\\vendor\\bin\\vscode_init.cmd"]
  }
},
"terminal.integrated.defaultProfile.windows": "cmder"
```
