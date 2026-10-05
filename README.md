# Planilha de Organização Financeira

Clone completo e funcional do site [planilhadeorganizacaofinanceira.online](https://planilhadeorganizacaofinanceira.online/).

## 📋 Sobre o Projeto

Este projeto é uma landing page interativa com um quiz de 5 perguntas para orientação financeira e funil de conversão para a **Planilha de Organização Financeira** (Google Planilhas).

### 🚀 Funcionalidades

- **Quiz interativo:** 5 perguntas rápidas com transições suaves e progresso em tempo real.
- **Resultado personalizado:** Algoritmo dinâmico (`result-rules.js`) que gera recomendações e passos práticos baseados nas respostas do usuário.
- **Apresentação em vídeo:** Demonstração integrada em vídeo da planilha.
- **Integração de checkout:** Integração com a plataforma Cakto e repasse automático de parâmetros UTM (`funnel.js`).
- **Persistência local:** Armazenamento do progresso via `sessionStorage`.
- **Design responsivo:** Estilização moderna e fluida com CSS nativo e fontes auto-hospedadas (Inter e Poppins).

## 📁 Estrutura de Arquivos

```text
├── index.html                  # Estrutura HTML principal do quiz e landing page
├── style.css                   # Folha de estilos e design tokens
├── script.js                   # Lógica da interface, navegação e interações do quiz
├── result-rules.js             # Lógica das regras e recomendação do quiz
├── funnel.js                   # Gerenciamento de eventos de rastreamento e checkout
└── assets/                     # Recursos visuais e mídias
    ├── fonts/                  # Fontes Inter e Poppins (.woff2)
    ├── video/                  # Vídeo de demonstração (.mp4) e poster (.jpg)
    ├── hero-stress.jpg         # Imagem principal da introdução
    ├── favicon.svg             # Ícone do site (SVG)
    ├── favicon-16.png          # Favicon 16x16
    ├── favicon-32.png          # Favicon 32x32
    └── apple-touch-icon.png    # Ícone para dispositivos Apple
```

## 🛠️ Como Executar Localmente

Não é necessário nenhum build ou dependência externa. Basta abrir o arquivo `index.html` em qualquer navegador ou servir via servidor local:

```bash
# Exemplo com Python:
python -m http.server 8000
```
Em seguida, acesse `http://localhost:8000`.
