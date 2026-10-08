# eye gate — abertura da apresentação

Site de entrada do TCC **EYE GATE** (sistema de acesso escolar com reconhecimento facial — turma 3CDS).
Formas Bauhaus flutuando em parallax → explosão de cores → intro cinematográfica com trilha sonora → **apresentação em PowerPoint** rodando dentro do próprio site.

## Estrutura

```
apresentacao/
├── index.html                     ← site completo (imagem, som e código embutidos — 1 arquivo só)
├── Apresentacao-EYE-GATE-TCC.pptx ← os slides (PowerPoint de verdade, 14 slides com transições)
└── README.md
```

## Como publicar (GitHub Pages)

1. Crie o repositório e suba os 3 arquivos desta pasta (ou a pasta inteira).
2. **Settings → Pages → Branch: `main` → Save.**
3. Em ~1 minuto o link fica ativo: `https://SEU-USUARIO.github.io/NOME-DO-REPO/`
   — é esse link que você manda pro professor.

## Como funciona a apresentação dentro do site

- **Site hospedado (GitHub Pages):** o site embute o **PowerPoint Online oficial da Microsoft**
  (`view.officeapps.live.com`) renderizando o `.pptx` desta mesma pasta. Os slides continuam
  sendo um arquivo PowerPoint — dá pra baixar e abrir no PowerPoint/Google Slides normalmente.
- **Opcional — Google Drive:** se preferir o visualizador do Drive, suba o `.pptx` no Drive
  (Compartilhar → Qualquer pessoa com o link), copie o ID do link
  (`drive.google.com/file/d/`**`ID`**`/view`) e cole em `ID_APRESENTACAO` no começo do `<script>` do `index.html`.
- **Abrindo direto do PC (file://):** aparece o botão *modo ensaio*, que abre o `.pptx` local no PowerPoint do computador.

## Trilha sonora

Trecho de *"Wave" (Tom Jobim)* a partir dos 30s, embutido no `index.html` em loop, com fade.
Durante a apresentação o volume cai automaticamente para 30% (botão de som na barra superior).
