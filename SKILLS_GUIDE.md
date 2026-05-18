# 🚀 Brasil Motores - Guia de Skills de Front-End e UI/UX Design

Bem-vindo ao workspace do projeto **Brasil Motores**! Para criar uma experiência digital industrial de altíssimo nível, exportamos todas as principais metodologias, padrões e melhores práticas de Front-End e UI/UX Design diretamente para o diretório `skills/` do seu projeto.

Este guia serve como um índice interativo e manual estratégico. Ele agrupa as skills por categorias e ensina como combiná-las para criar um site que não apenas pareça moderno e premium (com estética rica, animações fluidas e elementos 3D), mas também seja otimizado para conversão B2B, acessibilidade e performance máxima.

---

## 📂 Visão Geral do Diretório de Skills

Todas as diretrizes completas estão disponíveis localmente no seu workspace em `skills/`. Aqui está como elas estão estruturadas:

```
brasilmotoresSite/
├── skills/
│   ├── ui-ux-designer/              # Fundamentos de Design e Sistemas Visuais
│   ├── ui-skills/                   # Restrições de Design Estrito para Interfaces
│   ├── web-design-guidelines/       # Estética Rica, Cores, Tipografia, Glassmorphism
│   ├── ui-visual-validator/         # Validação Visual de Layouts e Espaçamentos
│   ├── core-components/             # Modelos de Componentes e Padrões de Design System
│   ├── tailwind-patterns/           # Padrões do Tailwind CSS v4 e Variáveis CSS
│   ├── tailwind-design-system/      # Estrutura de Design Tokens e Cores Curadas
│   ├── react-patterns/              # Arquitetura e Estado em React Moderno
│   ├── nextjs-best-practices/       # Otimização com App Router e Server Components
│   ├── shadcn-ui/                   # Integração e Customização de Shadcn Components
│   ├── interactive-portfolio/       # Efeitos Hover, Micro-interações e Transições Premium
│   ├── scroll-experience/           # Animações Narrativas de Scroll e Efeitos Parallax
│   ├── 3d-web-experience/           # Integração e Renderização 3D na Web
│   ├── threejs-skills/              # Diretrizes de Performance e Código com Three.js
│   ├── shader-programming-glsl/     # Shaders de Alta Performance para Backgrounds Fluidos
│   ├── copywriting/                 # Técnicas de Escrita Persuasiva (Copy B2B)
│   ├── form-cro/                    # Otimização de Conversão para Formulários de Orçamento
│   ├── page-cro/                    # Otimização de Páginas de Produto e Portfólio
│   ├── popup-cro/                   # Banners de Captura e Ofertas Não Intrusivas
│   ├── seo-fundamentals/            # SEO Técnico, Core Web Vitals e Metadados
│   ├── schema-markup/               # Marcação de Dados Estruturados (Produtos, Motores, B2B)
│   ├── programmatic-seo/            # Geração de Páginas de Motores por Categoria/Potência
│   └── wcag-audit-patterns/         # Conformidade e Acessibilidade (WCAG 2.1/2.2 AA)
└── SKILLS_GUIDE.md                  # Este documento
```

---

## 🎨 1. Arquitetura de Design & Estética Industrial Premium
*Skills de referência:* `[ui-ux-designer]`, `[ui-skills]`, `[web-design-guidelines]`, `[tailwind-design-system]`

Para o site da **Brasil Motores** (motores elétricos industriais), o design deve transmitir **robustez, eficiência, precisão técnica e inovação de ponta**. 

### 📐 Diretrizes Visuais Estritas
* **Paleta de Cores Curada:** Evite azuis e pretos padrão de navegador. Utilize uma paleta industrial de alta fidelidade:
  * **Fundo (Modo Escuro):** Azul meia-noite profundo ou cinza de aço escovado (`#0F172A`, `#0B0F19`).
  * **Primária / Acento:** Laranja energético ou amarelo industrial vibrante (`#F97316` ou `#EAB308`) para botões de call-to-action e acentos, contrastando perfeitamente com tons metálicos escuros.
  * **Superfícies:** Cinzas polidos com bordas semi-transparentes para efeito *glassmorphism* (`rgba(30, 41, 59, 0.7)`).
* **Tipografia Moderna:** Use fontes sem serifa geométricas de alto desempenho, como **Outfit**, **Inter** ou **Roboto Mono** para dados técnicos de motores (potência, RPM, carcaça).
* **Bordas e Arredondamento:** Arredondamento elegante e moderno (`border-radius: 12px` ou `rounded-2xl`).

---

## 💫 2. Animações, Interatividade e Elementos 3D Imersivos
*Skills de referência:* `[scroll-experience]`, `[interactive-portfolio]`, `[3d-web-experience]`, `[threejs-skills]`, `[shader-programming-glsl]`

Um motor elétrico é uma máquina dinâmica. O site deve refletir isso sendo "vivo" e responsivo ao toque e scroll.

