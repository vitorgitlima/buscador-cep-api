# Projeto Buscar Endereço por CEP

## Visão Geral
Este é um projeto simples que busca informações de endereço a partir de um número de CEP fornecido pelo usuário, usando requisições HTTP à API ViaCEP. O projeto também inclui a funcionalidade de salvar o resultado em um arquivo no formato JSON.

## Pré-requisitos
* Java Development Kit (JDK).
* IntelliJ ou Eclipse IDE.
* Conexão com a internet para fazer requisições à API ViaCEP

## Estrutura do Projeto
O projeto é dividido em três classes principais:

* Main.java: A classe principal que contém o método main. Ela interage com o usuário, recebe o CEP e coordena a busca e salvamento de endereço.

* ConsultaCep.java: Esta classe é responsável por fazer a requisição HTTP à API ViaCEP usando a biblioteca HttpClient e processar a resposta. Ela retorna um objeto Endereco com os detalhes do endereço.

* GeradorDeArquivo.java: Esta classe lida com a tarefa de salvar o objeto Endereco em um arquivo JSON.

## Exemplo de Saída
```json
{
"cep": "01001-000",
"logradouro": "Praça da Sé",
"complemento": "lado ímpar",
"localidade": "São Paulo",
"uf": "SP"
}
```

