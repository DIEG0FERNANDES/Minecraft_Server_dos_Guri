# Minecraft_Server_dos_Guri_1.19.4_Fabric
Servidor de Minecraft 1.19.4 com mods fabric, configuravel com RadminVPN e UltrasurfVPN

# Sumário
- Como ligar e desligar o servidor
- O que não deve ser alterado no server properties
- Como alterar quantia de consumo de ram do servidor
- Lista de mods
- Lista de Resource Pack
- Lista de Shader Pack
- Configurações recomendadas no sodium para pc potato, low ou mediano

# Como ligar e desligar o servidor
- Como ligar servidor
	- Arquivos .jar
		- clique duas vezes em ligar_fabric_server.jar
		- ou clique duas vezes em ligar_server.jar
	- Arquivos .bat
		- clique duas vezes em ligar_com_mods.bat
		- ou clique duas vezes em ligar_sem_mods.bat
- Como desligar servidor
	- Arquivos .jar
		- 1° digite no console do servidor /save-all , isso fara com que o mundo seja salvo
		- 2° Digite no console do servidor /stop , isso garantira que o mundo seja salvo com chances de corromper por isso o save anterior é feito, em seguida ou seu servidor automaticamente será fechado ou basta clicar qualquer tecla que fechara o console do servidor que consequetemente estara fechado seu servidor
	- Arquivos .bat
		- 1° digite no console do servidor /save-all , isso fara com que o mundo seja salvo
		- 2° Digite no console do servidor /stop , isso garantira que o mundo seja salvo com chances de corromper por isso o save anterior é feito, em seguida ou seu servidor automaticamente será fechado ou basta clicar qualquer tecla que fechara o console do servidor que consequetemente estara fechado seu servidor
# O que não deve e deve ser alterado no server properties
- Seed legal(não altere ela): -6476254842693137875
- Não altere a pasta backup de mapas, apenas acrescente copias do mundo do servidor na pasta para caso der errado alguma coisa e seja nescessário fazer um uso do mapa backup
- No arquivo sever.properties você deve pesquisar por 
	- "sever-ip": coloque aqui seu ipv4 do radmin ou o ip do ultrasurf sem a porta, este será o ip do seu servidor
	- "sever-port": 25565 é a porta padrão, não é recomendavel alterar na porta caso não saiba o que esteja fazendo
	- "online-mode": false é para minecraft versão não oficial, recomendavel deixar no modo false
	- "motd":é aqui que fica a descrição do servidor dentro de jogo
	- "pvp": true ou false, aqui é intuitivo, false pra desativar e true pra ativar
	- "difficulty": está setado no easy, mas pode ser modificado para normal ou hard mode, lembrando que hard não hardcore mode
	- "hardcore": true para modo hardcore e false para modo vanilla
# Como alterar quantia de consumo de ram do servidor
	Para isto é necessário ter editor de texto como vscode, bloco de notas, notepad++ou sublimetext para fazer tal alteração, basta abrir um dos arquivos .bat ou os dois ao mesmo tempo, e trocar os valores de "-Xmx3G -Xms3G" para uma das seguintes opções:
	- 512M
	- 1G
	- 2G
	- 3G
	Recomendavel - 4G
# Lista de mods
# Lista de Resource Pack
# Lista de Shader Pack
# Configurações recomendadas no sodium para pc potato, low ou mediano