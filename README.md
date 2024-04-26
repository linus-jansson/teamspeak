# teamspeak


docker run -d --name TeamSpeak3_Server -e TIME_ZONE=Europe/Berlin -p 9987:9987/udp -p 10011:10011/tcp -p 30033:30033/tcp -v ts3:/teamspeak/save/ ertagh/teamspeak3-server:latest
