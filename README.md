# Instalando o duckDB cli no Windows

O que é o DuckDB?

O DuckDB é um banco de dados relacional de código aberto, embarcado (similar ao SQLite), orientado a coluna, conhecido por sua velocidade e eficiência em consultas analíticas (OLAP). 

### Instalação do DuckDB no Windows

``` bash copy
winget install DuckDB.cli
```

Ao efetuar a instalação pelo winget, ele cria uma pasta em `C:\Users\jlsil\AppData\Local\Microsoft\WinGet\Packages\DuckDB.cli_Microsoft.Winget.Source...` colocar o arquivo `duckdb.exe` lá dentro e também adiciona no PATH do Windows.

Para testar se está tudo ok, execute os comandos abaixo:

``` bash copy
duckdb
```
![Alt text](image.png)

``` bash copy
duckdb --version
```
Para sair do shell do DuckDB, pressionar Control+Z.

Para verificar a versão:

``` bash copy
duckdb --version
```
![Alt text](image-1.png)


Referências:
https://duckdb.org/
https://duckdb.org/docs/installation/?version=latest&environment=cli&installer=binary&platform=win

