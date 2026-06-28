# 🌐 Atividade_Bootstrap_5

> Repositório destinado ao desenvolvimento do trabalho prático sobre a ferramenta de estilização e computação web **Bootstrap 5**.

Este projeto consiste em um portal de notícias moderno e totalmente responsivo voltado à cultura da internet, intitulado **Moji Maga Memes** (ou *Portal Awoo*). A aplicação explora componentes nativos do Bootstrap combinados com customizações avançadas de CSS para criar uma experiência de usuário rica e fluida.

---

## 🎨 Paleta de Cores do Projeto

O design foi construído utilizando uma identidade visual baseada em tons de roxo e lilás, configurada diretamente no escopo global (`:root`) do projeto:
* 🟪 **Roxo Profundo (`#2E073F`)**: Utilizado na Navbar, Rodapé e cabeçalhos de seções importantes.
* 🍇 **Roxo Vibrante (`#7A1CAC`)**: Cor dos botões principais, gradientes e destaques de borda.
* 🔮 **Lilás Aceso (`#AD49E1`)**: Aplicado a Badges e etiquetas de destaque.
* 🧼 **Lilás Pastel (`#EBD3F8`)**: Cor de fundo geral da página para garantir suavidade na leitura.

---

## 🚀 Funcionalidades e Destaques Técnicos

O portal foi desenvolvido aplicando conceitos modernos de Layout Responsivo (Mobile-First e Híbrido), destacando-se por:

1. **Estrutura Híbrida Inteligente na Hero Section:**
   * **No Desktop:** O conteúdo é exibido lado a lado de forma elegante (imagem alinhada à esquerda com proporções preservadas e textos detalhados à direita).
   * **No Mobile (Celular/Tablet):** Através do sistema de grid do Bootstrap, o layout se reorganiza de cima para baixo seguindo a ordem perfeita de leitura jornalística: **Manchete Principal ➔ Imagem da Notícia ➔ Título ➔ Texto Descritivo**.

2. **Garantia de Proporção de Imagens (Sem Distorção):**
   * Uso da propriedade `object-fit: cover;` combinada com alturas fixas para as miniaturas de notícias, impedindo que fotos com resoluções e proporções diferentes quebrem o alinhamento dos *cards*.

3. **Efeito Hover Interativo de Expansão:**
   * Ao passar o mouse (*hover*) sobre qualquer card de notícia, a imagem expande suavemente com efeito `scale` e transiciona para `object-fit: contain;`, permitindo que o usuário visualize a imagem original inteira sem nenhum corte.

4. **Componentes Bootstrap Utilizados:**
   * **Navbar Fixa (`fixed-top`)** com colapso responsivo para menu hambúrguer.
   * **Grids e Containers** dinâmicos (`row`, `col-lg-*`, `col-md-*`).
   * **Cards** com alinhamento flexível e empurramento de botões para a base (`mt-auto`).
   * **Modal Animado** centralizado para a captura de e-mails (Assinatura de Newsletter VIP).

---

## 🛠️ Tecnologias Utilizadas

* [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML) - Estruturação do portal.
* [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) - Customização de variáveis de cores, animações de hover e transições.
* [Bootstrap 5.3.3](https://getbootstrap.com/) - Framework principal para responsividade, utilitários de espaçamento, classes de botões e componentes Javascript.

---

## 💻 Como Executar o Projeto

Como o projeto é construído estritamente com tecnologias *Front-End* nativas, você não precisa instalar nenhuma dependência externa:

1. Clone este repositório:
   ```bash
   git clone [https://github.com/ViniciusSendoski/Atividade_Bootstrap_5]
