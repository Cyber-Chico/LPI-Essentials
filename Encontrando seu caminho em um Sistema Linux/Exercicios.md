<h1>Lição 1</h1>

<h2>1 - Divida as linhas abaixo nos componentes de comando, opção(ões)/parâmetro(s) e argumento(s):</h2>
ls -l /etc

Comando:ls

Opção:-l 

Argumento:/etc

ls -l -a

Comando:ls

Opção: -l -a

Argumento: Nenhum (o comando está sendo executado no diretório atual)

cd /home/user

Comando:cd 

Opção: Nenhuma

Argumento: /home/user

<h2>2 - Descubra que tipo são os seguintes comandos:</h2>
cd: shell embutido (ou built-in). O comando cd é parte integrante do shell.

cat: comando externo. O cat é um programa externo localizado no sistema de arquivos (geralmente em /bin/cat).

exit: shell embutido (ou built-in). O comando exit é outro exemplo de comando integrante do shell.

<h2>3 - Resolva os seguintes comandos que usam aspas:</h2>
touch "$USER"<br>
Explicação: Esse comando cria um arquivo com o nome do usuário que está logado. A variável $USER contém o nome do usuário atual, e as aspas duplas garantem que o nome do usuário seja tratado como um único argumento, mesmo que tenha espaços.<br>
Resultado: O arquivo criado terá o nome do usuário, por exemplo, se o usuário for "carol", o arquivo será chamado carol.

touch 'touch'<br>
Explicação: As aspas simples tratam tudo dentro delas como texto literal. Portanto, esse comando cria um arquivo literalmente chamado touch, e não executa o comando touch dentro das aspas.<br>
Resultado: Um arquivo chamado touch será criado

<h2>4 - Com um comando e usando expansão de chaves no Bash (revise a página de manual do Bash), crie 5 arquivos numerados de 1 a 5 com o prefixo game( game1, game2, …​).</h2>
touch game{1..5}

<h2>5 - Exclua todos os 5 arquivos que você acabou de criar com apenas um comando, usando um caractere especial diferente (consulte Expansão de nome de caminho nas páginas de manual do Bash).</h2>
rm game{1..5} ou rm game*

<h2>6 - Existe alguma outra maneira de fazer dois comandos interagirem um com o outro? Quais são essas?</h2>
Sim, além de adicionar opções, outra maneira muito comum de fazer dois ou mais comandos interagirem no Bash é através de redirecionamento e pipe (|).

<h1>Lição 2</h1>
<h2>1 - Crie uma variável local number. </h2>
# number=(número desejado)

<h2>2 - Crie uma variável de ambiente ORDER usando um dos dois métodos acima.</h2>
ORDER="your_value"
export ORDER

export ORDER="your_value"

<h2>3 - Exiba o nome das variáveis e seu conteúdo.</h2>
echo $number<br>
echo $ORDER

<h2>4 - Qual o escopo das variáveis criadas anteriormente?</h2>
number: É uma variável local e, portanto, seu escopo é restrito ao shell atual onde foi definida. Ela não estará disponível em subprocessos iniciados a partir desse shell.

ORDER: É uma variável de ambiente, então seu escopo abrange o shell atual e todos os subprocessos gerados a partir dele. Isso permite que ORDER seja acessada em comandos ou scripts executados nesse shell e em seus subprocessos.

<h2>5 - Crie uma variável local nr_files e atribua o número de linhas encontrado no arquivo /etc/passwd. Dica: pesquise sobre o comando wc e substituição de comandos, e não se esqueça das aspas.</h2>
Para criar a variável local nr_files e atribuir a ela o número de linhas do arquivo /etc/passwd, você pode usar o comando wc -l junto com substituição de comandos. Aqui está como fazer:

nr_files="$(wc -l < /etc/passwd)"
Esse comando conta as linhas do arquivo /etc/passwd e armazena o resultado em nr_files. A substituição de comandos $(...) captura a saída do comando e atribui à variável. As aspas garantem que o valor seja tratado corretamente, mesmo que contenha espaços ou caracteres especiais.

<h2>6 - Crie uma variável de ambiente ME. Atribua a ela o valor de variável USER.</h2>
ME="$USER"
export ME

<h2>7 - Inclua o valor da variável HOME a ME, usando o delimitador :. Exiba o conteúdo da variável ME.</h2>
ME="$USER:$HOME"
export ME
echo "$ME"

<h2>8 - Usando o exemplo acima, crie uma variável chamada today e atribua a data de um dos fusos horários.</h2>
today="$(TZ='UTC' date)"<br>
echo "$today"

<h2>9 - Crie outra variável chamada today1 e atribua a ela a data do sistema.</h2>
today1="$(date)"

echo "$today1"

