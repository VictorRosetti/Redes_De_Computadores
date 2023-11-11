# Redes_De_Computadores
1º Intuito: Tranferir dados entre computadores
DARPANET criada paa proteger dados 
Trocas de informações eram feitas por meios de simpósios 

Criação da Rede
Exército necessitava de um meio de comunicação na guerra de uma forma que não seja fácil de ser interceptada, então ele investe nas universidades que ja estavam pesquisando sobre redes para que eles pesquisem mais e consigam mais resutados.

As universidades trocavam informações por meio de simpósios e procuraram uma forma de fazer isso com mais facilidade.
Então, elas se conectaram por meio de cabos que ligavam umas nas outras, transferindo informações e as protegendo em caso de ataques.

Mais pra frente as universidades gostariam de fazer co  que pessoas que não fizesse parte da instituição utilizassem a rede que eles estavam utilizando, então começaram a divulgar e quem quisesse utilizar teria que pagar um certo valor para a instalação do cabo ser feita liberando o acesso a rede.

Porém, isso se tornou algo complicado a se fazer e as universidades recorreram a rede telefônic, que ja tinha uma rede que passava pela maior parte do país.
Então, ficou a crtério da telefônica a questão de implantar a rede nas casas.

Topologia de rede

Topologia de rede se refere à estrutura lógica ou física que um dispositivo ou computador esta interligado. Estas topologias estão relacionadas a como os dispositivos, servidores etc se comnicam e compartilham recursos entre si

Topologias mais comuns:

Topologia em Anel: Os dispositivos são ligados em formato de anel no qual um dispositivo esta ligado no anterior e no próximo. Os dados só podem correm em sentido único

Topologia em Estrela: Todos os dispositivos estã ligados a um ponto central e vão criando mais ligaçõe ao longo do tempo

Topologia de Barramento: 
todos os dispositivos estão ligados a um único cabo.

Topologia de Malha: Muito parecida com a de Estrela, os dispositivos vão sendo ligados formando uma especie de "teia de aranha". Cada dispositivo esta ligado a todos

Ligação a cabo

Cabo coaxial é um tipo de cabo de transmissão que é utilizado para enviar dados em uma rede
Fibra Óptica é um meio de transmissão de dados que utiliza da velocidade da luz, fazendo com que o processo seja cada vez mais rápido.

Cabo de rede são cabos que permitem transmitir sinais elétricos ou opticos que transportam dados de um dispositivo para o outro

TIPOS DE NET

INTRANET: Apenas empresa

EXTRANET: Fornecedores, clientes e colaboradores

INTERNET: O mundo

Camadas TCP/IP - Protocolo de enlace de dados - Criado para especificar como os computadores transferem dados uns aos outros

4 camadas do modelo TCP/IP

IP - Parte que obtém o endereço para o qual os dados serão enviados

TCP - Responsável pelo envio dos dados assim que o endereço for encontrado

Camada de enlace de dados - É aquela que lida com as partes físicas de envio e recebimento de dados usando cabo Ethernet, rede sem fio e etc.

Camada de rede - Realiza a comunicação entre máquinas vizinhas através do protocolo IP

Camada de transporte - Fornece uma conexão confiável entre dois dispositivos. Divide os dados em pacotes, reconhece os pacotes que recebeu e garante que o outro dispositivo reconheça os pacotes que recebeu

Camada de aplicativo - Reune os protocolos que fornecem serviços de comunicação ao sistema e ao usuário

Diferentes tipos de IP

Hoje em dia há dois tipos diferentes de IP: IPv4 e IPv6

IPs de dispositivos pessoais têm 4 tipos: privados, público, dinâmicos e estáticos

IP privado - Utilizado para se comunicar dentro de suas redes locais

IP público - Utilizado para se comunicar através de suas redes locais

Há dois tipos de endereços de IP público:

Dinâmico - Aquele que o provedor de internet oferece aos clientes

Estático - O endereço de IP é sempre fixo, a menos que o serviço de administração decida alterá-lo

IPv4 - Internet Protocol Version 4

Representada por um conjunto numérico de 32 bits dividos em 4 partes e separado por pontos.

O valor de cada conjunto varia entre 0 e 255

Ex: 25.42.25.175

IPv6 

São sequencias numéricas de 128 bits

São compostos por 8 conjuntos de dígitos hexadecimais de 16 bits separados por 2 pontos

É escrito com letras de A à F e de 0 à 9

Máscara de rede

Principal função é avisar ao roteador que as mensagens têm endereços diferentes, possibilitando que o identificador da rede e do host sejam identificados

A mascara de rede tem 32 bits tendo como finalidade mascarar um endereço IP

Todo endereço IP tem uma mascara correspondente para identificar qual parte é da rede e qual parte é do host

Calcular mascaras de sub rede

A cada 3 digitos da mascara, temos uma parte de oendereço de host 

192 . 168 . 0 . 1

Cada parte com 8 bits de 0 a 255

para calcular basta usar a elevação a 2

2^0 2¹ 2² 2³ 2³ 2^4 2^5 2^6 2^7 

Começando a somar da esquerda para a direita, pulando numeros e necessário

Ex:

192. 168.0.0

Para calcular 192 deve utilizar a soma de 128 + 64 
Sendo assim os bits utilizados foram os dois primeiros, então o número 192 em binarios seria: 11000000

Para calcular 168 deve utilizar a soma de 128(primeiro bit) + 32(terceiro bit) + 8(quinto bit)
Sendo assim os bits utilizados foram o primeiro, terceiro e quinto então o número 168 em binarios seria: 10101000

Para 0 todos os 8 bits são 0

Para 1 utilizará apenas o ultimo bit: 00000001

As mascaras de rede são utilizadas não apenas para identificção mas para ampliar a utilização da rede

















