# 🎸 Configuração de Rede para o Show da Banda de Miguel

Para o show da banda de Miguel, será necessário configurar uma **rede de computadores**. <br>
A comunicação entre os membros da equipe de produção, que estarão espalhados pelo teatro,
é **fundamental** para manter todos informados e garantir que tudo esteja sob controle. ✅<br>
O agente da banda decidiu modernizar a infraestrutura do show para melhorar essa comunicação. <br>
Para ajudá-los, você deve usar o **Cisco Packet Tracer** para criar uma **topologia de rede estrela** que permita a toda a equipe se comunicar facilmente. 🌟

Passos:
1. Definir o cenário
- Imagine que cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

2. Montar a topologia
- Crie uma nova topologia no Cisco Packet Tracer; 
- Arraste um switch para o centro da área de trabalho; 
- Arraste quatro PCs e posicione-os ao redor do switch, representando cada membro da equipe de produção.

3. Conectar os dispositivos
- Conecte cada PC a uma porta diferente no switch usando cabos ethernet;
- Visualize os computadores da equipe de produção formando uma estrela ao redor do switch central.

4. Configurar os endereços IP
- Crie um senso de identidade para cada computador, atribuindo nomes e números de endereços IP;
- Configure os endereços IP para as interfaces dos PCs e do switch de acordo com a mesma sub-rede.

5. Testar a comunicação
- Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe, abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.

Por fim, envie o arquivo do Cisco gerado, junto com um print da tela com a topologia e do comando ping executado para os outros três computadores.

Trabalhe esse código em seu IDE, suba ele para sua conta no GitHub e compartilhe o link desse projeto no campo ao lado para que outros desenvolvedores possam analisá-lo.
