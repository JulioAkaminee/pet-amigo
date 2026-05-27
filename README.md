# 🐾 Pet Amigo

> **Landing page premium para Pet Shop & Veterinária 24h em Bragança Paulista**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![A11y](https://img.shields.io/badge/WCAG_AA-Acessível-0F9E91?style=for-the-badge)

---

## ✨ Sobre o Projeto

O **Pet Amigo** é uma landing page de nível premium internacional para um Pet Shop e Clínica
Veterinária 24h em **Bragança Paulista, SP**. O projeto foi totalmente refatorado com foco em
estética de agência, micro-interações sofisticadas, performance e acessibilidade — transmitindo
ao mesmo tempo carinho, confiança e profissionalismo.

A linguagem visual combina **glassmorphism**, **gradientes sutis**, **sombras em camadas** e
**tipografia fluida**, sobre uma paleta quente e refinada inspirada no universo pet/veterinário.

---

## 🎨 Identidade Visual

| Elemento | Valor |
|----------|-------|
| **Primária (coral)** | `#F2622E` |
| **Secundária (teal)** | `#0F9E91` |
| **Acento (gold)** | `#F4A93C` |
| **Tinta / texto** | `#211C17` |
| **Fundos** | Creme `#FFFCF9` · Areia `#FBF5EE` |
| **Tipografia Display** | Sora (500–800) |
| **Tipografia Body** | Plus Jakarta Sans (400–700) |
| **Estilo** | Glassmorphism premium, gradientes sutis, grid de agência |

---

## 🏗️ Stack Tecnológica

- **HTML5** — Estrutura semântica, single-file, sem build
- **Tailwind CSS (CDN)** — Design system com tokens customizados (cores, sombras, raios, fontes)
- **JavaScript Vanilla** — Sem frameworks (sem React/Vue)
- **Intersection Observer API** — Reveals on-scroll, scroll-spy e contadores animados
- **Lucide Icons (CDN)** — Ícones consistentes e leves
- **Google Fonts** — Sora + Plus Jakarta Sans (máx. 2 famílias)
- **Imagens** — Unsplash & Pexels (URLs estáveis, com `lazy loading`)

---

## 🎬 Animações & Interações

Substituímos a biblioteca **AOS** por animações **CSS custom + Intersection Observer**:

- ✅ **Reveals com stagger** — entradas sequenciais por grupo (`data-stagger`)
- ✅ **Parallax suave** — blobs e cards flutuantes via `requestAnimationFrame` (throttled)
- ✅ **Micro-interações** — botões com efeito *sheen*, lift em cards, ícones que reagem ao hover
- ✅ **Contadores animados** — estatísticas que sobem ao entrar na viewport
- ✅ **Hamburger animado** — transforma em "X" com transição fluida
- ✅ **Loading states** — page loader, *skeleton/fade-in* de imagens
- ✅ **Navbar inteligente** — encolhe e ganha glass ao rolar, com scroll-spy do item ativo

---

## ⚡ Performance

- `preconnect` / `dns-prefetch` para fontes e CDNs de imagem
- `loading="lazy"` + `decoding="async"` em todas as imagens abaixo da dobra
- `fetchpriority="high"` na imagem principal do hero
- Atributos `width`/`height` para evitar **CLS** (layout shift)
- Animações **GPU-accelerated** (`transform` / `opacity`, `will-change`)

---

## ♿ Acessibilidade (WCAG AA)

- **Skip link** "Pular para o conteúdo"
- `aria-label`, `aria-current`, `aria-expanded`, `role="dialog"`, `aria-live` no formulário
- **Focus states** visíveis (`:focus-visible`) em toda a navegação
- Suporte completo a **`prefers-reduced-motion`** (desliga animações e parallax)
- HTML semântico (`header`, `main`, `nav`, `section`, `article`, `figure`, `blockquote`, `footer`)
- Contraste de cores em conformidade com nível AA

---

## 📑 Seções do Site

1. **Hero** — Headline com gradiente, estatísticas animadas, cards de confiança flutuantes
2. **Faixa de diferenciais** — Marquee contínuo com os principais serviços
3. **Serviços** — Banho & Tosa, Veterinária 24h, Hotelzinho, Adestramento + CTA de boas-vindas
4. **Produtos** — Grid de produtos premium com badges e botão de carrinho
5. **Galeria** — Mosaico responsivo com overlay no hover
6. **Depoimentos** — Avaliações de tutores em cards glass
7. **Agendamento** — Formulário validado + bloco de informações de contato
8. **Footer** — Navegação, redes sociais e créditos

---

## 📱 Responsividade

- Abordagem **mobile-first**
- **Tipografia fluida** com `clamp()` (sem saltos entre breakpoints)
- Menu **hamburguer animado** com overlay glass em telas menores
- Grids que se adaptam de 1 a 4 colunas conforme o dispositivo

---

## 🚀 Como Usar

1. Abra o arquivo `index.html` em qualquer navegador moderno
2. Não requer servidor nem build — tudo via CDN
3. Para deploy, faça upload do arquivo para qualquer hospedagem estática

---

## 📁 Estrutura

```
pet-amigo/
├── index.html      # Landing page completa (single-file)
└── README.md       # Documentação
```

---

## 📝 Notas

- As imagens são carregadas via CDN (Unsplash/Pexels) e não exigem arquivos locais
- O formulário de agendamento exibe confirmação no front-end; para integração, adicione um
  `action`/endpoint e trate o envio no `submit`

---

## 💼 Desenvolvido por

<p align="left"><strong>Akamine Web Studio</strong> — Bragança Paulista, SP</p>

Criado com 🧡 por [JulioAkaminee](https://github.com/JulioAkaminee) — desenvolvimento web,
design criativo e soluções digitais para negócios locais.

---

<p align="center">🐕 🐈 Feito com amor para pets 🐈 🐕</p>
