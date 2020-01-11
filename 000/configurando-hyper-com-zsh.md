# Configurando Hyper com zsh

## Abrir o Hyper
    * menu > edit > preference

## Fonte 
* fontSize: xx

## Bash no Windows
* C:\\Windows\\System32\\bash.exe
* Color em `shell:'',`
```js
// PowerShell on Windows
// - Example: `C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe`
shell: '',
```
* Fazer reload

## Inicializando o Hyper com zsh 
* Abrir o terminal do Ubuntu
* Execurar: l
* Executar: vim .bashrc
* i
* colar embaixo de `for exemples`: bash -c zsh
* :x
* source .zshrc tab + enter `reload`

## Bônus
### Vim
* i `editar`
* :x `salva e sai`
* :q `sai`
* :q! `sai sem salvar`
* v `modo visual`