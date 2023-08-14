<img src="https://oriondesign.art.br/wp-content/uploads/2023/08/Capa-tuto-git.webp">

# Auto Instalador do Typebot

Este auto instalador foi testado usando uma VPS vazia da Contabo (4vCores + 8Gb Ram) com **Ubunto 20.04**

### 📌 Observações importantes:

Recomendo criar uma snapshot da sua vps para evitar qualquer problema que possa vir acontecer.

Antes de instalar, é de extrema importancia que você crie 3 registros no DNS, sendo eles “typebot”, “bot” e “storage”. Todos do Tipo **A**, todos apontando para o **ip da sua VPS**, com **Proxy desativado** e **TTL Auto** (ou o valor que vier).
<details>
  <summary>Sobre o registro typebot</summary>
  <i>É através dele que conseguiremos acessar o sistema para criarmos o nosso bot, tambem é conhecido como Builder (construtor)</i><br><br>
  • Tipo: <b>A</b><br>
  • Entrada: <b>typebot</b><br>
  • Conteúdo: <b>IP do servidor</b><br><br>
  <img src="https://file.notion.so/f/s/c14b5ac1-d43a-4f18-bd76-4f10bd4262f1/Untitled.png?id=9855df72-743c-439d-b865-ec8391b93cc4&table=block&spaceId=f554c1aa-b56c-4ac0-88b1-4679371e6777&expirationTimestamp=1692072000000&signature=whfO8e8AETlGp2JEWdt0ML-i1QIlPr4kejWSGPXk-qY&downloadName=Untitled.png">
</details>
<details>
  <summary>Sobre o registro bot</summary>
  <i>Essa é a tela do Visualizador do bot, então quando você publicar seu bot, ele irá vir através do link bot.seudominio.com.br</i><br><br>
  • Tipo: <b>A</b><br>
  • Entrada: <b>bot</b><br>
  • Conteúdo: <b>IP do servidor</b><br><br>
  <img src="https://file.notion.so/f/s/236f6cc3-4857-4c48-a9d0-8b0b35c0ba94/Untitled.png?id=5703d967-1b89-423f-a6b1-60a377785be4&table=block&spaceId=f554c1aa-b56c-4ac0-88b1-4679371e6777&expirationTimestamp=1692072000000&signature=k1X9OIvmNeNfFzrKQg5xpqcS-HLcY9_x4zoc1sq8M6o&downloadName=Untitled.png">
</details>
<details>
  <summary>Sobre o registro storage</summary>
  <i>Utilizamos para salvar imagens, vídeos, áudios no nosso servidor para não precisar de exportar seu conteúdo para outro lugar e usar o link em nosso Typebot.</i><br><br>
  • Tipo: <b>A</b><br>
  • Entrada: <b>storage</b><br>
  • Conteúdo: <b>IP do servidor</b><br><br>
  <img src="https://file.notion.so/f/s/571842de-ad54-42e3-980e-542204b6ad0c/Untitled.png?id=c5772588-3c3f-4bd9-ad5c-8c7fc29d3d0a&table=block&spaceId=f554c1aa-b56c-4ac0-88b1-4679371e6777&expirationTimestamp=1692072000000&signature=OHFt_mSTmTRB9PEnhwllhnHQdCbzOa69ewqj5_PYRIc&downloadName=Untitled.png">
</details>

<hr/>

## 📀 Instalando Typebot

1- Copie o seguinte comando e cole em seu terminal:
```
git clone https://github.com/oriondesign2015/AutoInstaladorTypebot.git && cd AutoInstaladorTypebot && chmod +x typebot.sh && ./typebot.sh
```

Ao executar esse código, ele pedirá para você fornecer as seguintes informações:
  - Link do Builder (ex: typebot.seudominio.com);
  - Porta do Builder (padrão: 3001);
  - Link do Viewer (ex: bot.seudominio.com);
  - Porta do Viewer (padrão: 3002);
  - Link do Storage (ex: storage.seudominio.com);
  - Porta do Storage (padrão: 9000);
  - Seu Email (ex: contato@dominio.com);
  - Senha do seu Email (se for gmail, precisa ser a senha de aplicativo);
  - SMTP do seu email (ex: smtp.hostinger.com);
  - Porta SMTP (ex: 465);
  - SMTP_SECURE (Se a porta SMTP for 465, digite true, caso contrario,digite false);
  - Chave secreta de 32 caracteres (gerada no site: <a href="https://codebeautify.org/generate-random-hexadecimal-numbers">codebeautify</a>).

Após preencher os campos corretamente ele já iniciará a instalação e configurações do Typebot.

>
> No final fa instalação aparecerá uma mensagem, digite "Y" e de "ENTER" para finalizar a instalação do typebot.
>

<hr/>

### 💡 Ficou com alguma dúvida?

Entre em contato comigo através do WhatsApp [clicando aqui](http://wa.me/+5511973052593).

<hr/>

### ❤️ Agradecimentos

Agradoço especialmente o <a href="https://github.com/DeividMs">Deivid Santos</a> por ter me ensinado e insentivado a usar o GitHub, alem de me ensinar muitas outras coisas do universo da programação.
Tambem meus agradecimentos para o pessoal da comunidade <a href="https://github.com/cwmkt">CWMKT</a>.
<br><br><br>
Agora fique com o pato dançando:<br><br>
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3hpaTI2dzVuMGZmMnFteWE1bW80Z29hYXZub3cybTQyZHFrc2VoaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/b9QBHfcNpvqDK/giphy.gif">
