<h1>Validador de certificados digitais</h1>
Para realizar a compilação do binario basta fazer a clonagem do repositório e realizar o seguinte comando:

Linux/Windows
```
go build main.go
```

Para realizar a execução do arquivo sem compilar, Exemplo:

```
go run main.go <urls.txt>
```
Apos execução o mesmo irá gerar dois arquivos de output para uma melhor visualização: 

```
validadas.txt e invalidadas.txt
```
