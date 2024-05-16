# Resumos de Cada Ponto

22/02/2024 - Apresentação / Funcionamento de uma rede
-----------------------------------------------------

1.  Introdução às Redes de Computadores:

    -   As redes de computadores desempenham um papel fundamental na interconexão de dispositivos, permitindo comunicação e compartilhamento de recursos. Elas são essenciais na era digital, facilitando desde a comunicação instantânea até o armazenamento em nuvem e o acesso a serviços online.
2.  Componentes de uma Rede:

    -   Os principais componentes de uma rede incluem switches, roteadores, gateways e dispositivos finais, como computadores e smartphones. Cada componente desempenha um papel específico na rede, desde o encaminhamento de pacotes até o acesso à Internet.
3.  Princípios de Comunicação de Dados:

    -   As redes de computadores funcionam com base em protocolos de comunicação, como TCP/IP, que definem as regras para o envio e recebimento de dados. O endereçamento IP é usado para identificar dispositivos na rede, enquanto a transmissão de dados pode ocorrer por meio de cabos físicos ou conexões sem fio.
4.  Segurança da Rede:

    -   A segurança da rede é crucial para proteger os dados contra acesso não autorizado e ataques cibernéticos. Isso envolve a implementação de firewalls, criptografia e autenticação para garantir a integridade, confidencialidade e disponibilidade das informações.

* * * * *

29/02/2024 - Basic Switch and End Device Configuration
------------------------------------------------------

1.  Tipos de Switches:

    -   Os switches podem ser gerenciáveis ou não gerenciáveis. Os switches gerenciáveis oferecem recursos avançados de configuração e monitoramento, enquanto os não gerenciáveis são mais simples e não permitem personalização.
2.  Atribuição de Endereços IP:

    -   Os endereços IP podem ser atribuídos manualmente ou automaticamente pelo DHCP (Dynamic Host Configuration Protocol). Isso permite que os dispositivos se comuniquem dentro da mesma rede e com redes externas.
3.  VLANs (Virtual LANs):

    -   VLANs são usadas para segmentar o tráfego de rede em grupos lógicos, independentemente da localização física dos dispositivos. Isso melhora a segurança e o desempenho da rede.

* * * * *

7/03/2024 - LAB1 - Configuração Básica de um Switch Ethernet
------------------------------------------------------------

1.  Configuração de Switches Ethernet:

    -   Durante o laboratório, os alunos aprenderão a configurar portas, atribuir endereços MAC e criar VLANs em um switch. Isso permitirá que eles entendam como os switches funcionam e como podem ser personalizados para atender às necessidades específicas da rede.
2.  Exercícios Práticos:

    -   Os exercícios práticos ajudarão os alunos a aplicar os conceitos aprendidos durante a configuração do switch. Eles ganharão experiência prática na manipulação de configurações de rede e solução de problemas comuns.

* * * * *

14/03/2024 - Modelos TCP/IP e OSI / Encapsulamento e Desencapsulamento
----------------------------------------------------------------------

1.  Modelo OSI (Open Systems Interconnection):

    -   O modelo OSI é uma referência para entender como os dados são transmitidos em uma rede. Ele divide o processo em sete camadas, cada uma com funções específicas, como aplicação, transporte e física.
2.  Modelo TCP/IP:

    -   O modelo TCP/IP é o modelo de rede mais amplamente utilizado. Ele consiste em quatro camadas: aplicação, transporte, internet e interface de rede. Essas camadas fornecem um guia para o desenvolvimento de protocolos de rede, como HTTP, TCP e IP.
3.  Encapsulamento e Desencapsulamento:

    -   Durante a transmissão de dados, os dados são encapsulados em cada camada do modelo de referência. Isso significa que os dados são envolvidos em cabeçalhos adicionais que contêm informações de controle. No destino, os cabeçalhos são removidos em um processo chamado desencapsulamento.

* * * * *


21/03/2024 - Modelos TCP/IP e OSI / Encapsulamento e Desencapsulamento
----------------------------------------------------------------------

1.  Modelo OSI (Open Systems Interconnection):

    -   O modelo OSI é uma estrutura conceitual que define as etapas necessárias para que dois dispositivos em uma rede se comuniquem. Ele divide esse processo em sete camadas, cada uma responsável por uma função específica. As camadas do modelo OSI são: camada física, camada de enlace, camada de rede, camada de transporte, camada de sessão, camada de apresentação e camada de aplicação.
2.  Modelo TCP/IP:

    -   O modelo TCP/IP é um conjunto de protocolos de comunicação amplamente utilizado em redes de computadores. Ele é composto por quatro camadas: camada de aplicação, camada de transporte, camada de internet e camada de acesso à rede. O modelo TCP/IP é o padrão de facto para a Internet e é usado em muitas redes corporativas.
