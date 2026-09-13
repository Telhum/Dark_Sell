# 🎮 Dark_Sell — Monorepo de Mini Sites & Páginas de Vendas

Monorepo estruturado para hospedar múltiplos mini sites estáticos, landing pages de alta conversão e link hubs focados em tráfego mobile (Instagram, TikTok, WhatsApp).

---

## 📁 Estrutura do Repositório

```text
Dark_Sell/
├── .gitignore
├── vercel.json                 # Roteamento automático para a Vercel
├── README.md                   # Documentação do projeto
├── assets/                     # Assets globais do monorepo
└── frameincrivel/              # Aplicação 1: Frame Incrível (Cloud Gaming & Games)
    ├── index.html              # HTML5 com CSS embutido de alta performance
    ├── style.css               # Folha de estilos externa complementar
    └── assets/
        ├── logo.png            # Logo oficial do projeto
        └── banner.png          # Banner complementar
```

---

## ⚡ Aplicação 1: `/frameincrivel` (Frame Incrível)

Landing Page / Link Hub voltada para conversão de vendas de Cloud Gaming e jogos mobile.

### 🛠️ Como Personalizar os Links

Abra o arquivo [`frameincrivel/index.html`](frameincrivel/index.html) e edite os seguintes campos:

1. **Número de WhatsApp (Card 1 e Card 3)**:
   - Procure por `SEUNUMERO` no código e substitua pelo seu número com código do país (DDI) e DDD.
   - **Exemplo**: `https://wa.me/5511999999999?text=...`

2. **Link do Jogo Grátis (Card 2)**:
   - Procure por `[SEU_LINK_DO_JOGO]` no código e substitua pela URL do seu jogo ou funil.
   - **Exemplo**: `https://seujogo.vercel.app`

---

## 🚀 Como Fazer o Deploy na Vercel

O projeto já inclui um arquivo `vercel.json` e CSS embutido direto no `index.html`, garantindo carregamento instantâneo e renderização visual impecável.

1. Acesse [vercel.com](https://vercel.com) e conecte sua conta do GitHub.
2. Importe o repositório **`Dark_Sell`**.
3. Clique em **Deploy**.
4. O Vercel atualizará automaticamente toda vez que você fizer `git push`!
