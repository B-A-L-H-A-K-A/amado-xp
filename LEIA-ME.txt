AMADO XP — PWA

Conteúdo:
- index.html: aplicação
- manifest.webmanifest: configuração de instalação
- sw.js: funcionamento offline
- icons/: ícones da aplicação

Para instalar no iPhone:
1. Publica TODOS estes ficheiros numa pasta de um site HTTPS.
2. Abre o endereço no Safari do iPhone.
3. Toca em Partilhar.
4. Escolhe “Adicionar ao ecrã principal”.
5. Ativa “Abrir como aplicação web”, se essa opção for apresentada.
6. Confirma “Adicionar”.

IMPORTANTE:
Não abras apenas index.html a partir da app Ficheiros. O manifest e o service worker
precisam de um site HTTPS para a experiência PWA completa.

Dados:
Os registos continuam guardados localmente no navegador/dispositivo através do
armazenamento da app. Limpar os dados do site/navegador pode apagar esses registos.
