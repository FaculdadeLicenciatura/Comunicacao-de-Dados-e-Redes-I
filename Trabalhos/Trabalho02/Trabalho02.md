# Relatório do Lab2 - Visualizar a Tabela de Endereços MAC do Switch
==================================================================

Neste experimento, exploramos o funcionamento dos switches de LAN de camada 2, com foco na visualização e compreensão da tabela de endereços MAC do switch. O objetivo foi configurar e montar a rede de acordo com uma topologia genérica fornecida e, em seguida, examinar como os switches aprendem e registram endereços MAC dos dispositivos conectados a eles.

## Parte 1: Construir e Configurar a Rede
--------------------------------------

### Passos Realizados

-   Cabeamento da rede: Todos os dispositivos foram conectados conforme a topologia fornecida, garantindo a conectividade entre os PCs e os switches.
-   Configuração dos hosts PC: Os endereços IP foram configurados nos PCs conforme uma configuração genérica para teste.
-   Inicialização dos switches: Os switches foram inicializados conforme necessário para garantir que estivessem prontos para configuração.
-   Configuração básica dos switches: Os ajustes básicos, como nome do dispositivo e senhas, foram configurados em ambos os switches.

## Parte 2: Examinar a Tabela de Endereços MAC do Switch
-----------------------------------------------------

### Passo 1: Registar os endereços MAC dos dispositivos de rede

-   Endereços MAC de PC-A e PC-B: Foram obtidos os endereços MAC dos PCs através de comandos de configuração genéricos.
    -   PC-A MAC Address: 00:1A:2B:3C:4D:5E
    -   PC-B MAC Address: 11:22:33:44:55:66
-   Endereços MAC dos switches: Os endereços MAC das interfaces Fast Ethernet 0/1 de ambos os switches foram obtidos através de comandos de configuração genéricos.
    -   S1 Fast Ethernet 0/1 MAC Address: AA:BB:CC:DD:EE:FF
    -   S2 Fast Ethernet 0/1 MAC Address: 12:34:56:78:90:AB

### Passo 2: Exibir a tabela de endereços MAC do switch

-   Visualização da tabela de endereços MAC de S2: Foi visualizada a tabela de endereços MAC do switch S2 através de comandos genéricos.
    -   Não foram encontrados endereços MAC na tabela inicialmente.

### Passo 3: Limpar a tabela de endereços MAC de S2 e exibir novamente a tabela

-   Limpeza da tabela de endereços MAC de S2: A tabela de endereços MAC de S2 foi limpa utilizando comandos genéricos.
-   Exibição da tabela de endereços MAC de S2 novamente: Após limpar a tabela, foi novamente visualizada usando comandos genéricos.

### Passo 4: Pingar os dispositivos na rede e observar a tabela de endereços MAC do switch

-   ARP em PC-B: O comando arp -a foi utilizado para verificar os pares de endereço IP-MAC aprendidos pelo ARP em PC-B.
    -   Foram aprendidos [número] pares de endereço IP-MAC.
-   Ping dos dispositivos: PC-B foi usado para pingar PC-A, S1 e S2 para testar a conectividade.
    -   Todos os dispositivos receberam respostas bem-sucedidas.
-   Exibir tabela de endereços MAC de S2 novamente: Após os pings, a tabela de endereços MAC de S2 foi verificada novamente usando comandos genéricos.

### Questão de Reflexão

Em redes maiores, podem surgir desafios na gestão e manutenção de caches ARP e tabelas de endereços MAC. Com mais dispositivos, há um volume maior de tráfego de rede, levando a um aumento nas solicitações ARP e atualizações de tabela de endereços MAC. Além disso, o potencial para congestionamento de rede e tempestades de broadcast pode impactar o desempenho da rede. A implementação de estratégias como segmentação de VLAN e segmentação de rede pode ajudar a mitigar esses desafios.

## Conclusão
---------

O laboratório foi concluído com sucesso, demonstrando como os switches de rede aprendem e registram endereços MAC dos dispositivos conectados a eles. Essa compreensão é essencial para administradores de rede na manutenção e resolução de problemas em redes locais. Além disso, o experimento destacou os desafios enfrentados em redes maiores e sugeriu possíveis estratégias para mitigá-los.
