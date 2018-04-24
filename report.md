# Relatório

## Resultados dos testes

![100Reads](http://i.imgur.com/Y39YAZ3.png)
![100Writes](http://i.imgur.com/LDmVz5S.png)
![30Writes](http://i.imgur.com/irZvh5r.png)

## Análise dos resultados

Pelos testes que efetuamos ao longo do desenvolvimento da quinta parte do projeto, podemos concluir que os testes de carga 100Reads e 100Writes executam muito mais rapidamente que o teste de carga 30Writes devido à politica otimista da FénixFramework que assume que irão existir mais Reads do que Writes, fazendo com que uma totalidade de testes de Reads ou de Writes seja rápida mas tornando um teste de carga com apenas 30% de Writes mais lento pois o FénixFramework tem de limpar tudo e voltar atrás.




