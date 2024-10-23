<h1> Lição 1</h1>
O Linux, criado em 1991 por Linus Torvalds e inspirado no Unix, é um dos sistemas operacionais mais populares, amplamente utilizado em várias plataformas, com base em uma comunidade global de desenvolvedores. As distribuições Linux são pacotes que combinam o kernel Linux com softwares específicos para atender a diferentes necessidades, como Debian, voltado para confiabilidade e liberdade de software, e Ubuntu, que foca na facilidade de uso. Empresas como Red Hat e SUSE oferecem distribuições Linux comerciais com suporte corporativo, enquanto projetos como CentOS e Fedora são variações gratuitas com foco em servidores e desktop, respectivamente.<br><br>

Sistemas embarcados, como o Raspberry Pi, utilizam versões de Linux para funções específicas em dispositivos inteligentes e automação. O Android, baseado em Linux, é amplamente usado em dispositivos móveis, oferecendo flexibilidade e integração com o ecossistema do Google.<br>

Na nuvem, o Linux domina, sendo a base de até 90% das cargas de trabalho. Plataformas como AWS e Google Cloud oferecem uma gama de distribuições Linux otimizadas para uso em infraestruturas como serviço (IaaS), permitindo provisionamento rápido de servidores virtuais baseados em Linux.<br>

<h2>Resumo</h2>
<strong>Nesta lição você aprendeu:</strong><br>
Quais distribuições o Linux tem.<br>
O que são sistemas embarcados Linux.<br>
Como os sistemas embarcados Linux são usados.<br>
Diferentes aplicações do Android.<br>
Diferentes usos de um Raspberry Pi.<br>
O que é Computação em Nuvem.<br>
Qual o papel do Linux na computação em nuvem.

<h1>Lição 2</h1>
A introdução explica que aplicativos em um sistema Linux são programas voltados para o usuário, com várias opções disponíveis para diferentes tarefas, como aplicativos de escritório, navegadores e editores de multimídia. O usuário deve escolher o melhor aplicativo para suas necessidades.<br>

<strong>Pacotes de software:</strong> Distribuições Linux vêm com aplicativos pré-instalados e repositórios contendo uma vasta gama de softwares que podem ser instalados com gerenciadores de pacotes, como o apt (Debian/Ubuntu) ou yum/dnf (Red Hat/Fedora). Esses sistemas de gerenciamento também resolvem dependências automaticamente.<br>

<strong>Instalação de pacotes:</strong> Para instalar um novo programa, como o figlet, o usuário pode pesquisar e instalar o pacote usando comandos como apt-get install ou yum install, dependendo da distribuição.<br>

<strong>Remoção de pacotes:</strong> Pacotes podem ser removidos com apt-get remove ou yum remove. Os arquivos de configuração geralmente são mantidos após a remoção do pacote.<br>

<strong>Aplicativos de escritório:</strong> As suítes de escritório mais comuns são o LibreOffice e o Apache OpenOffice, que incluem aplicativos como Writer (texto), Calc (planilhas) e Impress (apresentações). Ambos suportam os formatos do Microsoft Office e preferem o formato aberto ODF.<br>

<strong>Navegadores da web:</strong> Mozilla Firefox e Google Chrome (baseado no projeto de código aberto Chromium) são os navegadores mais utilizados no Linux.<br>

<strong>Multimídia:</strong> Aplicativos populares incluem o Blender para renderização 3D, GIMP para edição de imagens, Inkscape para gráficos vetoriais, e Audacity para edição de áudio.<br>

<strong>Programas de servidor:</strong> Servidores HTTP como Apache e Nginx lidam com requisições de páginas da web. Para gerenciamento de dados, bancos de dados como MariaDB e PostgreSQL são comuns.<br>

<strong>Compartilhamento de dados:</strong> O Samba permite compartilhamento de arquivos entre Linux e Windows, enquanto o NFS é usado para redes Linux.<br>

<strong>Linguagens de programação:</strong> Diversas linguagens são mencionadas, como C (para sistemas operacionais), JavaScript (para a web), Python (popular entre iniciantes) e PHP (para servidores web).<br>

<h2>Resumo</h2>
<strong>Nesta lição, você aprendeu:</strong><br>
Os sistemas de gerenciamento de pacotes usados ​​nas principais distribuições Linux.<br>
Aplicativos de código aberto que podem editar formatos de arquivo populares.<br>
Os programas de servidor subjacentes a muitos serviços importantes da Internet e da rede local.<br>
Linguagens de programação comuns e seus usos.<br>

<h1>Lição 3</h1>
O software livre refere-se a programas que garantem ao usuário quatro liberdades essenciais, que são:<br><br>

