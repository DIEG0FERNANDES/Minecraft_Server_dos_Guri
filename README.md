# minecraft_server_dos_guri_1.20
Servidor de Minecraft 1.20 papermc, configuravel com RadminVPN e UltrasurfVPN

# Sumário
- Como ligar e desligar o servidor
- O que não deve ser alterado no server properties
- Como alterar quantia de consumo de ram do servidor
- Exemplo de server.properties
- Lista de mods
- Lista de Resource Pack
- Lista de Shader Pack
- Configurações recomendadas no sodium para pc potato, low ou mediano

# Como ligar e desligar o servidor
- Como ligar servidor
	- Arquivos .jar
		- clique duas vezes em paper.jar
	- Arquivos .bat
		- clique duas vezes em run.bat
- Como desligar servidor
	- Arquivos .jar
		- 1° digite no console do servidor save-all , isso fara com que o mundo seja salvo
		- 2° Digite no console do servidor stop , isso garantira que o mundo seja salvo com chances de corromper por isso o save anterior é feito, em seguida ou seu servidor automaticamente será fechado ou basta clicar qualquer tecla que fechara o console do servidor que consequetemente estara fechado seu servidor
	- Arquivos .bat
		- 1° digite no console do servidor save-all , isso fara com que o mundo seja salvo
		- 2° Digite no console do servidor stop , isso garantira que o mundo seja salvo com chances de corromper por isso o save anterior é feito, em seguida ou seu servidor automaticamente será fechado ou basta clicar qualquer tecla que fechara o console do servidor que consequetemente estara fechado seu servidor
# O que pode e não pode ser alterado no server properties e pastas
- Seed legal(não altere ela): -6476254842693137875
- Não altere a pasta backup de mapas, apenas acrescente copias do mundo do servidor na pasta para caso der errado alguma coisa e seja nescessário fazer um uso do mapa backup
- Pastas de sons e emotes podem ser adicionados seu proprio emote e sons que quiser desde que não sejá arquivo pesado
- No arquivo sever.properties você deve pesquisar por 
	- "sever-ip": coloque aqui seu ipv4 do radmin ou o ip do ultrasurf sem a porta, este será o ip do seu servidor
	- "sever-port": 25565 é a porta padrão, não é recomendavel alterar na porta caso não saiba o que esteja fazendo
	- "online-mode": false é para minecraft versão não oficial, recomendavel deixar no modo false
	- "motd":é aqui que fica a descrição do servidor dentro de jogo
	- "pvp": true ou false, aqui é intuitivo, false pra desativar e true pra ativar
	- "difficulty": está setado no easy, mas pode ser modificado para normal ou hard mode, lembrando que hard não hardcore mode
	- "hardcore": true para modo hardcore e false para modo vanilla
# Exemplo de server.properties
- Pode alterar
	- spawn-protection=16
	- view-distance=6 menos lagg 8 recomendavel paraq visão, só não passe de 10
	- simulation-distance=6
	- server-ip={ipv4 do radmin aqui}
	- server-port=25565
	- gamemode=survival
	- difficulty=easy
	- allow-nether=true
	- motd=\u00A7n\u00A7l\u00A77SERVER DOS \u00A7eGURI
	- hardcore=false
	- white-list=false
	- enforce-whitelist=false
	- broadcast-console-to-ops=true
	- pvp=true
	- spawn-npcs=true
	- spawn-animals=true
	- spawn-monsters=true
	- entity-broadcast-range-percentage=75
	- player-idle-timeout=0
	- max-players=4

- Players vão usar
	- resource-pack=
	- require-resource-pack=false
	- resource-pack-prompt=
	- enable-command-block=false
	- force-gamemode=false
	- level-name=world
	- online-mode=false {true é para mine original}
	- max-world-size=29999984
	- allow-flight=false
	- enable-status=true

- Indevido para maioria dos players
	- broadcast-rcon-to-ops=true
	- enable-jmx-monitoring=false
	- resource-pack-sha1==
	- enable-rcon=false
	- rcon.password=
	- rcon.port=25575
	- sync-chunk-writes=true
	- enable-query=false
	- query.port=25565
	- op-permission-level=4
	- prevent-proxy-connections=false
	- rate-limit=0
	- snooper-enabled=true
	- function-permission-level=2
	- network-compression-threshold=256
	- text-filtering-config=
	- max-tick-time=60000
	- use-native-transport=true

- Inalteravel 100%
	- level-seed=-6476254842693137875
	- generator-settings={}
	- enforce-secure-profile=true
	- generate-structures=true
	- max-chained-neighbor-updates=1000000
	- initial-disabled-packs=
	- hide-online-players=false
	- initial-enabled-packs=vanilla
	- level-type=minecraft\:normal

# Como alterar quantia de consumo de ram do servidor
Para isto é necessário ter editor de texto como vscode, bloco de notas, notepad++ou sublimetext para fazer tal alteração, basta abrir um dos arquivos .bat ou os dois ao mesmo tempo, e trocar os valores de "-Xmx3G -Xms3G" para uma das seguintes opções:
- 512M
- 1G
- 2G
- 3G
- 4G (Recomendavel)
- 5G
- 6G (Confortável)
# Lista de mods
- Amplified Nether
- Better Third Person
- CITResewn
- Dynamic Sound Filter
- Fast Load
- Presence Footsteps
- Wi Zoom
- Audio Player
- Axolot Buckets "não funciona por algum motivo"
- Better Sodium Video Settings
- Chat Heads
- Cloth config
- Complete config
- Continuity
- Dynamic FPS
- Eating animation
- Emote craft
- Entity model features
- Entity texture features
- Entity culling
- Fabric api
- Ferrite core
- Indium
- Iris
- Krypton
- Lambdynamiclights
- Language reload
- Memoryleakfix
- Modmenu
- Reeses sodium
- Smoothboot
- Sodium extra
- Sodium fabric
- Sound physics
- Starlight
- Tooltipfix
- Simple Voice Chat
- Visuality
- Voice chat fabric
### [_Lista de Resource Pack_] (https://github.com/DIEG0FERNANDES/Resoucepacks_dos_Guri)
- Fresh Animation 1.19
- Bare Bones
# Lista de Shader Pack
- Complementary Shaders
- Chocapic v6
- BSL v8.3
- Sildurs Shaders enhanced fast
# Configurações recomendadas no sodium para pc potato, low ou mediano
As configurações devem ser de computador para computador, mas caso seu computador sejá realmente fraco, faça como nas imagens abaixo quando estiver disponivel as imagens, na duvida desative tudo que tu ache necessario e tenha impacto na sua maquina.