# VES Control — PWA

Web App simples para facilitar o acesso individual ao portal VES e lembrar a equipe da rotina semanal.

## Publicar gratuitamente pelo GitHub Pages
1. Crie um repositório público chamado `ves-control` na sua conta GitHub.
2. Envie todos os arquivos e pastas deste pacote para a raiz do repositório.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`, depois salve.
6. Aguarde a publicação. O endereço ficará parecido com `https://SEU-USUARIO.github.io/ves-control/`.
7. Fixe esse endereço no WhatsApp da empresa.

## Instalar
Abra o endereço publicado no Chrome/Android e use **Instalar aplicativo** ou **Adicionar à tela inicial**. No iPhone, abra no Safari, toque em Compartilhar e depois em **Adicionar à Tela de Início**.

## Lembrete semanal
O botão “Lembrete na agenda” baixa um evento recorrente para as segundas-feiras. O usuário precisa adicionar esse arquivo à agenda/calendário. Um PWA estático, sozinho, não consegue garantir notificações automáticas quando está fechado; isso exigiria um serviço de notificações push e configuração adicional.

## Importante
- O app não coleta, solicita ou armazena usuário/senha.
- O botão abre o portal oficial do VES em outra aba.
- Abrir o portal não comprova que o login foi concluído.
- Confirme com a Vale a regra vigente de inatividade e se o uso deste atalho é permitido.
