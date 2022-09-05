# Busca de ip e servidores 

O codigo pode ser utilizado para busca de ips e servidores dos sites informados, escrito totalmente em Go a pesquisa deve ser realizada em linha de comando.

#

## Como executar

Bem simples dentro da pasta do arquivo, basta rodar o programa da seguinte maneira:

```
go run main.go ip --host (site)
```
Para a busca do Ip do site, exemplo:
```
go run main.go ip --host amazon.com.br
```

### E para a busca de servidor

Basta usar o comando: 

```
go run main.go servidores --host (site)
```
Exemplo:

```
go run main.go servidores --host amazon.com.br
```