3.  Encapsulamento e Desencapsulamento:

    -   O encapsulamento é o processo de adicionar informações de controle aos dados à medida que eles passam por cada camada do modelo OSI ou TCP/IP. Essas informações são usadas para rotear os dados para o destino correto e garantir sua integridade durante a transmissão. O desencapsulamento é o processo inverso, no qual as informações de controle são removidas dos dados à medida que são recebidos pelo destino.

* * * * *

4/04/2024 - Protocolo Ethernet e Endereçamento MAC / Funcionamento de um Switch
-------------------------------------------------------------------------------

1.  Protocolo Ethernet:

    -   O protocolo Ethernet é o padrão de comunicação mais comum em redes locais (LANs). Ele define as regras para o formato dos pacotes de dados e como eles são transmitidos e recebidos em uma rede. O protocolo Ethernet opera na camada de enlace do modelo OSI e usa endereços MAC para identificar dispositivos na rede.
2.  Endereçamento MAC:

    -   O endereço MAC (Media Access Control) é um identificador exclusivo atribuído a cada dispositivo de rede. Ele é usado pelo protocolo Ethernet para encaminhar pacotes de dados para o destino correto em uma rede local. O endereço MAC é gravado em hardware e não pode ser alterado.
3.  Funcionamento de um Switch:

    -   Um switch é um dispositivo de rede que encaminha pacotes de dados entre dispositivos em uma rede local. Ele opera na camada de enlace do modelo OSI e usa endereços MAC para encaminhar os pacotes para o destino correto. Os switches são mais eficientes do que os hubs porque eles encaminham os pacotes apenas para as portas relevantes, em vez de transmiti-los para todas as portas na rede.

* * * * *

11/04/2024 - LAB2 - Endereçamento MAC e FDB
-------------------------------------------

1.  Configuração de Endereços MAC:

    -   Durante o laboratório, os alunos aprenderão a atribuir e modificar endereços MAC em dispositivos de rede. Isso permite que eles entendam como os endereços MAC são usados para encaminhar o tráfego em uma rede local.
2.  Construção da Tabela de Endereços MAC (FDB):

    -   Os switches usam uma tabela de endereços MAC, também conhecida como tabela FDB (Forwarding Database), para encaminhar os pacotes para o destino correto. Durante o laboratório, os alunos aprenderão como essa tabela é construída e atualizada à medida que os dispositivos se comunicam na rede.

* * * * *

18/04/2024 - Protocolo IPv4
---------------------------

1.  Introdução ao Protocolo IPv4:

    -   O protocolo IPv4 é o protocolo de rede mais amplamente utilizado na Internet. Ele é responsável por fornecer um endereço único para cada dispositivo na rede e encaminhar os pacotes de dados entre eles. O IPv4 usa endereços de 32 bits, o que limita o número de dispositivos que podem ser conectados à Internet.
2.  Roteamento IPv4:

    -   O roteamento IPv4 é o processo de encaminhamento de pacotes de dados entre redes. Isso envolve a seleção da rota mais eficiente com base no endereço de destino e a transmissão dos pacotes através dos roteadores intermediários.
3.  Subnetting e Supernetting:

    -   Subnetting e supernetting são técnicas usadas para dividir e combinar redes IPv4, respectivamente. O subnetting permite que uma rede seja dividida em sub-redes menores, enquanto o supernetting permite que várias redes sejam combinadas em uma única rede maior.

* * * * *

24/04/2024 - Protocolo IPv4
---------------------------

1.  Introdução ao Protocolo IPv4:

    -   O protocolo IPv4 é o protocolo de rede mais amplamente utilizado na Internet. Ele é responsável por fornecer um endereço único para cada dispositivo na rede e encaminhar os pacotes de dados entre eles. O IPv4 usa endereços de 32 bits, o que limita o número de dispositivos que podem ser conectados à Internet.
2.  Roteamento IPv4:

    -   O roteamento IPv4 é o processo de encaminhamento de pacotes de dados entre redes. Isso envolve a seleção da rota mais eficiente com base no endereço de destino e a transmissão dos pacotes através dos roteadores intermediários.
3.  Subnetting e Supernetting:

    -   Subnetting e supernetting são técnicas usadas para dividir e combinar redes IPv4, respectivamente. O subnetting permite que uma rede seja dividida em sub-redes menores, enquanto o supernetting permite que várias redes sejam combinadas em uma única rede maior.

* * * * *

2/05/2024 - Frequência 1
------------------------

1.  Revisão dos Tópicos Anteriores:

    -   Durante a frequência, os alunos terão a oportunidade de revisar os tópicos abordados até o momento, consolidando seu conhecimento e identificando áreas que precisam de mais estudo.
2.  Aprofundamento em Tópicos Específicos:

    -   Além da revisão, a frequência também pode incluir a exploração de tópicos adicionais ou mais complexos dentro do escopo de redes de computadores, dependendo das necessidades e interesses dos alunos.

