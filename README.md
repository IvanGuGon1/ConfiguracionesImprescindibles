# ConfiguracionesImprescindibles

## MongoDB 3.2 en Ubuntu server 16.04

https://www.digitalocean.com/community/tutorials/como-instalar-mongodb-en-ubuntu-16-04-es

## Configuracion básica git

https://git-scm.com/book/es/v1/Empezando-Configurando-Git-por-primera-vez

## Sublime desde repositorios

Recursos, enlaces e info de interes

- Instalacion sublime2

sudo add-apt-repository ppa:webupd8team/sublime-text-2 sudo apt-get update sudo apt-get install sublime-text

- Instalacion sublime3

sudo add-apt-repository ppa:webupd8team/sublime-text-3 sudo apt-get update sudo apt-get install sublime-text-installer

- Ejecucion

subl

## Jupyter Notebooks desde Ubuntu Server sin GUI

Para Python 2.7, instalar ipython 5.0 LTS ( pip install ipython==5.0 )
Para Python 3.5, instalar ipython 6.0 +

sudo apt-get -y install ipython ipython-notebook
sudo -H pip install jupyter

-- JUPYTER NOTEBOOKS SSH TUNNELING

-En el servidor 

ipython notebook --no-browser --port=8889

o

jupyter notebook --no-browser --port=8889

-En local

ssh -N -f -L localhost:8888:localhost:8889 usuario_remoto@host_remoto

-- Abrir navegador en local

localhost:8888
Introducir token
