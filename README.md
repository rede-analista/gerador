# Controle Remoto de Gerador
 Controle e partida de gerador de pequeno porte.
 # Descrição:
O objetivo é criar uma programação para ESP32, de forma que remotamente possa dar partida em um gerador e acompanhar informações.

# Resumo:
A programação é feita de forma que a maioria das configurações estejam disponíveis em uma interface web no ESP32, para que o usuário possa acessar pelo navegador e realizar as configurações desejadas, salvando as informações da memória flash (preferences) do ESP32.<br>
Algumas das características são proporcionar notificação por Telegram e comunicação com MqTT.

A intenção é controlar um Gerador de Energia à Gasolina 7,2 Kva Bivolt Partida Elétrica TG8000CXER TOYAMA, este gerador tem apenas partida elétrica mas não possui interface para controle e partida automática.

**NOTA: Não sou programador e nem técnico em eletrônica, somente me interesso por programação e controladores, sendo assim, não espere uma programação "bonita" e/ou dentro das melhores práticas, mas fique a vontade para trocar informações ou sugerir alguma melhoria**

## Recursos:


# Ambiente Desenvolvimento:
- O desenvolvimento foi realizado na interface Visual Studio versão 1.92.2 com sistema operacional Debian 12.1 Bookworm.


# !!!! IMPORTANTE !!!!
A programação atual ainda não faz nenhuma tratativa com as informações que são inseridas/configuradas, não há tratativas para informações com acentuação e tambem não há tratativas para configurações incorretas de pinagem.<br>
Desta forma, uma configuração incorreta pode causar travamentos, falhas ou ainda danificar o módulo ESP32, tenha cuidado e muita atenção para inserir as informações.