### ⚙️ Showroom 3D de Motores
* **Modelos Rotacionáveis (Three.js):** Integre visualizadores 3D interativos onde o cliente B2B pode girar um motor elétrico trifásico em 360°, ver suas partes internas (bobinado, rolamentos, rotor, caixa de ligação) de forma explodida.
* **Shaders Fluidos (`shader-programming-glsl`):** Use backgrounds de partículas ou ondas magnéticas fluidas geradas por GPU no fundo da seção "Hero" para representar o fluxo magnético e a indução eletromagnética dos motores.
* **Scroll-Triggered Animations:** À medida que o usuário rola a página, o motor 3D se move e se desmonta, revelando os diferenciais tecnológicos da Brasil Motores em tempo real (como a eficiência energética premium IE3 / IE4).

---

## 📈 3. Redação e Otimização de Conversão (CRO) B2B
*Skills de referência:* `[copywriting]`, `[form-cro]`, `[page-cro]`, `[popup-cro]`

O mercado de motores industriais envolve decisões de compra B2B racionais, focadas em retorno sobre o investimento (ROI), economia de energia, prazo de entrega e assistência técnica.

### ✍️ Copywriting Técnico e de Alto Impacto
* **Chamadas Centradas em Benefícios:** Em vez de apenas "Vendemos motores elétricos", utilize copy forte de vendas: *"Maximize a eficiência da sua indústria com motores elétricos de alto rendimento. Economia de até 30% no consumo de energia."*
* **Informação Clara e Direta:** Destacar os padrões de eficiência (IE2, IE3, IE4) e proteção (IP55, IP66).

### 📝 Formulário de Orçamento de Alto Rendimento (`form-cro`)
* **Fluxo de Cotação Inteligente:** Um formulário com etapas claras (Progressive Disclosure) onde o comprador seleciona o tipo de motor, a potência (CV/kW), a rotação (2, 4, 6 ou 8 polos) e a voltagem.
* **Preenchimento Automático:** Auxílio na digitação, preenchimento de endereço por CEP para indústrias e validação imediata livre de erros.
* **Opção de WhatsApp Direta:** Botões dinâmicos que enviam as especificações selecionadas diretamente para um consultor de vendas no WhatsApp.

---

## 🔍 4. SEO Técnico e Programmatic SEO Industrial
*Skills de referência:* `[seo-fundamentals]`, `[schema-markup]`, `[programmatic-seo]`

Engenheiros e compradores industriais procuram motores digitando códigos de carcaças, potências ou aplicações muito específicas no Google (ex: *"motor elétrico trifásico 5cv 4 polos ip55 carcaça 100L"*).

### 🤖 SEO Programático (Scale Optimization)
* Crie um sistema de templates dinâmicos para gerar páginas otimizadas para todas as combinações de motores (ex: 2 CV, 5 CV, 10 CV, 50 CV, 100 CV).
* Garanta que cada página de produto tenha títulos SEO exatos e descrições detalhadas baseadas nas especificações técnicas.

### 🏷️ Marcação de Dados Estruturados (`schema-markup`)
* Implemente dados estruturados JSON-LD do tipo `Product` e `LocalBusiness`.
* Forneça informações ricas como disponibilidade de estoque, potência do motor, certificação de eficiência (INMETRO / Procel) e avaliações dos clientes para que apareçam como rich snippets nos resultados de busca do Google.

---

## 🛠️ 5. Práticas de Desenvolvimento Front-End Moderno
*Skills de referência:* `[react-patterns]`, `[nextjs-best-practices]`, `[tailwind-patterns]`, `[shadcn-ui]`, `[zustand-store-ts]`

### 📦 Componentes Reutilizáveis & Estado Limpo
* Use React Standalone Components com propriedades fortemente tipadas em TypeScript.
* Mantenha o estado global de cotações e especificações no **Zustand** para máxima leveza e simplicidade.
* Desenvolva o site com foco total em **acessibilidade (WCAG 2.2 AA)**, garantindo contraste de cores excelente e navegação completa por teclado.

---

## 🏁 Próximos Passos para Criar o Site

Agora que temos as skills estruturadas e organizadas, estamos prontos para projetar e codificar o site da **Brasil Motores**. 

1. **Definição da Identidade Visual & Design System:**
   * Podemos ler o arquivo `skills/design-md/SKILL.md` e gerar um arquivo `DESIGN.md` semântico para a Brasil Motores, mapeando as cores, tipografia e espaçamentos ideais.
2. **Criação da Estrutura de Arquivos:**
   * Inicializar o ecossistema do projeto (Vite/React ou Next.js, dependendo da necessidade).
3. **Criação da Interface (Página Hero Interativa):**
   * Programar um layout hero majestoso com micro-animações nas especificações técnicas e suporte a renders de motores industriais.

*Dica: Você pode pedir para eu iniciar a criação do design de qualquer componente a qualquer momento!*