* * * * *

16/05/2024 - Endereçamento IPv4
-------------------------------

1.  Endereçamento IPv4:
    -   O endereçamento IPv4 é o método usado para atribuir endereços únicos a dispositivos em uma rede. Os endereços IPv4 são compostos por 32 bits, divididos em quatro octetos, e são expressos em notação decimal pontuada, como 192.168.1.1. Cada dispositivo em uma rede deve ter um endereço IPv4 exclusivo para comunicação.

* * * * *

23/05/2024 - Endereçamento IPv4
-------------------------------

1.  Endereçamento IPv4:
    -   O endereçamento IPv4 é o método usado para atribuir endereços únicos a dispositivos em uma rede. Os endereços IPv4 são compostos por 32 bits, divididos em quatro octetos, e são expressos em notação decimal pontuada, como 192.168.1.1. Cada dispositivo em uma rede deve ter um endereço IPv4 exclusivo para comunicação.

* * * * *

29/05/2024 - Funcionamento de um Router
---------------------------------------

1.  Funcionamento de um Roteador:
    -   Um roteador é um dispositivo de rede que encaminha pacotes de dados entre redes diferentes. Ele opera na camada de rede do modelo OSI e usa tabelas de roteamento para determinar a melhor rota para encaminhar os pacotes. Os roteadores são essenciais para interconectar redes e facilitar a comunicação entre dispositivos em diferentes locais.

* * * * *

6/06/2024 - Funcionamento de um Router / LAB3 - Configuração Básica de um Router
--------------------------------------------------------------------------------

1.  Funcionamento de um Roteador:

    -   Um roteador é um dispositivo de rede que encaminha pacotes de dados entre redes diferentes. Ele opera na camada de rede do modelo OSI e usa tabelas de roteamento para determinar a melhor rota para encaminhar os pacotes. Os roteadores são essenciais para interconectar redes e facilitar a comunicação entre dispositivos em diferentes locais.
2.  LAB3 - Configuração Básica de um Roteador:

    -   Durante o laboratório, os alunos aprenderão a configurar interfaces, rotas estáticas e protocolos de roteamento básicos em um roteador. Isso permitirá que eles entendam como os roteadores funcionam e como podem ser configurados para rotear o tráfego de rede de maneira eficiente.

* * * * *

13/06/2024 - LAB3 - Configuração Básica de um Router
----------------------------------------------------

1.  LAB3 - Configuração Básica de um Roteador:
    -   Continuação do guia passo a passo para configurar interfaces, rotas estáticas e protocolos de roteamento básicos em um roteador. Os alunos terão a oportunidade de aplicar os conceitos aprendidos durante o laboratório anterior e resolver problemas práticos relacionados à configuração de roteadores.

* * * * *

20/06/2024 - Frequência 2
-------------------------

1.  Revisão dos Tópicos Anteriores:

    -   Durante a frequência, os alunos terão outra oportunidade de revisar os tópicos abordados até o momento e consolidar seu conhecimento.
2.  Aprofundamento em Tópicos Específicos:

    -   Além da revisão, a frequência também pode incluir a exploração de tópicos adicionais ou mais complexos dentro do escopo de redes de computadores, conforme as necessidades e interesses dos alunos.

* * * * *

O que significa cada palavra mais importante:
---------------------------------------------

-   Redes de Computadores: Sistemas interconectados que permitem a comunicação e o compartilhamento de recursos entre dispositivos.
-   Protocolos de Comunicação: Conjunto de regras e procedimentos que permitem a comunicação eficiente entre dispositivos em uma rede.
-   Endereçamento IP: Identificador numérico atribuído a cada dispositivo em uma rede para permitir a comunicação.
-   Switches e Roteadores: Dispositivos de rede que encaminham pacotes de dados entre redes locais e/ou remotas.
-   VLANs: Redes virtuais que segmentam o tráfego de rede para melhorar o desempenho e a segurança.
-   Encapsulamento e Desencapsulamento: Processo de adicionar e remover cabeçalhos de controle aos dados durante a transmissão em uma rede.
-   Segurança da Rede: Conjunto de medidas para proteger os dados e os dispositivos de rede contra acesso não autorizado e ameaças cibernéticas.
-   Protocolo Ethernet: Padrão de comunicação para redes locais (LANs) que define como os dados são transmitidos e recebidos.
-   Endereço MAC: Identificador único atribuído a cada dispositivo de rede para facilitar o encaminhamento de pacotes.
-   Roteamento IPv4: Processo de encaminhamento de pacotes de dados entre redes usando o protocolo IPv4.
-   Subnetting e Supernetting: Técnicas para dividir e combinar redes IPv4, respectivamente, para gerenciar eficientemente os endereços IP disponíveis.
