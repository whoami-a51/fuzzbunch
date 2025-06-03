## Fuzzbunch
Fuzzbunch é uma ferramenta de ataque desenvolvida pela NSA, que veio a público em 2017 após vazamentos. Projetado para sistemas operacionais Windows, o Fuzzbunch é comparável ao Metasploit, uma ferramenta amplamente utilizada em testes de penetração,
mas com capacidades mais avançadas, incluindo a integração de exploits 0day.

** Repositório Original
- https://github.com/x0rz/EQGRP_Lost_in_Translation

# Instalação
- Baixe o pacote em https://github.com/whoami-a51/fuzzbunch/archive/master.zip
- Extraia-o para o seu disco rígido
- Execute install.bat somente no Windows XP 32 bits ou Windows 7 32 bits
- Copie os atalhos: (console do fuzzbunch, java do fuzzbunch, configuração do fuzzbunch) de c:\fuzzbunch-master\dependencies para a sua área de trabalho

- Ao executar o fuzzbunch, certifique-se de escrever no caminho dos logs (D:\Logs\NOME_DO_PROJETO)
- Após carregar o fuzzbunch (GUI), escreva pc_prep no console do fuzzbunch para preparar o payload

# Requisitos
- O usuário deve ter uma partição de disco rígido d:\ ou criar uma pasta virtual e atribuí-la como unidade

- Para quem não possui a unidade D::
crie uma pasta na unidade C: com o nome "drived", abra uma linha de comando (cmd) e execute este comando:
(subst d: c:\drived)

- Importante: certifique-se de que não haja uma unidade de CD atribuída à unidade D:. Caso tenha, altere a letra da unidade.
https://www.computerhope.com/issues/ch000038.htm

# Dicas
- É recomendável usar uma máquina virtual Windows XP/7 de 32 bits para instalar este git.

# Vídeo de instalação
- https://www.youtube.com/watch?v=GKIS9ynaSL4

# Como funciona o Fuzzbunch
- <img src="https://s1.postimg.cc/4mk2z300jz/exp.jpg" width="50%"></img>
- <img src="https://s1.postimg.cc/7kn268yhlr/exp1.jpg" width="50%"></img>

# Exploits

- **EARLYSHOVEL** exploit RedHat 7.0 - 7.1 Sendmail 8.11.x
- **EBBISLAND (EBBSHAVE)** root RCE via estouro de RPC XDR no Solaris 6, 7, 8, 9 e 10 (possivelmente mais recentes), tanto SPARC quanto x86.
- **ECHOWRECKER** exploit remoto Samba 3.0.x Linux.
- **EASYBEE** parece ser uma vulnerabilidade no servidor de e-mail MDaemon
- **EASYFUN** Exploit EasyFun 2.2.0 para WDaemon / IIS MDaemon/WorldClient anterior à versão 9.5.6
- **EASYPI** é um exploit para IBM Lotus Notes que é detectado como Stuxnet
- **EWOKFRENZY** é um exploit para IBM Lotus Domino 6.5.4 e 7.0.2
- **EXPLODINGCAN** é um exploit para IIS 6.0 que cria um backdoor remoto
- **ETERNALROMANCE** é um exploit SMB1 na porta TCP 445 que tem como alvo XP, 2003, Vista, 7, Windows 8, 2008, 2008 R2 e concede privilégios de SISTEMA (MS17-010)
- **EDUCATEDSCHOLAR** é um exploit SMB (MS09-050)
- **EMERALDTHREAD** é um exploit SMB para Windows XP e Server 2003 (MS10-061)
- **EMPHASISMINE** é um exploit IMAP remoto para IBM Lotus Domino 6.6.4 a 8.5.2
- **ENGLISHMANSDENTIST** define regras do Outlook Exchange WebAccess para acionar código executável no lado do cliente para enviar um e-mail a outros usuários
- **EPICHERO** exploit de dia zero (RCE) para Avaya Call Server
- **ERRATICGOPHER** é um exploit SMBv1 direcionado ao Windows XP e Server 2003
- **ETERNALSYNERGY** é uma falha de execução remota de código SMBv3 para Windows 8 e Server 2012 SP0 (MS17-010)
- **ETERNALBLUE** é um exploit SMBv2 para Windows 7 SP1 (MS17-010)
- **ETERNALCHAMPION** é um exploit SMBv1
- **ESKIMOROLL** é um Exploração do Kerberos direcionada a controladores de domínio 2000, 2003, 2008 e 2008 R2
- **ESTEEMAUDIT** é uma exploração RDP e backdoor para Windows Server 2003
- **ECLIPSEDWING** é uma exploração RCE para o serviço Server no Windows Server 2008 e versões posteriores (MS08-067)
- **ETRE** é uma exploração para o IMail 8.10 a 8.22
- **ETCETERABLUE** é uma exploração para o IMail 7.04 a 8.05
- **FUZZBUNCH** é um framework de exploração, semelhante ao MetaSploit
- **ODDJOB** é um construtor de implantes e servidor C&C que pode fornecer explorações para Windows 2000 e versões posteriores, também não detectado por nenhum fornecedor de antivírus
- **EXPIREDPAYCHECK** exploração para IIS6
- **EAGERLEVER** exploração NBT/SMB para Windows NT4.0 2000, XP SP1 e SP2, 2003 SP1 e Versão Base
- **EASYFUN** Exploit do WordClient / IIS6.0
- **ESSAYKEYNOTE**
- **EVADEFRED**

# Utilitários

- Utilitário **PASSFREELY** que "Ignora a autenticação para servidores Oracle"
- **SMBTOUCH** verifica se o alvo é vulnerável a exploits do Samba como ETERNALSYNERGY, ETERNALBLUE, ETERNALROMANCE
- **ERRATICGOPHERTOUCH** verifica se o alvo está executando algum RPC
- **IISTOUCH** verifica se a versão do IIS em execução é vulnerável
- **RPCOUTCH** obtém informações sobre o Windows via RPC
- **DOPU** usado para conectar-se a máquinas exploradas por ETERNALCHAMPIONS
- **NAMEDPIPETOUCH** Utilitário para testar uma lista predefinida de pipes nomeados, principalmente detecção de antivírus. O usuário pode adicionar verificações para pipes nomeados personalizados.

# Agradecimentos

- * misterch0c pelas informações sobre exploits: https://github.com/misterch0c/shadowbroker/
- * informações detalhadas sobre os problemas do misterch0c: https://github.com/misterch0c/shadowbroker/issues/22

# Não muito divulgado
- Eventualmente, a versão original do shadowbrokers foi lançada devido a uma intervenção dos EUA na Síria.
- * Link relacionado à publicação de exploits deste framework do shadowbrokers
- https://www.rt.com/usa/384082-shadow-brokers-nsa-password-trump/
