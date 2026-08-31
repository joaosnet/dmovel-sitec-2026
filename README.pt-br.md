<div align="center">

# ♿ DMovel — Apresentação Interativa SITEC UFPA 2026
### Acessibilidade Urbana Inteligente & Cartografia Colaborativa

[![English](https://img.shields.io/badge/Language-English-0361A3?style=for-the-badge&logo=googletranslate&logoColor=white)](README.md)
[![Português](https://img.shields.io/badge/Idioma-Portugu%C3%AAs%20(Atual)-22c55e?style=for-the-badge&logo=googletranslate&logoColor=white)](README.pt-br.md)
[![Deutsch](https://img.shields.io/badge/Sprache-Deutsch-f59e0b?style=for-the-badge&logo=googletranslate&logoColor=white)](README.de.md)
[![Français](https://img.shields.io/badge/Langue-Fran%C3%A7ais-8b5cf6?style=for-the-badge&logo=googletranslate&logoColor=white)](README.fr.md)

<br/>

[![Evento](https://img.shields.io/badge/Evento-SITEC%20UFPA%202026-0361A3?style=for-the-badge&logo=academia&logoColor=white)](https://lapshub.github.io/dmovel-sitec-2026/)
[![Datas](https://img.shields.io/badge/Datas-1%20e%202%20de%20Setembro%2C%202026-0284c7?style=for-the-badge)](https://lapshub.github.io/dmovel-sitec-2026/)
[![Instituição](https://img.shields.io/badge/Institui%C3%A7%C3%A3o-ITEC%20%2F%20LaPS%20%2F%20UFPA-0B132B?style=for-the-badge)](https://www.laps.ufpa.br/)
[![Acessibilidade](https://img.shields.io/badge/WCAG%202.1-Conformidade%20AAA-emerald?style=for-the-badge&logo=w3c&logoColor=white)](https://lapshub.github.io/dmovel-sitec-2026/)
[![Web App](https://img.shields.io/badge/App%20Online-dmovel__web__app-blueviolet?style=for-the-badge&logo=flutter&logoColor=white)](https://lapshub.github.io/dmovel_web_app/)

<p align="center">
  <strong>Apresentação interativa em 6 slides com Vídeo Motivador em tela cheia, Acessibilidade Universal & Teste ao Vivo por QR Code para a Semana do Instituto de Tecnologia (SITEC 2026) da Universidade Federal do Pará (UFPA).</strong>
</p>

[🌐 Ver Apresentação Online](https://lapshub.github.io/dmovel-sitec-2026/) • [📱 Testar DMovel Web App](https://lapshub.github.io/dmovel_web_app/) • [📄 Laboratório LaPS](https://www.laps.ufpa.br/)

</div>

---

## 📌 Visão Geral

O **DMovel** é um ecossistema aberto, distribuído e bilíngue de tecnologia assistiva, concebido para mapear, avaliar e transformar a mobilidade urbana e a acessibilidade física de pessoas com deficiência na Amazônia (Belém, PA) e no campus universitário da UFPA.

Este repositório contém a apresentação web oficial interativa para a **SITEC UFPA 2026 (Semana do Instituto de Tecnologia • 1 e 2 de setembro de 2026)**, construída sob rigoroso padrão de **engenharia de software e acessibilidade digital AAA**.

---

## 🎯 Destaques da Apresentação

### 1. 🎬 Intercalação com Vídeo Motivador em Tela Cheia
- Integração nativa com o **vídeo motivacional produzido pela Professora Kelly para o DMovel** (Direitos reservados ao DMovel / UFPA).
- O orador pode pressionar a tecla <kbd>M</kbd> (ou clicar no botão de vídeo no rodapé) para abrir a exibição cinematográfica e retornar fluidamente ao slide exato onde estava, sem perder o ritmo ou o estado da fala.

### 2. 📱 QR Code Persistente em Todos os Slides para Teste ao Vivo
- Cada um dos 6 slides possui um QR Code de alto contraste que permite a estudantes e professores na plateia apontarem a câmera do smartphone e abrirem imediatamente o Web App oficial em produção:
  👉 **`https://lapshub.github.io/dmovel_web_app/`**
- Slide 1 com Card Hero inicial, Slides 2 a 5 com badge compacto no topo direito, e Slide 6 com Mega QR Code para a sessão de perguntas e demonstração prática.

### 3. 🌓 Modo Projetor & Modo Escuro OLED Calibrados
- **Modo Projetor (Tema Claro):** Fundo `#F8FAFC`, tipografia escura `#0F172A` e azul institucional `#0361A3`, desenhado para resistir à luz ambiente de salas de aula e auditórios.
- **Modo Escuro (OLED):** Fundo `#070B19` com realces neon e contraste WCAG AAA.
- Alternância instantânea com a tecla <kbd>T</kbd>.

### 4. ♿ Recursos de Acessibilidade Universal Integrados (WCAG 2.1 AAA)
- **Leitor de Tela por Voz (TTS Integrado):** Pressione <kbd>V</kbd> para narrar o slide e as notas em português claro com a Web Speech API.
- **Zoom de Texto:** Ajuste o tamanho da fonte em tempo real com <kbd>+</kbd> e <kbd>-</kbd> (ou botões `A+` / `A-`).
- **Compatibilidade com Leitores de Tela:** Estrutura semântica ARIA (`role="region"`, `aria-live="polite"`), navegação integral por teclado e audiodescrições detalhadas.
- **Guia de Acessibilidade:** Pressione <kbd>A</kbd> para visualizar a lista de atalhos e recursos inclusivos.

---

## 🗂️ Estrutura dos 6 Slides (Foco em Produto & Engenharia)

1. **Slide 1 — Abertura SITEC 2026:** Missão DMovel, autoria, orientador e QR Code Hero de teste inicial.
2. **Slide 2 — O Desafio Urbano na Amazônia & Belém:** A barreira da falta de dados, desafios do campus da UFPA e números globais (15% OMS, 18,6M IBGE).
3. **Slide 3 — A Solução DMovel & Três Pilares:** Cartografia Colaborativa, Avaliação Multicritério Ponderada e Inclusão Global com Tradução Neural.
4. **Slide 4 — Galeria Mobile & Execução Real:** Capturas no hardware Samsung Galaxy M34 5G (Android 16): Biometria, Mapas Vetoriais, Sliders com Emojis e Temas Claro/Escuro.
5. **Slide 5 — Engenharia de Software Padrão AAA:** Flutter 3.41, Python 3.14 No-GIL / FastAPI, MongoDB com 2dsphere, Redis, Dash Mantine, Backblaze B2 e 380+ testes sem mocks.
6. **Slide 6 — Conclusão, Visão Futura & Mega Demonstração:** IA preditiva de barreiras por visão computacional, rotas acessíveis no campus, QR Code central e Q&A.

---

## 👥 Autoria & Créditos Acadêmicos

- **Discentes Pesquisadores / Apresentadores:**
  - **João da Cruz N. Neto** — Pesquisador & Engenheiro de Software (`joaodacruznatividade@gmail.com`)
  - **Daniel Moreira Barra** — Pesquisador & Discente de Engenharia Biomédica
- **Orientador:**
  - **Prof. Dr. Ronaldo de Freitas Zampolo** — Coordenador do Laboratório de Processamento de Sinais (LaPS)
- **Instituições:**
  - **LaPS / LAPSHub** (Laboratório de Processamento de Sinais)
  - **ITEC** (Instituto de Tecnologia)
  - **UFPA** (Universidade Federal do Pará), Belém, Pará

---

## ⌨️ Tabela de Atalhos do Apresentador

| Atalho | Ação |
| :--- | :--- |
| <kbd>→</kbd> / <kbd>Espaço</kbd> / <kbd>PageDown</kbd> | Próximo Slide |
| <kbd>←</kbd> / <kbd>PageUp</kbd> | Slide Anterior |
| <kbd>M</kbd> | Abrir / Fechar Vídeo Motivador em Tela Cheia |
| <kbd>T</kbd> | Alternar Modo Projetor / Modo Escuro |
| <kbd>V</kbd> | Iniciar / Pausar Leitor de Voz (TTS) |
| <kbd>+</kbd> / <kbd>-</kbd> | Aumentar / Diminuir tamanho das fontes |
| <kbd>N</kbd> | Abrir / Fechar Notas do Orador |
| <kbd>A</kbd> | Abrir Guia de Acessibilidade |
| <kbd>F</kbd> | Modo Tela Cheia no Navegador |
| <kbd>Home</kbd> / <kbd>End</kbd> | Ir para o Primeiro / Último Slide |
| <kbd>Esc</kbd> | Fechar Vídeo ou Janelas Modais |

---

## 🚀 Como Executar Localmente

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/LAPSHub/dmovel-sitec-2026.git
   cd dmovel-sitec-2026
   ```

2. **Suba um servidor HTTP local:**
   ```bash
   python -m http.server 8000
   ```

3. **Abra no navegador:**
   Acesse `http://localhost:8000/`
