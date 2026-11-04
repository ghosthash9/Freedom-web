# Publicação no GitHub Pages

1. Crie no GitHub um repositório **público** chamado `ghosthash-ps4`.
2. Envie o conteúdo desta pasta para a raiz do repositório (não envie a pasta externa `ghosthash-ps4` como subpasta).
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`; clique em **Save**.
6. Aguarde a publicação. O endereço terá o formato `https://SEU-USUARIO.github.io/ghosthash-ps4/`.

Não é necessário manter o computador ligado depois que o GitHub Pages publicar o site.

## Atenção ao cache

O GitHub Pages não oferece configuração personalizada dos cabeçalhos HTTP
`Cache-Control` deste projeto. O `serve.sh` local define `no-store` para os
arquivos de código e payload; o GitHub Pages não permite reproduzir esse
comportamento exatamente. Por isso, valide o carregamento no PS4 e tenha em
mente que alterações recentes podem demorar a aparecer por causa do cache.

Para testar localmente, execute `./serve.sh` nesta pasta. Isso exige Python 3.
