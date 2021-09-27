# Conversão temperatura

## Construir a imagem

* docker image build -t edsontanaka/conversao-temperatura:1 .

## Executar o container

* docker run -d -p 8080:8080 edsontanaka/conversao-temperatura:1

## Listar os containers

* docker container ls

## Remover o container

* docker container rm -f 827eee3979834 (id do container)
