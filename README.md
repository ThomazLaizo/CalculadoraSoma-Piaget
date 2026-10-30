# ➕ Calculadora de Soma

Calculadora web simples que soma dois números informados pelo usuário e exibe o resultado na tela. Projeto acadêmico da faculdade **Piaget**, desenvolvido para praticar **JavaScript e manipulação do DOM**.

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Linguagem principal](https://img.shields.io/github/languages/top/ThomazLaizo/CalculadoraSoma-Piaget)

## 🎓 Sobre o projeto

Este projeto foi desenvolvido na faculdade **Piaget** como atividade prática de JavaScript. A ideia é capturar valores digitados em um formulário, processá-los e **criar um elemento na página dinamicamente** para mostrar o resultado.

## ✨ Funcionalidades

- Dois campos numéricos para entrada dos valores
- Botão **Somar** que calcula o resultado sem recarregar a página
- Resultado exibido em um parágrafo criado dinamicamente pelo JavaScript
- Aceita números inteiros, decimais e negativos

## 🧠 Conceitos praticados

| Conceito | Onde aparece |
|---|---|
| **Variáveis e constantes** | `const n1`, `const n2` e `const soma` |
| **Operadores aritméticos** | Soma com `+` |
| **Eventos** | `addEventListener('submit')` com `preventDefault()` |
| **Conversão de tipos** | `Number()` converte o texto dos campos em número |
| **Seleção de elementos** | `getElementById` |
| **Criação dinâmica de elementos** | `createElement('p')` e `appendChild` |
| **Manipulação de texto** | `textContent` para exibir o resultado |

## 🗂️ Estrutura do projeto

```
CalculadoraSoma-Piaget/
├── index.html    # Estrutura da página (formulário)
├── styles.css    # Estilos
├── main.js       # Lógica da soma
├── LICENSE
└── README.md
```

## 🛠️ Tecnologias

- **HTML5**
- **CSS3**
- **JavaScript** (puro, sem bibliotecas)
- **Google Fonts** (Roboto)

## ▶️ Como executar

Não é necessário instalar nada. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
# 1. Clone o repositório
git clone https://github.com/ThomazLaizo/CalculadoraSoma-Piaget.git

# 2. Entre na pasta do projeto
cd CalculadoraSoma-Piaget

# 3. Abra o index.html no navegador (ou use a extensão Live Server do VS Code)
```

> ⚠️ É preciso ter conexão com a internet para carregar a fonte Roboto, importada do Google Fonts.

## 🖥️ Como usar

1. Digite um número no campo **Número 1**.
2. Digite outro número no campo **Número 2**.
3. Clique em **Somar**.
4. O resultado aparece abaixo do formulário.

**Exemplo:** `7` + `5` exibe `O Resultado da soma é: 12`.

## 🛣️ Roadmap

- [ ] Validar campos vazios (hoje um campo vazio é tratado como `0`)
- [ ] Adicionar as demais operações: subtração, multiplicação e divisão
- [ ] Tornar o layout responsivo (os espaçamentos atuais são fixos)
- [ ] Remover a `div` de resultado do HTML, que não é usada
- [ ] Testes automatizados

## 📄 Licença

Distribuído sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

Feito por **[Thomaz Silva Laizo](https://github.com/ThomazLaizo)**.