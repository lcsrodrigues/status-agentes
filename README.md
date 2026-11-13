# Status dos agentes

Painel publico com as notificacoes dos agentes em cada projeto.

- Cada evento e um arquivo em `data/events/`, criado pelo script `scripts/notify.ps1` de cada projeto.
- A pagina `index.html` le esses arquivos direto do GitHub e mostra o ultimo status por projeto e o historico.

Nao coloque tokens, senhas ou dados sensiveis nas mensagens, porque o repositorio e publico.