<strong>Liberdade 0:</strong> A liberdade de executar o programa como desejar, para qualquer propósito, sem restrições.<br><br>
<strong>Liberdade 1:</strong> A liberdade de estudar o funcionamento do programa e modificá-lo para atender às suas necessidades. Para isso, o acesso ao código-fonte é necessário.<br><br>
<strong>Liberdade 2:</strong> A liberdade de redistribuir cópias do software, promovendo o compartilhamento com outros.<br><br>
<strong>Liberdade 3:</strong> A liberdade de distribuir versões modificadas, permitindo que suas alterações beneficiem a comunidade. O código modificado deve manter as liberdades originais.<br><br>
Essas liberdades visam promover a cooperação e o compartilhamento, com ênfase em evitar a restrição de uso e modificação imposta por softwares proprietários.<br>

<strong>O software livre</strong> surgiu com o movimento liderado por Richard Stallman e o projeto GNU, em 1985, com foco nas quatro liberdades essenciais que garantem o uso, modificação e compartilhamento do software. O movimento tem uma base social, política e ideológica, priorizando a liberdade dos usuários.<br>

<strong>O software de código aberto</strong>, por outro lado, adotou uma abordagem mais pragmática e técnica, focando na transparência do código e na colaboração, especialmente após o sucesso do Linux e a expansão das comunidades de desenvolvimento online. O código visível passou a ser a principal característica, sem ênfase nas liberdades sociais.

Embora ambos os movimentos trabalhem de forma semelhante e colaborem em projetos globais, há conflitos quando um software atende às exigências de "código aberto" mas não às quatro liberdades do software livre. Esses conflitos surgem especialmente em questões de licenciamento, com o movimento de software livre sendo mais rigoroso em suas exigências.

Em resumo, a diferença principal está no foco: o software livre prioriza liberdades sociais, enquanto o código aberto foca em eficiência técnica e pragmatismo.

Ao contrário de produtos físicos, o software não transfere propriedade, mas sim direitos de uso, que são detalhados em licenças.

Empresas de software proprietário, como Microsoft, possuem suas próprias licenças específicas. Já o software livre e de código aberto busca clareza e simplicidade nas licenças, para que qualquer usuário possa entendê-las e aplicá-las. No entanto, alcançar simplicidade é difícil devido a diferenças legais entre países, como nas leis de direitos autorais da Alemanha e dos EUA, que possuem entendimentos diferentes sobre autoria e propriedade intelectual.

Isso resulta em diversas licenças FOSS e, às vezes, em confusão ou disputas legais ao combinar diferentes licenças. Organizações tanto do movimento de software livre quanto de código aberto formulam e ajudam na aplicação dessas licenças para garantir que os princípios de cada movimento sejam seguidos.

promovido pela Free Software Foundation (FSF) por meio da licença GNU General Public License (GPL). O copyleft garante que a liberdade de um software seja mantida em suas versões modificadas, evitando que restrições sejam impostas no futuro. Isso, porém, gera complicações práticas, já que softwares sob diferentes licenças copyleft podem ser incompatíveis entre si, ou até mesmo entre versões da mesma licença.

Para evitar esses problemas, algumas licenças, como a GNU Lesser General Public License (LGPL), permitem a combinação de software livre com software proprietário, como em bibliotecas. Outra solução é o licenciamento duplo, que oferece o software sob uma licença livre e outra proprietária, permitindo mais flexibilidade em troca de uma taxa.

A escolha da licença é crucial, pois afeta a cooperação com outros projetos, a compatibilidade de componentes e o futuro do software. O copyleft, embora promova liberdade, traz desafios especiais para os desenvolvedores.

Open Source Initiative (OSI), fundada em 1998, que cuida de questões de licenciamento de código aberto. A OSI desenvolveu um processo para verificar a conformidade de licenças com sua Open Source Definition, aprovando mais de 80 licenças, incluindo algumas que contradizem o princípio de copyleft, como as licenças BSD.

As licenças BSD são permissivas, permitindo ampla liberdade de uso e modificação do software, sem exigir que versões modificadas também sejam abertas. Um exemplo é a Licença BSD de 2 Cláusulas, que é simples e permite a redistribuição com poucas condições: manter os avisos de direitos autorais e a isenção de responsabilidade, tanto no código-fonte quanto em binários. Essas licenças dão aos desenvolvedores liberdade máxima para decidir se suas modificações serão abertas ou comerciais.

código aberto foi expandido para além do software, influenciando áreas como conhecimento e criatividade. Esse movimento levou à criação de fundações que promovem o compartilhamento de trabalho de forma colaborativa, sendo a Creative Commons (CC) a mais importante iniciativa nesse sentido.

