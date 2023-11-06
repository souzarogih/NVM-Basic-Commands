
<h1 align='center'>Comandos básicos NVM</h1>
<h2>
    Gerenciador para várias instalações de node.js em um computador Windows.
</h2>

### >Comando para exibir a versão atual do node em execução.
`nvm current`
```
$ nvm current
 v18.17.1
```

### >Comando para instalar uma versão do node
`nvm install <version> [arch]`
```
$ nvm install 16.0.0
Downloading node.js version 16.0.0 (64-bit)...
Complete
Creating C:\Users\HigorSouza\AppData\Roaming\nvm\temp

Downloading npm version 7.10.0... Complete
Installing npm v7.10.0...

Installation complete. If you want to use this version, type

nvm use 16.0.0
```

### >Comando para listar as instalações do nodeJS existente na máquina
`nvm list`
```
 $nvm list

  * 18.17.1 (Currently using 64-bit executable)
    7.1.0
```

### >Comando para usar uma versão instalada
`nvm use <version> [arch]`
```
$ nvm use 7.1.0
Now using node v7.1.0 (64-bit)
```

### >Comando para listar a versão atual do nvm instalada
`nvm version`
```
$ nvm version
1.1.11
```


### >Comando para desinstalar uma versão do nodeJS instalada
`nvm uninstall <version>`
```
HigorSouza@DESKTOP-KCPSELH MINGW64
$ nvm list

  * 18.17.1 (Currently using 64-bit executable)
    16.0.0
    7.1.0

HigorSouza@DESKTOP-KCPSELH MINGW64
$ nvm uninstall 16.0.0
Uninstalling node v16.0.0... done

HigorSouza@DESKTOP-KCPSELH MINGW64
$ nvm list

  * 18.17.1 (Currently using 64-bit executable)
    7.1.0
```


### >Exemplo de uso
```
HigorSouza@DESKTOP-KCPSELH MINGW64
$ node -v
v18.17.1

HigorSouza@DESKTOP-KCPSELH MINGW64
$ nvm list

  * 18.17.1 (Currently using 64-bit executable)
    16.0.0
    7.1.0

HigorSouza@DESKTOP-KCPSELH MINGW64
$ nvm use 7.1.0
Now using node v7.1.0 (64-bit)

HigorSouza@DESKTOP-KCPSELH MINGW64
$ node -v
v7.1.0
```

## [Repositório nvm]
https://github.com/coreybutler/nvm-windows
https://github.com/nvm-sh/nvm#installing-and-updating


## [Link para download das versões]
https://github.com/coreybutler/nvm-windows/releases

## [Lista das versões]
https://nodejs.org/dist/