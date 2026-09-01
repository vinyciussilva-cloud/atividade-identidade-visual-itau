# 🎨 Identidade Visual — Itaú
> Guia de Identidade Visual acadêmico focado em Tipografia, Teoria das Cores, Escala e Contraste Baseado no Ecossistema Itaú.

<p align="center">
  <img src="https://img.shields.io/badge/Ambiente-Production-FF6200?style=for-the-badge&logo=github" alt="Production">
  <img src="https://img.shields.io/badge/Design-Branding-267FE3?style=for-the-badge&logo=adobe-illustrator" alt="Branding">
  <img src="https://img.shields.io/badge/UI%2FUX-Design%20System-262323?style=for-the-badge&logo=figma" alt="Design System">
  <img src="https://img.shields.io/badge/Acessibilidade-WCAG%20AA-2FC63E?style=for-the-badge" alt="Acessibilidade">
</p>

---

## 📑 Sumário
- [📌 Sobre o Projeto](#-sobre-o-projeto)
- [🎯 Objetivos e Escopo](#-objetivos-e-escopo)
- [🧠 Arquitetura do Conceito](#-arquitetura-do-conceito)
- [🏷️ Anatomia do Logotipo](#️-anatomia-do-logotipo)
- [🎨 Sistema de Cores & Design Tokens](#-sistema-de-cores--design-tokens)
- [🔤 Arquitetura Tipográfica](#-arquitetura-tipográfica)
- [📏 Escala Tipográfica Proporcional](#-escala-tipográfica-proporcional)
- [🌓 Matriz de Contraste e Acessibilidade](#-matriz-de-contraste-e-acessibilidade)
- [🛠️ Stack Técnica e Conceitos](#️-stack-técnica-e-conceitos)
- [📂 Estrutura Arquitetural do Repositório](#-estrutura-arquitetural-do-repositório)
- [📚 Aprendizados & Key Takeaways](#-aprendizados--key-takeaways)
- [⚠️ Compliance & Disclaimer](#️-compliance--disclaimer)
- [👨‍💻 Autor](#-autor)

---

## 📌 Sobre o Projeto

O **Identidade Visual — Itaú** é um estudo de caso e projeto acadêmico de alta fidelidade desenvolvido para analisar, desconstruir e documentar os elementos estruturais de uma grande marca. 

O projeto transpõe os fundamentos de **Design Gráfico, Branding e Comunicação Visual** para uma documentação técnica viva, simulando as diretrizes reais de um **Brand Guidelines** moderno ou a especificação inicial de um **Design System**.

### 💎 Pilares de Engenharia do Design:
* **Consistência Sistêmica:** Garantia de que cada componente siga regras matemáticas de escala.
* **Acessibilidade Nativa:** Verificação sistemática de contraste para conformidade com padrões modernos de UI.
* **Documentação Semântica:** Tradução de cores e tipografias em tokens lógicos e utilizáveis.

---

## 🎯 Objetivos e Escopo

### 🎯 Objetivo Geral
Estruturar e consolidar um guia de identidade de marca inspirado no ecossistema visual do Itaú, validando teorias de **hierarquia visual, contraste cromático e design focado na experiência humana**.

### 🔍 Objetivos Específicos
* **Mapeamento Cromático:** Identificar e catalogar nuances primárias, secundárias e contextuais.
* **Sistematização Tipográfica:** Implementar uma escala tipográfica harmônica baseada em pesos e proporções de leitura.
* **Engenharia de Contraste:** Analisar combinações críticas de cores para mitigar problemas de legibilidade.
* **Arquitetura de Componentes:** Desenvolver uma árvore conceitual de dependência de elementos de design.

---

## 🧠 Arquitetura do Conceito

Uma identidade visual robusta funciona como um ecossistema modular onde a alteração de um nó impacta toda a percepção de valor da marca.

```text
                  [ SISTEMA DE IDENTIDADE VISUAL ]
                                 │
         ┌───────────────────────┼───────────────────────┐
         ▼                       ▼                       ▼
   [ BRANDING ]            [ COMPOSIÇÃO ]          [ ACESSIBILIDADE ]
         │                       │                       │
   ┌─────┴─────┐           ┌─────┴─────┐           ┌─────┴─────┐
   ▼           ▼           ▼           ▼           ▼           ▼
Logotipo    Conceito     Cores    Tipografia   Contraste  Legibilidade
                       (Tokens)    (Escalas)   (WCAG AA)   (Leitura)
```

---

## 🏷️ Anatomia do Logotipo

O logotipo atua como o ponto de gravidade da marca. Na engenharia deste guia, ele foi posicionado como o elemento raiz, estabelecendo a grade proporcional (*grid*) que governa o espaçamento e alinhamento de todos os subcomponentes secundários.

### 📐 Diretrizes de Implementação:
* **Área de Respiro (Safe Zone):** Proporções de margem calculadas dinamicamente para evitar poluição visual.
* **Relação de Aspecto (Aspect Ratio):** Preservação rigorosa do eixo X/Y para evitar distorções de renderização.
* **Variantes de Fundo:** Regras de aplicação sobre fundos claros (*Light Mode*) e fundos escuros (*Dark Mode*).

---

## 🎨 Sistema de Cores & Design Tokens

As cores foram transformadas em **Design Tokens** estruturados, divididos por semântica e funcionalidade para facilitar a reutilização de código e a manutenção do design.

### 🟠 Cores Primárias (Core Brand)
```text
Token: color-brand-primary-main | HEX: #FF6200
```
| Token Visual | Hex Code | Aplicação no Sistema |
| :--- | :---: | :--- |
| `primary-dark-1` | `#CC4E00` | Estados de hover, elementos pressionados, sombras sutis |
| `primary-main` | `#FF6200` | Cor de assinatura da marca, botões de ação principal (CTA) |
| `primary-light-1` | `#FF8133` | Bordas ativas, realces visuais secundários |

### 🔵 Cores Secundárias (Product Accents)
| Token Visual | Hex Code | Aplicação no Sistema |
| :--- | :---: | :--- |
| `secondary-light-1` | `#539AE9` | Links secundários, elementos de apoio decorativos |
| `secondary-main` | `#267FE3` | Cor ativa de produtos digitais, destaques de navegação |
| `secondary-dark-1` | `#1868BE` | Hover em elementos secundários, textos sobre azul claro |

### ⚫ Neutros Escuros (Dark Framework)
| Token Visual | Hex Code | Aplicação no Sistema |
| :--- | :---: | :--- |
| `neutral-dark-light` | `#403B3B` | Texto de leitura longo (parágrafos), descrições |
| `neutral-dark-main` | `#262323` | Títulos primários, cabeçalhos, elementos de alta densidade |
| `neutral-dark-deep` | `#0B0A0A` | Fundo de contraste escuro, áreas de isolamento total |

### ⚪ Neutros Claros (Light Framework)
| Token Visual | Hex Code | Aplicação no Sistema |
| :--- | :---: | :--- |
| `neutral-light-pure` | `#FFFFFF` | Texto em superfícies escuras, cartões, fundos internos |
| `neutral-light-main` | `#F2F5F7` | Cor padrão de background da interface (Canvas) |
| `neutral-light-dark` | `#D3DDE4` | Divisores de seção (borders), grids invisíveis, linhas |

### 🟢 Status: Sucesso (System Feedback)
| Token Visual | Hex Code | Aplicação no Sistema |
| :--- | :---: | :--- |
| `feedback-success-light`| `#7BE085` | Fundos de alertas positivos, badges de aprovação |
| `feedback-success-main` | `#52D65F` | Ícones de check, feedback de sucesso em formulários |
| `feedback-success-dark` | `#2FC63E` | Texto acessível de sucesso sobre fundos brancos |

### 🔴 Status: Erro & Crítico (System Alerts)
| Token Visual | Hex Code | Aplicação no Sistema |
| :--- | :---: | :--- |
| `feedback-danger-dark` | `#9E1500` | Texto de erro crítico, avisos de alta restrição |
| `feedback-danger-main` | `#D11C00` | Botões destrutivos, ícones de erro em validações |
| `feedback-danger-light`| `#FF2705` | Bordas de inputs inválidos, sinalizadores de atenção |

---

## 🔤 Arquitetura Tipográfica

### Poppins — The Modern Geometric Sans
A fonte **Poppins** foi selecionada devido à sua geometria cirúrgica e distribuição equilibrada de peso ótico, garantindo legibilidade perfeita tanto em microtextos de aplicações mobile quanto em grandes outdoors publicitários.

### ⚖️ Matriz de Pesos e Mapeamento Semântico
| Peso da Fonte | Nome Técnico | Token de Código | Escopo de Uso |
| :--- | :--- | :---: | :--- |
| **Regular (400)** | `Poppins Regular` | `weight-regular` | Corpo de texto, artigos, e-mails e parágrafos estruturais. |
| **Medium (500)** | `Poppins Medium` | `weight-medium` | Rótulos de botões, tags de estado, cabeçalhos de tabelas. |
| **SemiBold (600)** | `Poppins SemiBold`| `weight-semibold`| Subtítulos, títulos de componentes, seções internas. |
| **Bold (700)** | `Poppins Bold` | `weight-bold` | Títulos de seções principais (`H1`), chamadas épicas. |

---

## 📏 Escala Tipográfica Proporcional

O projeto adota o princípio de **Escala Modular Baseada em 4px / 8px** para assegurar harmonia matemática vertical entre todos os níveis de texto.

| Nível de Escala | Tamanho (px) | Tamanho (rem) | Line-Height | Uso Recomendado |
| :--- | :---: | :---: | :---: | :--- |
| **Display / H1** | `32px` | `2.0rem` | `125%` | Título principal de Hero |
| **Heading / H2** | `24px` | `1.5rem` | `130%` | Cabeçalhos de seções principais |
| **Subheading / H3**| `20px` | `1.25rem` | `135%` | Títulos de módulos e blocos |
| **Body (Padrão)** | `16px` | `1.0rem` | `150%` | Texto corrido e leitura fluida |
| **Small / Caption**| `12px` | `0.75rem` | `140%` | Legendas, notas de rodapé, tokens |

---

## 🌓 Matriz de Contraste e Acessibilidade

Alinhado com as diretrizes internacionais da **WCAG 2.1 (Web Content Accessibility Guidelines)**, o ecossistema de cores passou por uma simulação de conformidade de contraste para a camada de texto:

* **Texto Dark (`#262323`) sobre Fundo Light (`#F2F5F7`):** Proporção de contraste superior a **7:1** (Aprovado em nível **WCAG AAA** para qualquer tamanho de fonte).
* **Texto Light (`#FFFFFF`) sobre Fundo Primário (`#FF6200`):** Proporção limítrofe. Recomenda-se o uso estrito do peso **Bold (700)** para garantir a leitura estável (Aprovado em nível **WCAG AA** para textos grandes/fortes).
* **Texto Light (`#FFFFFF`) sobre Fundo Secundário (`#267FE3`):** Proporção em conformidade estável para textos médios e grandes (Aprovado **WCAG AA**).

---

## 🛠️ Stack Técnica e Conceitos

Para a modelagem deste repositório e materialização teórica da marca, empregaram-se as seguintes competências e frameworks analíticos:
* **Figma** (Modelagem espacial de vetores, gerenciamento de bibliotecas de componentes e grids).
* **Design System Principles** (Transformação de valores hexadecimais puros em tokens semânticos funcionais).
* **Teoria das Cores de Munsell & Ostwald** (Criação de escalas harmônicas de luminosidade e saturação).
* **Markdown Sintático Avançado** (Estruturação semântica da documentação em repositórios Git).

---

## 📚 Aprendizados & Key Takeaways

O desenvolvimento deste estudo aprofundado consolidou conceitos valiosos sobre o ciclo de vida do design centrado no usuário:
1. **A marca é um ser vivo:** Entender que a consistência visual dita o nível de confiança que o usuário deposita no software.
2. **A acessibilidade não é opcional:** Criar pensando nas paletas de sucesso e perigo com variantes escuras prova que o bom design é inclusivo por natureza.
3. **Documentação economiza tempo:** Estruturar tabelas limpas e escalas numéricas claras reduz drasticamente o atrito de comunicação entre designers e engenheiros de software (*Design Hand-off*).

---

## ⚠️ Compliance & Disclaimer

Este repositório possui natureza **estritamente acadêmica, demonstrativa e pedagógica**. As marcas, logotipos, identidades corporativas e propriedades intelectuais mencionadas pertencem ao **Itaú Unibanco S.A.** O projeto foi estruturado sem fins lucrativos ou comerciais, visando exclusivamente o estudo acadêmico de técnicas de design de interface e documentação técnica.

---

## 👨‍💻 Autor

Desenvolvido com dedicação por VINYCIUS LOPES MONETRIO DA SILVA. Conecte-se comigo e confira meus outros projetos de design e desenvolvimento de software!

<p align="left">
  <a href="https://github.com"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---
<p align="center">Se este estudo de caso de design foi útil para você ou serviu de inspiração, por favor deixe uma ⭐️ no repositório!</p>
