# Time of Life

Calculadora de horas de trabalho para adquirir um produto

Esta é uma aplicação web simples que calcula quantas horas de trabalho são necessárias para adquirir um produto com base no salário e nas horas trabalhadas por mês. A interface utiliza Bootstrap para a estilização e jQuery para manipulação de dados.

## Funcionalidades

- **Entrada de Dados:** Permite ao usuário inserir o salário mensal, as horas trabalhadas por mês e o valor do produto.
- **Cálculo Automático:** Calcula automaticamente o número de horas e dias de trabalho necessários para adquirir o produto.
- **Interface Responsiva:** Utiliza Bootstrap para garantir que a interface seja amigável e responsiva em diferentes dispositivos.
- **Máscara de Entrada:** Utiliza jQuery Mask Plugin para formatar os campos de entrada monetários.

## Tecnologias Utilizadas

- HTML
- CSS
- JavaScript
- [Bootstrap](https://getbootstrap.com/)
- [jQuery](https://jquery.com/)
- [jQuery Mask Plugin](https://igorescobar.github.io/jQuery-Mask-Plugin/)
- [Svelte Toast](https://github.com/zerodevx/svelte-toast)

## Como Usar

Acessando o [projeto no GitHub Pages](https://gabriersdev.github.io/time-of-life) ou

1. **Clone o Repositório:**

    ```bash
    git clone https://github.com/gabriersdev/time-of-life.git
    cd time-of-life
    ```

2. **Abra o Arquivo `index.html` no Seu Navegador:**

    Basta abrir o arquivo `index.html` em seu navegador preferido.

## Estrutura do Projeto

```plaintext
time-of-life/
│
├── css/
│   └── animate.min.css             # Biblioteca de animações
│   └── bootstrap.min.css           # Estilos do bootstrap
│   └── pretendard.css              # Fonte de letra
│   └── styles.css                  # Estilos personalizados
│
├── js/
│   ├── bootstrap.bundle.min.js     # Scripts do Bootstrap
│   ├── jquery.min.js               # Biblioteca jQuery
│   ├── jquery.mask.min.js          # Plugin jQuery Mask
│   ├── popper.min.js               # Scripts para popovers e tooltips do Bootstrap
│   └── scripts.js                  # Scripts personalizados
│
├── index.html                      # Página principal da aplicação
│
└── README.md                       # Documentação do projeto
