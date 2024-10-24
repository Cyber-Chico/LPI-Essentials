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
