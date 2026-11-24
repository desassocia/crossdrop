# CrossDrop

Site experimental para transferir arquivos entre iPhone, Android e computador usando PeerJS/WebRTC.

## Publicar gratuitamente com GitHub Pages

1. Abra **Settings** neste repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch **main** e a pasta **/(root)** e salve.
5. Aguarde o GitHub publicar. O endereço será https://desassocia.github.io/crossdrop/.

## Como usar

- No aparelho que envia: abra o site, escolha arquivos e toque em **Gerar código de conexão**.
- No aparelho que recebe: abra o site, entre em **Receber**, digite o código e toque em **Conectar e receber**.
- Mantenha as duas páginas abertas durante a transferência.

## Observações

- A conexão inicial usa o serviço público de sinalização PeerJS. Os dados são transferidos por WebRTC diretamente entre os aparelhos quando a rede permite.
- Os arquivos não são enviados para o GitHub nem armazenados por este site.
- Algumas redes podem impedir a conexão direta; nesse caso, tente outra rede Wi-Fi ou dados móveis.
- Esta é uma primeira versão experimental. Teste primeiro com arquivos pequenos. Arquivos muito grandes podem consumir bastante memória no aparelho que recebe.
- Não use para arquivos sensíveis até concluir testes de segurança e confiabilidade.
