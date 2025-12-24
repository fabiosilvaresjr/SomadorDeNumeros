# ➕ Somador de Valores (DOM)

> Projeto focado na interação entre elementos de formulário HTML e lógica matemática com JavaScript.

Esta aplicação captura valores inseridos pelo usuário em caixas de texto (`input`), realiza a conversão de tipos (String para Number) e exibe o resultado da soma dinamicamente na página, sem necessidade de recarregamento.

## 🚀 Tecnologias Utilizadas

- **HTML5** (Estrutura e Inputs)
- **CSS3** (Estilização de caixas e centralização)
- **JavaScript** (Manipulação do DOM e Coerção de Tipos)

## ⚙️ Funcionalidades

- [x] **Captura de Valores:** Uso de `getElementById().value` para ler o que o usuário digitou.
- [x] **Conversão de Tipos:** Utilização de `Number()` para garantir que a operação seja uma soma matemática e não uma concatenação de texto.
- [x] **Validação de Inputs:** Lógica condicional para verificar se os campos estão vazios ou inválidos (`NaN`) antes de calcular.
- [x] **Atualização do DOM:** Uso de `innerHTML` para injetar o resultado na `div` específica.

## 🧠 Aprendizados e Destaques do Código

1. **Manipulação do DOM:** Aprendi a "pegar" valores do HTML, processar no JS e "devolver" para o HTML usando `innerHTML`.
2. **Tratamento de Erros:** Implementei uma verificação para garantir que o usuário inseriu números válidos.
3. **Estilização Dinâmica:** A estrutura separa visualmente a área de entrada (azul) da área de resultado (verde), melhorando a experiência do usuário (UX).

## 📦 Como rodar o projeto

1. Clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Digite dois números e clique em "Somar".

---
Desenvolvido por **Fabio** durante estudos de DOM e JavaScript.
