# Claro · Assistente de escrita (versão GitHub Pages · Gemini)

Ficheiros: `index.html`, `manifest.webmanifest`, `logo.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`.
Nenhum destes ficheiros contém a chave da API: a chave é colada na app e fica guardada só no iPhone.

## 1. Chave da API Gemini (grátis)
1. Entra em https://aistudio.google.com/apikey com a tua conta Google.
2. Toca em "Create API key" (cria/escolhe um projeto) e copia a chave (começa por `AIza`).
3. Não ligues faturação: assim ficas no plano gratuito e nunca há custos (se passares o limite, a app só avisa para esperares).
4. Nota: no plano gratuito a Google pode usar os textos para melhorar os produtos. Evita dados confidenciais.

## 2. Publicar no GitHub Pages
1. Em github.com, cria um repositório **público** chamado `claro` (sem README).
2. Dentro do repositório: Add file › Upload files › arrasta os 6 ficheiros › Commit changes.
3. Settings › Pages › Source: "Deploy from a branch" › Branch: `main` / `(root)` › Save.
4. Espera 1–2 minutos. O endereço fica `https://O-TEU-UTILIZADOR.github.io/claro/`.

## 3. Instalar no iPhone
1. Abre o endereço no **Safari** (não na app do Claude).
2. ⋯ › Partilhar › Adicionar ao ecrã principal › Adicionar.
3. Abre a app pelo ícone, vai a Definições › Ligação à IA, cola a chave e toca em Testar.

## Atualizar
Volta a fazer Upload files com o `index.html` novo e Commit. O iPhone apanha a versão nova ao reabrir (às vezes é preciso fechar e abrir a app).

## Segurança
- Nunca coloques a chave em nenhum ficheiro do repositório.
- Se perderes o iPhone ou suspeitares de uso indevido, apaga a chave no Google AI Studio e cria outra.
