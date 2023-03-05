## Introdução ao Git e GitHub
Git é um sistema de controle de versão distribuído que permite que várias pessoas trabalhem juntas em um projeto. Ele permite que você acompanhe as alterações em seus arquivos, reverta a um estado anterior, ramifique-se em diferentes versões e trabalhe em colaboração com outros desenvolvedores.

GitHub é uma plataforma de hospedagem de código fonte baseado no Git que permite que você armazene, compartilhe e gerencie seu código-fonte. É uma plataforma muito popular e amplamente utilizada para desenvolvimento colaborativo.

Neste guia, vamos apresentar os principais conceitos e comandos do Git e GitHub para ajudá-lo a começar a usar essas ferramentas no desenvolvimento de seus projetos.

Instalação
Antes de começar a trabalhar com Git e GitHub, você precisará instalá-los em sua máquina. Existem várias maneiras de fazer isso, dependendo do seu sistema operacional. Aqui estão alguns links úteis para ajudá-lo a começar:

Git
GitHub Desktop
Configuração inicial
Após a instalação do Git, você precisará fazer algumas configurações iniciais. Isso inclui definir seu nome e endereço de e-mail, que serão usados para identificar você em suas contribuições ao projeto.

Para configurar seu nome e endereço de e-mail, abra o terminal e execute os seguintes comandos:

python
Copy code
git config --global user.name "Seu nome aqui"
git config --global user.email "Seu e-mail aqui"
Comandos básicos do Git
Aqui estão alguns dos comandos básicos do Git que você precisará conhecer para começar a trabalhar com o sistema de controle de versão:

git init
O comando git init é usado para inicializar um novo repositório Git em um diretório existente. Isso cria um novo subdiretório oculto chamado .git, que contém todos os arquivos necessários para o controle de versão.

git add
O comando git add é usado para adicionar um arquivo ao índice (também conhecido como área de preparação) para o controle de versão. Você pode adicionar um arquivo específico ou adicionar todos os arquivos em um diretório usando o . caractere.

csharp
Copy code
git add arquivo.txt
git add .
git commit
O comando git commit é usado para criar uma nova revisão no histórico de versão. Ele grava uma mensagem de confirmação que descreve as alterações que você fez.

sql
Copy code
git commit -m "Adicionando arquivo.txt"
git status
O comando git status é usado para ver o status atual do seu repositório. Ele informa quais arquivos estão em rastreamento, quais arquivos foram modificados e quais arquivos estão prontos para serem confirmados.

lua
Copy code
git status
git log
O comando git log é usado para exibir o histórico de confirmações em seu repositório. Ele mostra informações como a mensagem de confirmação, o autor, a data e a hora da confirmação.

bash
Copy code
git log