A Creative Commons oferece licenças que permitem aos autores escolher como desejam compartilhar suas obras, mantendo certos direitos. O autor decide quais permissões conceder, resultando em seis licenças possíveis:

<strong>CC BY:</strong> Permite qualquer uso, desde que o autor seja citado.<br>
<strong>CC BY-SA:</strong> Como CC BY, mas obras derivadas devem manter a mesma licença.<br>
<strong>CC BY-ND:</strong> Permite redistribuição, mas sem modificações.<br>
<strong>CC BY-NC:</strong> Uso permitido apenas para fins não comerciais, com atribuição.<br>
<strong>CC BY-NC-SA:</strong> Não comercial e com compartilhamento pela mesma licença.<br>
<strong>CC BY-NC-ND:</strong> A mais restritiva, permitindo apenas redistribuição sem alterações e para fins não comerciais.<br><br>
Essas licenças proporcionam flexibilidade para os autores decidirem como suas obras serão usadas e distribuídas.<br>

Os modelos de negócios no ambiente de software livre e de código aberto (FLOSS), que, embora inicialmente idealista e não comercial, evoluiu para permitir formas de monetização. Alguns dos principais modelos de negócio mencionados incluem:

<strong>Crowdfunding:</strong> Desenvolvedores arrecadam doações por plataformas como Kickstarter em troca de recompensas ou acesso ao software.<br>
<strong>Licenciamento duplo:</strong> Oferece o software livre e, simultaneamente, uma versão proprietária com mais serviços, como suporte e atualizações, exemplificado pelo ownCloud.<br>
<strong>Serviços profissionais:</strong> Empresas pagam por consultoria, manutenção e suporte técnico para implementar e operar software livre.<br>
<strong>Certificações e merchandising:</strong> Plataformas como Moodle oferecem certificação, gerando receita adicional e reconhecimento no mercado.<br>
<strong>Software como Serviço (SaaS):</strong> Provedores hospedam software em nuvem e cobram pelo acesso, poupando o cliente de manutenção e instalação.<br>
<strong>Desenvolvimento sob encomenda:</strong> Desenvolvedores criam extensões específicas para clientes, que podem optar por liberar ou manter essas modificações privadas.<br><br>
Esses modelos permitem que desenvolvedores de software livre obtenham receita e garantem a sustentabilidade do movimento FLOSS.

<h2>Resumo</h2>
<Strong>Nesta lição você aprendeu:</Strong>

Semelhanças e diferenças entre software livre e de código aberto (FLOSS)

Licenças FLOSS, sua importância e problemas

Licenças copyleft vs. permissivas

Modelos de negócios FLOSS

<h1>Lição 4</h1>

Antigamente, usar o Linux no desktop era considerado difícil, pois faltavam aplicativos e ferramentas de configuração sofisticadas. Isso se devia ao fato de o Linux ser mais novo e inicialmente focado em usuários avançados, o que priorizou o desenvolvimento de ferramentas de linha de comando antes de interfaces gráficas. Porém, com o tempo, os ambientes de desktop no Linux amadureceram e agora oferecem recursos e facilidade de uso comparáveis a outros sistemas operacionais. Ainda assim, a linha de comando continua sendo uma ferramenta poderosa para usuários avançados. Hoje, as habilidades básicas de desktop, incluindo o uso da linha de comando, são importantes para escolher a melhor ferramenta para cada tarefa.

Ao utilizar um sistema Linux, você pode interagir tanto pela linha de comando quanto por uma interface gráfica de usuário (GUI). Ambas permitem acessar uma variedade de aplicativos que suportam quase todas as tarefas que você pode realizar no computador. Embora o objetivo anterior tenha apresentado alguns aplicativos comuns, esta lição foca em uma análise mais detalhada dos ambientes de desktop, formas de acessar o terminal, e ferramentas voltadas para apresentações e gerenciamento de projetos.

O Linux adota uma abordagem modular, onde diferentes partes do sistema são desenvolvidas por diversos projetos. Isso resulta em uma variedade de ambientes de desktop, que, junto com os gerenciadores de pacotes, são as principais diferenças entre as distribuições Linux. Ao contrário de sistemas proprietários como Windows e macOS, no Linux é possível instalar e escolher diferentes ambientes de desktop.

Os dois principais ambientes de desktop são Gnome e KDE. O Gnome segue o princípio KISS ("keep it simple, stupid"), oferecendo uma interface mais simplificada, enquanto o KDE oferece mais personalizações e configurações. Aplicativos Gnome usam a biblioteca GTK (C), e os do KDE usam Qt (C++), o que cria uma experiência visual unificada e otimiza o desempenho, economizando memória e acelerando o carregamento de aplicativos.

