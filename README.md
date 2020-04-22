# Projeto_Integrador















Projeto em Grupo para apresentação no dia 05/05/2020 



Introdução
Premissas:  

Será fornecido um APP feito em NodeJS que escreve e lê arquivos no S3
As configurações necessárias para esse app funcionar serão definidas por variáveis de ambiente (environment)

O objetivo:

Criar as duas máquinas de app na AWS junto com uma máquina que conterá o Jenkins (para facilitar a evolução
fora da sala de aula)
Com o jenkins no ar elas deverão construir as pipelines clonando o projeto, executando os testes e configurando 
com as devidas variáveis de ambiente e por fim publicando no ambiente de destino: Prod ou Homolog

Resultados Esperados:

Com os aplicativos NodeJS no ar as alunas devem observar a url /healthcheck de cada um dos ambientes (homolog e prod) para testar se foram ou não carregadas as imagens com sucesso na S3.
