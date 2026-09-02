# Diretrizes e Regras Obrigatórias para Agentes de IA (AGENTS.md)

Este repositório (`joaosnet/dmovel-sitec-2026`) hospeda o site e apresentação oficial do projeto **DMovel** para a **SITEC UFPA 2026** (Semana do Instituto de Tecnologia da Universidade Federal do Pará), publicado via GitHub Pages em `https://joaosnet.github.io/dmovel-sitec-2026/`.

Qualquer agente de IA autônomo (Antigravity, Cursor, Claude, Copilot, etc.) que opere neste projeto **DEVE SEGUIR ESTRITAMENTE AS REGRAS ABAIXO SEM EXCEÇÃO**.

---

## 1. Regra Obrigatória: Logotipo Oficial da SITEC 2026 UFPA
- **SITEC 2026:** Em qualquer local do site onde estiver escrito `SITEC 2026` ou for mencionada a `SITEC 2026` / `Semana do Instituto de Tecnologia`, deve constar obrigatoriamente o **logotipo oficial do SITEC 2026 UFPA**.
- Os arquivos do logotipo oficial estão localizados em:
  - `assets/images/logo_sitec_icon.png` (ícone circular de alta resolução para badges, botões, modais e pílulas);
  - `assets/images/logo_sitec_2026.png` e `assets/images/logo_sitec_2026.svg` (versões completas com tipografia oficial do evento e ITEC/UFPA).
- Nunca remova o logo nem substitua por ícones genéricos sem o logotipo do evento.

---

## 2. Regra Obrigatória: Atualização Contínua do Social Preview Remoto
- **Social Preview Sempre Sincronizado:** Sempre que houver qualquer modificação visual, estrutural, de texto ou de layout no site, o agente de IA deve obrigatoriamente:
  1. Capturar o screenshot da versão atualizada do site na proporção exata **1280 × 640 px** (padrão 2:1 recomendado pelo GitHub), preferencialmente com o slide 1 renderizado e a barra de navegação inferior (`footer.glass-nav`) temporariamente oculta para obter uma imagem limpa tipo banner.
  2. Sobrescrever o arquivo na raiz do repositório: `social_preview.png`.
  3. Sobrescrever o arquivo na pasta de assets: `assets/images/social_preview.png`.
  4. Garantir que as metatags Open Graph e Twitter Card no `<head>` de `index.html` apontem para a imagem atualizada com URL absoluta:
     - `<meta property="og:image" content="https://joaosnet.github.io/dmovel-sitec-2026/assets/images/social_preview.png">`
     - `<meta property="og:image:secure_url" content="https://joaosnet.github.io/dmovel-sitec-2026/assets/images/social_preview.png">`
     - `<meta property="og:image:width" content="1280">`
     - `<meta property="og:image:height" content="640">`
     - `<meta name="twitter:image" content="https://joaosnet.github.io/dmovel-sitec-2026/assets/images/social_preview.png">`
  5. Atualizar os banners no topo dos READMEs caso necessário.
  6. Fazer o commit e push para o repositório remoto no GitHub (`joaosnet/dmovel-sitec-2026`, branch `main`).

---

## 3. Regras de Conteúdo, Autoria e Identidade Institucional
- **Autoria Discente:** João da Cruz N. Neto e Daniel Moreira Barra.
- **Orientação Docente:** Prof. Dr. Ronaldo de Freitas Zampolo e Prof. Dr. Agostinho Luiz da Silva Castro.
- **Laboratórios Associados:** Sempre que o laboratório **LaPS** for mencionado, o **LAMIC** deve ser incluído conjuntamente (**LaPS & LAMIC • ITEC / UFPA**).
- **Link e Rótulo de Contato:** O link do autor João Neto deve apontar exclusivamente para sua página de contato pessoal: `https://joaosnet.github.io/`. A palavra usada na interface deve ser sempre **"Contato"** (nunca "Portfólio" ou e-mail).
- **Tradução:** No slide 3 e em todo o material, o termo a ser utilizado é **"Tradução Dinâmica"** (e não "Tradução Neural").

---

## 4. Padrão de Qualidade e Responsividade (AAA)
- O site deve ser 100% responsivo e calibrado para apresentações em telas de **1280 × 720** (Desktop/Projetor), **360 × 760** (Smartphone em modo retrato) e **760 × 360** (Smartphone em modo paisagem).
- Nenhuma imagem, texto, pilar ou mockups de celular deve ficar cortado ou inacessível.
- A rolagem vertical fluida (`overflow-y: auto`, `-webkit-overflow-scrolling: touch`) deve estar ativa nos slides quando o conteúdo exceder a altura da tela em dispositivos móveis.
- Validação dinâmica obrigatória via ferramentas Playwright/MCP antes de considerar qualquer alteração concluída.
