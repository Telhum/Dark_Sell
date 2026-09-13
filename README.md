# 🎮 Dark_Sell — Monorepo de Mini Sites & Páginas de Vendas

Monorepo estruturado para hospedar múltiplos mini sites estáticos, landing pages de alta conversão e link hubs focados em tráfego mobile (Instagram, TikTok, WhatsApp).

---

## 📁 Estrutura do Repositório

```text
Dark_Sell/
├── .gitignore
├── vercel.json                 # Roteamento automático para a Vercel
├── README.md                   # Documentação do projeto
└── frameincrivel/              # Aplicação 1: Link Hub Gamer / Cloud Gaming
    ├── index.html              # HTML5 semântico, leve e otimizado para CRO
    ├── style.css               # Estilos Gamer Dark Mode (#0d0f17) + Neons + Glassmorphism
    └── assets/
        ├── logo.png            # Logo oficial do projeto
        └── banner.png          # Banner complementar
```

---

## ⚡ Aplicação 1: `/frameincrivel` (Play de Bolso)

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

O projeto já inclui um arquivo `vercel.json` configurado na raiz.

1. Acesse [vercel.com](https://vercel.com) e conecte sua conta do GitHub.
2. Importe o repositório **`Dark_Sell`**.
3. Em **Framework Preset**, selecione **Other**.
4. Clique em **Deploy**.
5. Sua página estará online em segundos com carregamento ultra-rápido (< 100ms)!

---

## ➕ Como Adicionar Novos Mini Sites no Monorepo

Para criar uma nova página de vendas ou mini site independente:
1. Crie uma nova pasta na raiz (ex: `/nova-oferta`).
2. Adicione os arquivos `index.html`, `style.css` e `assets/` dentro dela.
3. Se desejar uma rota personalizada, adicione o caminho no `vercel.json`.
