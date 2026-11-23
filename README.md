# ATP07 - Versionamento de Dados e Modelos

## Pré-requisitos
- Git
- Python 3.10 ou superior
- DVC 3

## Armazenamento DVC
O armazenamento remoto utilizado é a pasta irmã dvc-storage.

Para verificar:
dvc remote list

## Restaurar uma versão anterior
git clone [URL_DO_REPOSITORIO](https://github.com/juliocmarinho/aula-ml)
git switch --detach modelo-r1
dvc pull
