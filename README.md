# Portfólio de Augusto Henrique do Amaral

Site estático em `dist/`, com páginas Projetos e Perfil, em português, inglês e espanhol. O idioma escolhido é salvo no navegador. O site não possui login ou edição pública.

**Site publicado:** https://portfolio-augusto-amaral-2026.meanderingmochi1.chatgpt.site/

O portfólio apresenta 3DEasy e Chronos Pomodoro, além de uma seção sobre minha atuação em produtos do Mercado Livre e do Itaú. As descrições dessas experiências se referem às frentes em que trabalhei, não aos aplicativos completos.

## Atualizar projetos

1. Abra `editor.html` no navegador (no seu computador), selecione `dist/projects.json` e edite os projetos no campo de texto. Clique em **Validar** e **Baixar projects.json**.
2. Substitua `dist/projects.json` pelo arquivo baixado. Cada projeto deve ter textos `pt`, `en` e `es`. Use links HTTPS públicos para aplicativo, código, foto e vídeo. `stack` e `gallery` são listas; `imageAlt` descreve a imagem principal nos três idiomas. `visualType: "timer"` é a prévia visual específica do Chronos.
3. Para uma imagem local, coloque o arquivo em `dist/assets/` e use o caminho relativo `./assets/nome-do-arquivo.jpg`. Para vídeo, prefira um arquivo MP4 publicado em uma URL HTTPS. `demoAccounts` contém apenas contas de teste autorizadas para divulgação pública; nunca inclua credenciais pessoais ou administrativas.
4. Pré-visualize o site e publique uma nova versão pelo fluxo Sites. O editor é local e fica fora de `dist/`, portanto visitantes não podem alterar os projetos.

3DEasy usa imagens e informações exibidas no seu site público; a contribuição individual e a stack ainda precisam de validação. As duas contas de teste foram fornecidas pelo proprietário para divulgação no portfólio. Chronos Pomodoro possui links públicos verificados para aplicativo e código; sua prévia visual no portfólio é uma composição baseada na interface, não uma captura de tela. A seção de experiência em produtos descreve frentes específicas do trabalho no Mercado Livre e no Itaú, sem atribuir autoria integral dos aplicativos. Seus links externos foram indicados pelo proprietário: páginas públicas de farmácia no México e na Argentina e a página inicial do Itaú.

## Desenvolvimento local

Sirva a pasta `dist/` em um servidor estático local. A leitura de `projects.json` pode ser bloqueada se `index.html` for aberto pelo protocolo `file:`.
