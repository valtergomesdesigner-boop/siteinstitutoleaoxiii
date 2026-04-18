# Instituto Leão XIII — Site Institucional

> *"Virgo Rosarii Victores nos Facit!"*

Site institucional do **Instituto Leão XIII**, uma Associação Civil de Direito Privado sediada em João Pessoa, Paraíba — Brasil. Desenvolvido em HTML, CSS e JavaScript puros (sem frameworks), com design clássico e tipográfico inspirado na tradição católica.

---

## Estrutura do Projeto

```
/
├── index.html        # Arquivo principal — todo o HTML, CSS e JS em um único arquivo
└── SVG LOGO.svg      # Logotipo/brasão do Instituto (necessário para exibição correta)
```

---

## Seções da Página

| Seção | ID | Descrição |
|---|---|---|
| Hero | — | Apresentação principal com brasão, título e botões de ação |
| O Combate | `#combate` | Texto sobre o contexto contemporâneo e a missão de resistência |
| Quem Somos | `#quem-somos` | Apresentação da associação e seus membros |
| Missão | `#missao` | Quatro pilares da atuação: Doutrina, Fé, Família e Salvação |
| Princípios | `#principios` | Fundamentos espirituais e citação bíblica |
| Contato / Rodapé | `#contato` | Endereço, e-mail e links para redes sociais |

---

## Tecnologias Utilizadas

- **HTML5** — Estrutura semântica
- **CSS3** — Estilização completa com variáveis, grid, animações e responsividade
- **JavaScript Vanilla** — Menu mobile e scroll reveal (sem dependências externas)
- **Google Fonts** — Tipografias: `Playfair Display`, `EB Garamond`, `Cormorant Garamond`

---

## Funcionalidades

- **Navbar fixa** com links de navegação âncora e efeito hover sublinhado
- **Menu hambúrguer** para dispositivos móveis (aparece abaixo de 920px)
- **Hero animado** com fundo texturizado, moldura ornamental e animação `fadeInUp`
- **Scroll reveal** — elementos entram suavemente na tela conforme o usuário rola a página
- **Destaque de link ativo** na navbar baseado na seção visível durante o scroll
- **Layout responsivo** com breakpoints em `920px` e `680px`

---

## Paleta de Cores

| Variável CSS | Valor | Uso |
|---|---|---|
| `--navy` | `#0E2E54` | Fundo da navbar, seção "Quem Somos" |
| `--blue` | `#004DA8` | Bordas dos cards de missão, labels |
| `--crimson` | `#AA0E1B` | Seção "Princípios", destaques em títulos |
| `--red` | `#ED1C2F` | Efeitos de gradiente |
| `--gold` | `#C9A84C` | Divisores ornamentais, bordas, destaques |
| `--gold-lt` | `#E8C97A` | Textos em fundo escuro, títulos no rodapé |
| `--cream` | `#F5F0E8` | Fundo principal da página |
| `--parchment` | `#EDE5D4` | Fundo da seção "Quem Somos" |
| `--dark` | `#0A1A2E` | Fundo do hero e rodapé |

---

## Como Usar

1. Clone ou baixe os arquivos do projeto.
2. Certifique-se de que o arquivo `SVG LOGO.svg` está na mesma pasta que o `index.html`.
3. Abra o `index.html` em qualquer navegador moderno — não requer servidor web.

```bash
# Opcionalmente, sirva localmente com Python:
python3 -m http.server 8000
# Acesse: http://localhost:8000
```

---

## Links Externos

- **Instagram:** [@institutoleaoxiii](https://www.instagram.com/institutoleaoxiii/)
- **Apoia.se:** [apoia.se/institutoleaoxiii](https://apoia.se/institutoleaoxiii)
- **E-mail:** contato@institutoleaoxiii.org

---

## Licença

© Instituto Leão XIII — Todos os direitos reservados.
