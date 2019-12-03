# Django Girls setups
Uma compilação de steps para configurar o ambiente para o workshop


## MacOs

### Instale um terminal legal
https://www.iterm2.com/downloads.html

### Instale uma IDE

Sugestão: [Pycharm](https://www.jetbrains.com/pycharm/download/#section=mac), [vscode](https://code.visualstudio.com/docs?dv=osx), [sublime](https://www.sublimetext.com/)

### Instale o Homebrew

[Siga as instruções](https://brew.sh/index_pt-br)

### Instalando o python3: 
Use o comando para verificar os pacotes disponíveis de python

`brew search python`

O terminal irá exibir algo assim:

```
Output
app-engine-python          micropython                python3                 
boost-python               python                     wxpython                 
gst-python                 python-markdown            zpython                  
homebrew/apache/mod_python               homebrew/versions/gst-python010        
homebrew/python/python-dbus              Caskroom/cask/kk7ds-python-runtime     
homebrew/python/vpython                  Caskroom/cask/mysql-connector-python
```
Python 3 estará entre os itens da lista. Vamos instalá-lo:

`brew install python3`

para instalar pacotes, tente:

`pip3 install package_name`

### Install a Virtual Env

Na sua home crie o seguinte diretório:

`mkdir Environments`

Entre na pasta assim:

`cd Environments`

Assim que você entrar no diretório no qual queira qeu seus envs estejam, você pode criar um environment rodando o seguinte comando:mmand:

`python3.7 -m venv my_env``

Para usar este envm você precisa ativá-lo, o qual você pode fazer rodando o seguinte comando:

`source my_env/bin/activate`


[Reference](https://www.digitalocean.com/community/tutorials/how-to-install-python-3-and-set-up-a-local-programming-environment-on-macos)
