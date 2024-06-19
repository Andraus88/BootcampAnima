Bootcamp Anima Base2
Desafio:

Exercício - Automação de testes funcionais de interface (Web)

Automatize o caso de teste abaixo, projetado para a funcionalidade “Criar Tarefa” do
sistema “Mantis”.
Utilizar a linguagem de programação Java, a biblioteca Selenium WebDriver para manipular
a interface, a biblioteca JUnit para orquestrar o testes e o browser Google Chrome.
Sobre o Mantis: É uma ferramenta de rastreamento de problemas e bugs de software. É
usada para reportar e monitorar defeitos de software, gerenciar projetos e colaborar entre
equipes de desenvolvimento.
___________________________________________________________________

CT01 - Criar tarefa com sucesso preenchendo todos os campos do formulário.
Pré condições:

1. Usuário deverá ter permissão para criação de tarefas em um projeto
Passos:
1. Acessar o Mantis (https://mantis-prova.base2.com.br/)
2. Efetuar login (usuario: grupoXX, senha 123456, onde XX é o número do seu grupo)
3. Clicar em “Criar tarefa” no menu lateral
4. Selecionar uma categoria
5. Selecionar uma frequência
6. Selecionar uma prioridade
7. Preencher o campo “Resumo”
8. Preencher o campo “Descrição”
9. Preencher o campo “Passos para reproduzir”
10. Preencher o campo “Informações adicionais”
11. (Opcional) Inserir anexo em “Enviar arquivos”
12. Clicar em “Criar nova tarefa”

Resultado esperado:
1. O sistema deve exibir a mensagem “Operação realizada com sucesso.”
2. A tarefa é criada com sucesso contendo todas as informações fornecidas no
cadastro
