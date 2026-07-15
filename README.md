# 💪 Vinicius Mascagni — Landing Page

Landing page de alta conversão para consultoria online de treino e dieta, com foco em transformar visitantes vindos do Instagram em leads qualificados via WhatsApp.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Responsive](https://img.shields.io/badge/Responsive-Mobile--First-D9506B?style=flat)
![Status](https://img.shields.io/badge/Status-Completo-A9314A?style=flat)

## Preview

![Preview](./img/preview.png)

## Sobre o Projeto

Site institucional de página única (one-page) desenvolvido para **Vinicius Mascagni**, personal trainer especializado em **consultoria online de treino e dieta**. A página foi pensada para receber tráfego principalmente do Instagram e converter esse visitante em lead através de um único caminho: o **WhatsApp**.

Todo o conteúdo — copy, prova social e CTAs — foi estruturado para guiar o usuário do primeiro impacto visual até o clique em "Falar no WhatsApp", reforçando autoridade, resultados reais de alunos e um processo de acompanhamento claro.

## Tecnologias Utilizadas

- 🧱 **HTML5** semântico (`header`, `main`, `section`, `footer`)
- 🎨 **CSS3** — custom properties, Grid, Flexbox, gradientes, glassmorphism (`backdrop-filter`) e animações
- ⚡ **JavaScript** vanilla — `IntersectionObserver` para scroll reveal e contadores animados, sem dependências
- 🔤 **Google Fonts** — Anton (display), Manrope (corpo de texto), Caveat (assinatura)
- 🧩 **Font Awesome 6** (via CDN)
- 📱 **Mobile-first**, totalmente responsivo

## Funcionalidades

- Navbar fixa, transparente no topo e sólida (com blur) ao rolar a página
- Scroll reveal com `IntersectionObserver` — elementos surgem conforme entram na tela
- Contadores animados na seção de números (count-up)
- Ticker de texto em loop infinito via CSS
- Botão flutuante de WhatsApp com animação de pulso
- Cards com hover premium (glow, borda gradiente, leve escala)
- Scroll suave entre seções
- SEO básico (meta tags, Open Graph)
- Acessibilidade: `alt` em imagens, `aria-label`, estados de `focus-visible` e suporte a `prefers-reduced-motion`

## Seções da Página

1. **Hero** — headline de impacto, foto e CTA principal
2. **Sobre** — apresentação do Vinicius e sua metodologia
3. **Como Funciona** — etapas da consultoria online
4. **Benefícios** — diferenciais do acompanhamento
5. **Depoimentos** — relatos reais de alunos
6. **Números** — indicadores de resultado (contadores animados)
7. **CTA Final** — chamada de conversão direta para o WhatsApp
8. **Footer** — contato e informações legais

## Paleta de Cores

| Uso                  | Cor                                  |
|----------------------|---------------------------------------|
| Background           | `#0A0A0A` / `#121212`                |
| Surface (cards)      | `#181818` / `#1F1F1F`                |
| Accent — vinho        | `#D9506B` / `#A9314A`                |
| Accent secundário — dourado | `#D4AF37`                       |
| Texto                | `#F2EFE9` / `#A8A49C`                |

## Como Rodar

Não há build, dependências ou `node_modules`. Basta abrir o arquivo diretamente no navegador:

```bash
# opção 1: abrir direto
open index.html      # macOS
start index.html     # Windows

# opção 2: usar Live Server (VS Code) ou qualquer servidor estático simples
npx serve .
```

## Deploy

Por ser um projeto 100% estático, pode ser publicado em qualquer serviço de hospedagem estática, como:

- [Vercel](https://vercel.com)
- [Netlify](https://netlify.com)
- [GitHub Pages](https://pages.github.com)

Basta apontar o serviço para a raiz do repositório — não há passo de build.

## Estrutura de Arquivos

```
/
├── index.html          # Estrutura HTML da página
├── css/
│   └── styles.css      # Estilos (variáveis, layout, componentes, animações)
├── js/
│   └── main.js         # Scroll reveal, navbar, contadores animados
└── img/
    └── vinicius-hero.png  # Foto usada na seção Hero
```

## Autor / Créditos

Desenvolvido por **Eduardo Ciudad**
🔗 [github.com/eduardo-Ciudad](https://github.com/eduardo-Ciudad)

Cliente: **Vinicius Mascagni** — Personal Trainer
📷 Instagram: [@vinicius.mascagni](https://instagram.com/vinicius.mascagni)

## Licença

Projeto freelance desenvolvido sob encomenda. Uso e distribuição do código restritos ao cliente, salvo autorização prévia.
