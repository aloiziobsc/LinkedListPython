## Como rodar este projeto

1. Tenha o docker instalado [install Docker](https://www.docker.com/products/docker-desktop/)
2. Clone este repositório para sua máquina local
```
 git clone git@github.com:aloiziobsc/LinkedListPython.git
```
3. Navegue até o diretório do projeto:
 ```
 cd LinkedListPython
```
4. Use o seguinte comando no terminal para criar a imagem do container:
 ```
docker build -t linked-list-python .
```
5. Para rodar o container use o comando:
 ```
docker run -it linked-list-python
```
6. Para remover a imagem do container use o comando:
 ```
docker run -it --rm linked-list-python
```
