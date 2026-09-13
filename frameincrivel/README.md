# 🎮 Frame Incrível — Seu Console Portátil no Celular

> **Landing Page / Link Hub Mobile-First de Alta Conversão (CRO)** para venda de acessos ao **Xbox Game Pass Cloud** e funil de engajamento gamer.

---

## 📍 Onde Está Localizado

* **Caminho no Projeto Local**: `C:\Users\Telum\Documents\GitHub\Dark_Sell\frameincrivel`
* **Repositório GitHub**: [`https://github.com/Telhum/Dark_Sell`](https://github.com/Telhum/Dark_Sell)
* **Estrutura no Monorepo**: Faz parte do monorepo `Dark_Sell`.

```text
Dark_Sell/
├── index.html                   # Página principal espelhada na raiz
├── vercel.json                  # Roteamento automático e cleanUrls da Vercel
├── README.md                    # Documentação geral do repositório
└── frameincrivel/               # 🎯 Esta pasta
    ├── README.md                # Esta documentação
    ├── index.html               # Landing page completa com CSS embutido
    ├── style.css                # Folha de estilo externa (backup / modular)
    └── assets/
        ├── logo.png             # Logo oficial Frame Incrível
        └── banner.png           # Banner de divulgação
```

---

## 💡 Qual a Ideia e o Que Estamos Vendendo?

### 🎯 Proposta de Valor
Transformar qualquer smartphone básico (Android ou iOS) em um **console de última geração**, sem que o cliente precise gastar milhares de reais em um Xbox Series X ou PC Gamer e sem precisar baixar gigabytes de arquivos.

### 🛒 Produtos & Elementos da Página

1. **🔥 Oferta Principal (Carro-Chefe de Venda)**:
   * **Produto**: **Xbox Game Pass Cloud (Acesso de 30 Dias)**.
   * **Preço de Venda**: **R$ 19,90** no PIX.
   * **Promessa**: Jogar títulos consagrados como *GTA V, Forza Horizon 5, FIFA/EA FC* direto na nuvem pelo celular, rodando a 60 FPS e sem filas de espera.
   * **Gatilhos de Conversão**:
     * Selo de *Poucas Vagas* e *Oferta Exclusiva*.
     * Botão pulsante com efeito shimmer para chamar o clique.
     * Envio imediato no WhatsApp com garantia de 30 dias.

2. **🚀 Funil de Engajamento / Lead Magnet (Jogo Grátis)**:
   * **Produto**: **Desafio Espacial** (Minigame web integrado).
   * **Link configurado**: [`https://phantom-asteroid.onrender.com`](https://phantom-asteroid.onrender.com)
   * **Objetivo**: Entreter o visitante que ainda está indeciso, reter o lead na página e criar senso de comunidade através de torneios diários com premiações via PIX.

3. **💬 Canal de Atendimento & Suporte VIP**:
   * Botão direto para contato humano no WhatsApp para tirar dúvidas de clientes leigos sobre compatibilidade e receber suporte pós-venda.

---

## 🌐 Onde Está na Vercel & Como Funciona o Deploy

### 🔗 Rotas de Acesso na Vercel
Como o repositório foi configurado como um monorepo com `vercel.json` e arquivo espelhado na raiz:

* **Acesso Direto pela Raiz**:  
  `https://dark-sell.vercel.app/` *(ou a URL personalizada do seu projeto na Vercel)*
* **Acesso pela Subpasta**:  
  `https://dark-sell.vercel.app/frameincrivel`

### ⚙️ Como Funciona o Deploy Automático
1. O repositório está conectado diretamente à conta da **Vercel** vinculada ao GitHub (`Telhum/Dark_Sell`).
2. Toda vez que você executar um `git push origin main`, a Vercel compila e publica as alterações em segundos.
3. O arquivo [`vercel.json`](../vercel.json) conta com a flag `"cleanUrls": true`, permitindo URLs limpas sem `.html` no final.

### ⚡ Performance e Otimizações
* **Zero Dependências Pesadas**: Feito em HTML5 puro, sem frameworks pesados como React ou Vue que pesariam na conexão móvel 4G/5G.
* **CSS Inline Crítico**: Todo o CSS moderno (Glassmorphism, gradientes neons, animações de brilho e botões) está embutido no `<head>` do `index.html`.
* **First Contentful Paint (FCP) < 50ms**: Abre instantaneamente ao ser clicado na bio do Instagram ou TikTok.

---

## 🛠️ Guia Prático: Como Personalizar Seus Links

Para começar a vender e receber as mensagens no seu número, abra o arquivo [`index.html`](index.html) e ajuste os seguintes pontos:

### 1. Colocar o seu WhatsApp de Vendas (Card 1)
Procure por `SEUNUMERO` no Card 1 e substitua pelo seu número com DDI (55 para Brasil) e DDD:
```html
<!-- De: -->
<a href="https://wa.me/SEUNUMERO?text=Ol%C3%A1!..." ...>

<!-- Para (exemplo): -->
<a href="https://wa.me/5511999999999?text=Ol%C3%A1!%20Vim%20pelo%20Instagram%20e%20quero%20o%20acesso%20do%20Game%20Pass%20Cloud%2030%20Dias%20por%20R$%2019,90" ...>
```

### 2. Alterar o Link do Jogo Grátis (Card 2)
Caso deseje apontar para outro funil ou minigame, altere o link no Card 2:
```html
<!-- Atualmente configurado para: -->
<a href="https://phantom-asteroid.onrender.com" ... id="btn-jogar-gratis">
```

### 3. Ajustar o WhatsApp de Suporte / Grupo VIP (Card 3)
Substitua `SEUNUMERO` ou insira o link de convite do seu grupo (`https://chat.whatsapp.com/...`):
```html
<a href="https://wa.me/5511999999999?text=Ol%C3%A1!%20Gostaria%20de%20tirar%20uma%20d%C3%BAvida%20e%20entrar%20no%20Grupo%20VIP" ...>
```

---

## 💻 Como Rodar e Testar Localmente

Se quiser visualizar as alterações no seu computador antes de subir:

1. **Pelo VS Code**:
   * Instale a extensão **Live Server**.
   * Clique com o botão direito em `frameincrivel/index.html` e selecione **Open with Live Server**.
2. **Pelo Terminal (Python)**:
   ```bash
   cd C:\Users\Telum\Documents\GitHub\Dark_Sell\frameincrivel
   python -m http.server 3000
   ```
   Acesse no navegador: `http://localhost:3000`

---

## 📈 Boas Práticas para Tráfego (Instagram & TikTok)

* **Bio do Instagram**: Coloque a URL direta da Vercel na bio (`Link na Bio`).
* **Chamada para Ação (CTA) nos Vídeos**: Use ganchos como:
  > *"Como jogar GTA V no celular fraco sem baixar nada por menos de R$ 20. Link no primeiro comentário ou na bio!"*
* **Rastreamento**: Se for rodar anúncios pagos (Meta Ads / TikTok Ads), insira o Pixel do Facebook / TikTok no `<head>` do `index.html`.
