# Auto Instalador do Typebot

Este auto instalador foi testado usando uma VPS vazia da Contabo (4vCores + 8Gb Ram) com **Ubunto 20.04**

## Observações importantes:
- Recomendo criar uma snapshot da sua vps para evitar qualquer problema que possa vir acontecer;
- Antes de iniciar a instalação, crie 3 registros no seu DNS do tipo **A**, sendo eles typebot, bot, storage
<hr/>

Vamos precisar de 3 registros, sendo eles “typebot”, “bot” e “storage”, todos de Tipo A, todos apontando para o ip da sua VPS, Proxy desativado e TTL Auto (ou o valor que vier).

<details>
  <summary>typebot</summary>
  • Tipo: <b>A</b>
  • Entrada: <b>typebot</b>
  • Conteúdo: <b>IP do servidor</b>
  <img src="https://file.notion.so/f/s/c14b5ac1-d43a-4f18-bd76-4f10bd4262f1/Untitled.png?id=9855df72-743c-439d-b865-ec8391b93cc4&table=block&spaceId=f554c1aa-b56c-4ac0-88b1-4679371e6777&expirationTimestamp=1692072000000&signature=whfO8e8AETlGp2JEWdt0ML-i1QIlPr4kejWSGPXk-qY&downloadName=Untitled.png">
</details>

1- Copie o seguinte comando e cole em seu terminal:
```
git clone https://github.com/oriondesign2015/AutoInstaladorTypebot.git && cd AutoInstaladorTypebot && chmod +x typebot.sh && ./typebot.sh
```

Ao executar esse código, ele pedirá para você fornecer as seguintes coisas:
  - Link do Builder (ex: typebot.seudominio.com)

Observações sobre provedores de email
<details>
  <summary>Gmail</summary>

  >
  >
  >
  
</details>

# instalando-docker

>blablabla
>
>bleblebleble
>

<p align="center">
    <img src="https://imagepng.org/google-chrome-icone-icon/google-chrome-icon/" alt="Logo Chatwoot" width=70>
</p>

<ul>
  <li>teste</li>
</ul>


[Instalação Docker](#instalando-docker) |
[Instalação Portainer](#instalando-portainer) |
[Instalação Postgree](#instalando-postgree) |
[Instalação Bridge e Botpress](#instalando-o-bridge-e-bortpress) |
[Conectando Chatwoot Botpress](#conectando-chatwoot-com-botpress)