Os emuladores de terminal gráfico em Linux simulam antigos terminais seriais usados nas primeiras versões do Unix. No Gnome, o emulador é o Gnome Terminal, enquanto no KDE é o Konsole, e outras opções incluem o Xterm. Esses aplicativos permitem acessar o ambiente de linha de comando e interagir com um shell.

Para acessar o terminal, você pode encontrar o emulador no menu de aplicativos da sua distribuição. Outra forma de acessar o terminal é via TTY virtual, usando a combinação de teclas Ctrl + Alt + F#, onde "F#" é uma tecla de função (de F1 a F7), com algumas já usadas pelo ambiente gráfico.

O Linux é amplamente utilizado em servidores, com cerca de 68% dos servidores de sites sendo alimentados por Unix, principalmente Linux, devido à sua estabilidade, flexibilidade e desempenho. Ele é muito comum na nuvem, suportando modelos como IaaS (Infraestrutura como serviço), PaaS (Plataforma como serviço) e SaaS (Software como serviço).

No IaaS, os recursos são compartilhados via virtualização, onde hipervisores como Xen, KVM e VirtualBox gerenciam máquinas virtuais. O KVM, patrocinado pela Red Hat, é o hipervisor mais proeminente atualmente. No PaaS, como o Heroku, os usuários acessam plataformas para executar aplicativos sem lidar com a administração do sistema. Já no SaaS, como Dropbox e Salesforce, o usuário paga por acesso a softwares sem se preocupar com a infraestrutura.

O OpenStack é um projeto de código aberto que oferece um ambiente de nuvem IaaS, mas sua configuração é complexa.

O navegador da web é essencial em qualquer desktop hoje, mas muitos ainda não sabem usá-lo com segurança. À medida que mais serviços são acessados por navegadores, quase todas as ações dos usuários são rastreadas e analisadas por terceiros. Proteger o acesso aos serviços da internet e impedir o rastreamento é crucial para um uso seguro da internet.

Cookies são pequenos arquivos que sites armazenam em seu computador para guardar informações úteis, como itens em um carrinho de compras. Eles permitem que sites lembrem de suas ações em visitas futuras, o que pode ser conveniente. No entanto, redes de anúncios também utilizam cookies para rastrear suas atividades e exibir anúncios direcionados em outros sites. Isso ocorre porque, ao visitar um site de comércio eletrônico, um cookie da rede de anúncios é salvo, permitindo que a rede exiba anúncios relacionados aos produtos que você pesquisou.

Esse rastreamento pode ser desativado configurando seu navegador para bloquear cookies de terceiros. No entanto, isso pode afetar o funcionamento de alguns recursos em sites. Usar um gerenciador de cookies pode oferecer mais controle sobre quais cookies são armazenados.

O modo privado (ou "incógnito") nos navegadores, como Firefox e Chrome, abre uma nova sessão que não compartilha dados com o perfil padrão do usuário e apaga automaticamente o histórico, senhas e cookies ao ser fechada. No entanto, muitas pessoas acreditam que isso garante total anonimato na internet, o que não é verdade. Embora o modo privado evite o rastreamento por cookies ao apagar dados locais, outras técnicas ainda podem ser usadas para rastrear o usuário online.

O modo privado oferece proteção apenas no computador usado, sendo útil em locais públicos, como hotéis ou aeroportos, ao acessar contas pessoais. Porém, ele não protege contra outras ameaças, como malware ou keyloggers, em computadores públicos.

Criar senhas seguras é essencial para proteger suas contas, evitando combinações óbvias como "123456" ou dados pessoais. Um método recomendado é usar frases e formar senhas com as primeiras letras de cada palavra. No entanto, com o aumento de contas, lembrar várias senhas diferentes se torna difícil, e reutilizá-las entre serviços é arriscado, pois vazamentos em um serviço podem comprometer outros.

Uma solução mais segura é usar um gerenciador de senhas, que armazena suas senhas criptografadas, acessíveis por uma única senha mestra. Exemplos incluem:

<strong>KeePass:</strong> Um gerenciador de senhas de código aberto que armazena dados localmente em um arquivo criptografado.<br>
<strong>Bitwarden:</strong> Outro gerenciador de senhas de código aberto, que sincroniza senhas via nuvem, oferecendo a opção de hospedar seu próprio servidor.<br>
Esses gerenciadores geralmente incluem geradores de senhas aleatórias, garantindo senhas únicas e seguras para cada serviço.<br>

