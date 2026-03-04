## 📚 Sobre este projeto
Este projeto faz parte da minha jornada de aprendizado em Python.
O objetivo foi praticar automação de tarefas utilizando Python, simulando o cadastro automático de produtos em um sistema a partir de uma base de dados CSV.
Ainda estou evoluindo na linguagem, e este repositório serve como registro prático do que estou aprendendo ao longo dos estudos.

Automação de Cadastro de Produtos com Python
📌 Descrição do Projeto
Este projeto tem como objetivo automatizar o cadastro de produtos em um sistema web utilizando Python.

Em muitas situações do mundo real, empresas precisam cadastrar grandes quantidades de informações em sistemas, como produtos, preços ou registros diversos. Quando esse processo é feito manualmente, ele pode levar horas ou até dias de trabalho, além de aumentar as chances de erro humano.

Para resolver esse problema, este projeto demonstra como criar uma automação capaz de controlar o mouse e o teclado do computador, executando tarefas automaticamente como se fosse um usuário realizando o processo manualmente.

🎯 Objetivo
Criar um script em Python que:

Abra o navegador
Acesse um site de cadastro
Faça login no sistema
Leia uma base de dados com produtos
Cadastre automaticamente cada produto no sistema
📂 Base de Dados
Os dados utilizados no projeto estão no arquivo:

produtos.csv
Esse arquivo contém uma lista de produtos que devem ser cadastrados no sistema.

Cada linha representa um produto com as seguintes informações:

Código do produto
Marca
Tipo
Preço unitário
Custo
Observação
A base de dados possui 264 registros, o que exigiria o preenchimento manual de 6 campos para cada produto, tornando o processo repetitivo e demorado.

⚙️ Funcionamento da Automação
Ao executar o programa, a automação realiza as seguintes etapas:

Abre o navegador
Acessa o site do sistema
Realiza o login com usuário e senha
Lê os dados do arquivo produtos.csv
Preenche automaticamente os campos do sistema
Envia o cadastro do produto
Repete o processo até que todos os produtos sejam cadastrados
🚀 Resultado Esperado
Ao final da execução do script, todos os produtos presentes na base de dados estarão cadastrados automaticamente no sistema, sem necessidade de intervenção manual.

Isso demonstra como automações podem economizar tempo, reduzir erros e aumentar a produtividade em tarefas repetitivas.
