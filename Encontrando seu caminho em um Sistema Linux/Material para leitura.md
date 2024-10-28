<h1>Lição 1</h1>
<h2>Introdução</h2>
As distribuições Linux modernas oferecem uma ampla gama de interfaces gráficas, mas o uso da linha de comando (ou shell) é fundamental para administradores de sistemas. O shell permite a comunicação baseada em texto entre o usuário e o sistema operacional. Existem diferentes tipos de shells no Linux, com o Bash sendo o mais comum.

<h2>Estrutura do Prompt</h2>
O prompt da linha de comando em diferentes distribuições segue um padrão que inclui:
username: Nome do usuário que está executando o shell.<br>
hostname: Nome do computador.<br>
current_directory: Diretório atual onde o shell está.<br>
shell_type: O símbolo $ indica um usuário comum, enquanto # indica o superusuário root.<br>

<h2>Estrutura da Linha de Comando</h2>
A maioria dos comandos segue esta estrutura:<br>
comando: O programa a ser executado.<br>
opção(ões): Modificam o comportamento do comando (como -l).<br>
argumento(s): Dados adicionais necessários pelo comando (como arquivos ou diretórios).

<h2>Tipos de Comando</h2>
Comandos Internos: São parte do próprio shell, como cd e export.<br>
Comandos Externos: São arquivos executáveis armazenados no sistema, como ls ou cat.

<h2>Citações no Bash</h2>
O shell Bash oferece três tipos de aspas que controlam como caracteres especiais e variáveis são manipulados:<br>
Aspas Duplas (" "): Mantêm o valor especial de variáveis, mas ignoram outros caracteres especiais.<br>
Aspas Simples (' '): Tratam todo o conteúdo entre aspas como texto literal, sem interpretar variáveis.<br>
Caracteres de Escape (): Precedem caracteres especiais, removendo seus significados especiais.<br>

<h1>Lição 2</h1>
<h2>Introdução</h2>
Todos os shells gerenciam um conjunto de informações de status ao longo das sessões do shell. Essas informações de tempo de execução podem mudar durante a sessão e influenciar o comportamento do shell. Esses dados também são usados pelos programas para determinar aspectos da configuração do sistema. A maioria desses dados é armazenada nas chamadas variáveis, que abordaremos nesta lição.

<h2>Variáveis</h2>
As variáveis no shell são espaços para armazenar dados, como texto ou números, e podem ser acessadas posteriormente pelo nome, facilitando o uso em sessões e comandos do shell. Existem dois tipos principais de variáveis no Linux:

Variáveis locais: São específicas do processo atual do shell e não podem ser acessadas por programas ou subprocessos iniciados depois de sua criação. São úteis para dados temporários e específicos de uma sessão.

Variáveis de ambiente: São acessíveis tanto na sessão de shell quanto em subprocessos derivados dessa sessão. Servem para passar dados de configuração, como o PATH ou USER, e são escritas em letras maiúsculas por convenção. O conjunto dessas variáveis define o "ambiente" do sistema, carregando configurações fundamentais para o usuário e o sistema.

<h2>Manipulação de variáveis</h2>
Como administrador do sistema, você precisará criar, modificar ou remover variáveis locais e de ambiente.

<h2>Trabalhando com variáveis locais</h2>
Você pode configurar uma variável local usando o operador = (igual). Uma atribuição simples criará uma variável local:

greeting=hello

É possível exibir qualquer variável usando o comando echo. O comando geralmente exibe o texto na seção de argumentos:

echo greeting<br>
greeting

Para acessar o valor da variável, você terá de usar $ (cifrão) na frente do nome da variável.

echo $greeting<br>
hello

Para remover uma variável, usamos o comando unset:

echo $greeting<br>
hey<br>
unset greeting<br>
echo $greeting<br>

<h2>Trabalhando com variáveis globais</h2>
Para disponibilizar uma variável local para subprocessos, podemos transformá-la em variável de ambiente. Usamos para isso o comando export. Quando ele é invocado junto ao nome da variável, essa variável é adicionada ao ambiente do shell:

greeting=hello
export greeting

