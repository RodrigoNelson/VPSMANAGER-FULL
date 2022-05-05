# Instalar script + atualizar pacotes do sistema

`apt update -y && apt upgrade -y && wget https://raw.githubusercontent.com/RodrigoNelson/VPSMANAGER-FULL/main/Plus; chmod 777 Plus; ./Plus`


# Liberar acesso root do sistema

`wget https://raw.githubusercontent.com/RodrigoNelson/VPSMANAGER-FULL/main/senharoot.sh; chmod 777 senharoot.sh; ./senharoot.sh`

# Atenção ao v2ray e trojan-go

Lembre-se que o V2RAY e TROJAN-GO está em desenvolvimento, então fique ciente dos riscos de bugs. Recomendo instalar em Ubunbu 18.04 para o melhor funcionamento.

# Portas padrão para não haver conflitos
- WEBSOCKET: 80
- TLS: 443
- V2RAY: 8080
- TROJAN-GO: 8000 (porta padrão para não haver conflito com websocket/v2ray)

# Créditos ao desenvolvedor principal
- @crazy_vpn sshplus