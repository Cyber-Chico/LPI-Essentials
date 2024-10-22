<h1> Lição 1</h1>
O Linux, criado em 1991 por Linus Torvalds e inspirado no Unix, é um dos sistemas operacionais mais populares, amplamente utilizado em várias plataformas, com base em uma comunidade global de desenvolvedores. As distribuições Linux são pacotes que combinam o kernel Linux com softwares específicos para atender a diferentes necessidades, como Debian, voltado para confiabilidade e liberdade de software, e Ubuntu, que foca na facilidade de uso. Empresas como Red Hat e SUSE oferecem distribuições Linux comerciais com suporte corporativo, enquanto projetos como CentOS e Fedora são variações gratuitas com foco em servidores e desktop, respectivamente.<br><br>

Sistemas embarcados, como o Raspberry Pi, utilizam versões de Linux para funções específicas em dispositivos inteligentes e automação. O Android, baseado em Linux, é amplamente usado em dispositivos móveis, oferecendo flexibilidade e integração com o ecossistema do Google.<br>

Na nuvem, o Linux domina, sendo a base de até 90% das cargas de trabalho. Plataformas como AWS e Google Cloud oferecem uma gama de distribuições Linux otimizadas para uso em infraestruturas como serviço (IaaS), permitindo provisionamento rápido de servidores virtuais baseados em Linux.<br>

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