Sempre que dados são transferidos ou armazenados, é essencial tomar precauções para evitar o acesso por terceiros. Dados transferidos pela internet passam por várias redes, tornando-os vulneráveis, assim como dados armazenados em mídia física, que podem ser acessados por quem tiver posse dela. Para proteger informações confidenciais, elas devem ser criptografadas antes de serem enviadas ou armazenadas, garantindo que apenas os destinatários autorizados possam acessá-las.

Transport Layer Security (TLS) é um protocolo que garante segurança em conexões de rede por meio de criptografia, sendo o sucessor do SSL, que foi descontinuado devido a falhas. A versão mais recente do TLS é a 1.3, que oferece privacidade e autenticidade através de criptografia simétrica e de chave pública, protegendo as comunicações contra espionagem ou alterações.

O TLS é usado no protocolo HTTPS para transmitir dados sensíveis com segurança na web. Para verificar se um site é confiável, procure o cadeado na barra de endereços do navegador e clique para inspecionar o certificado que garante a segurança da conexão.

O GnuPG (GNU Privacy Guard) é uma ferramenta de código aberto que implementa o padrão OpenPGP e é usada para assinar, criptografar e descriptografar e-mails, textos, arquivos e até partições de disco. Ele utiliza criptografia de chave pública, gerando um par de chaves: pública (compartilhada com qualquer pessoa) e privada (mantida em segredo). A chave pública é usada por outros para criptografar dados que só sua chave privada pode descriptografar.

Além disso, o GnuPG permite assinar digitalmente arquivos ou e-mails com sua chave privada. O destinatário pode validar essa assinatura com sua chave pública, garantindo a autenticidade e integridade do conteúdo, já que qualquer alteração invalida a assinatura.

Existem dois principais métodos de criptografia para proteger dados em discos: criptografia de dispositivo empilhado e criptografia em bloco.

Na criptografia de dispositivo empilhado, os arquivos e diretórios são criptografados antes de serem armazenados no sistema de arquivos e descriptografados após a leitura. Os arquivos ainda existem como no sistema de arquivos normal, mas seu conteúdo e nomes são criptografados.

A criptografia em bloco atua abaixo do sistema de arquivos, criptografando todos os dados no dispositivo. Todo o conteúdo do disco parece aleatório quando o sistema está offline, e metadados e permissões também são criptografados.

Ferramentas recomendadas:

dm-crypt (com LUKS): padrão para criptografia de bloco no Linux.<br>
EncFS: método empilhado, fácil de usar e não requer privilégios de root.<br>
Veracrypt: sucessor do Truecrypt, compatível com Linux, macOS e Windows.<br>
Cada método oferece diferentes níveis de proteção e deve ser escolhido conforme a necessidade de segurança e compatibilidade.<br>

<h1>Resumo</h1>
O terminal é uma maneira poderosa de interagir com o sistema e há muitas ferramentas úteis e muito maduras para usar neste tipo de ambiente. Você pode chegar ao terminal procurando por um gráfico no menu do ambiente de trabalho ou pressionando Ctrl+ Alt+F# .<br>
O Linux é amplamente usado na indústria de tecnologia para oferecer serviços IaaS, PaaS e SaaS. Há três hipervisores principais que desempenham um papel importante no suporte a eles: Xen, KVM e Virtualbox.<br>
O navegador é um software essencial na computação hoje em dia, mas é necessário entender algumas coisas para usá-lo com segurança. DNT é apenas uma maneira de dizer ao site que você não quer ser rastreado, mas não há garantias sobre isso. Janelas privadas são privadas apenas para o computador que você está usando, mas isso pode permitir que você escape do rastreamento de cookies exatamente por isso.<br>
O TLS é capaz de criptografar sua comunicação na Internet, mas você precisa ser capaz de reconhecer quando ele está em uso. Usar senhas fortes também é muito importante para mantê-lo seguro, então a melhor ideia é delegar essa responsabilidade a um gerenciador de senhas e permitir que o software crie senhas aleatórias para cada site em que você fizer login.<br>
Outra maneira de proteger sua comunicação é assinar e criptografar seus arquivos, pastas e e-mails com o GnuPG. dm-crypt e EncFS são duas alternativas para criptografar discos ou partições inteiras que usam métodos de criptografia de bloco e pilha, respectivamente.<br>
Por fim, o LibreOffice Impress é uma alternativa de código aberto muito completa ao Microsoft Powerpoint, mas há o Beamer e o RevealJS se você preferir criar apresentações usando código em vez de GUIs. O ProjectLibre e o GanttProject podem ser a escolha certa se você precisar de um substituto do Microsoft Project.<br>
