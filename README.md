<p align="center"><img src="docs/assets/banner.svg" alt="Calculadora de Cédulas — Um exercício de decomposição de valores em JavaScript" width="100%" /></p>

<p align="center"><strong>HTML · CSS · JavaScript · Lógica de programação</strong></p>
<p align="center"><a href="#sobre">Sobre</a> · <a href="#como-executar">Como executar</a> · <a href="https://github.com/Dudulonabr">Perfil do autor</a></p>

# Calculadora de Cédulas

## Sobre

Exercício em **HTML, CSS e JavaScript** que decompõe um valor informado em unidades de 100, 50, 20, 10, 5, 2 e 1. O resultado é exibido no navegador após a entrada por `prompt`.

## Como funciona

O algoritmo percorre os valores em ordem decrescente, calcula a quantidade com `Math.floor()` e atualiza o restante com o operador `%`.

**Exemplo:** para 186, a saída contém uma unidade de 100, uma de 50, uma de 20, uma de 10, uma de 5 e uma de 1.

O exercício inclui a unidade de 1 como parte do algoritmo didático. A aplicação não realiza operações bancárias.

## Como executar

```bash
git clone https://github.com/Dudulonabr/Caixa-eletronico.git
```

Abra `index.html` no navegador, clique em **Calcular Valor** e informe um número inteiro positivo. O arquivo `estilo.css` contém os estilos da página.

## Conceitos praticados

Entrada e conversão de dados, validação com `isNaN`, arrays, laço `for`, divisão inteira, resto e atualização do DOM.

## Limitações atuais

A entrada utiliza `parseInt()`: valores com casas decimais são truncados. A versão atual serve como estudo de decomposição de inteiros; uma evolução seria validar toda a entrada e trabalhar explicitamente com centavos.

## Autor

**Eduardo Moreira Monteiro Lona** · São Paulo, Brasil

Estudante de **Análise e Desenvolvimento de Sistemas (UNIP)** e **Engenharia de Software (Cruzeiro do Sul)**, com formação técnica em **Informática pelo SENAC**.

[LinkedIn](https://www.linkedin.com/in/eduardo-moreira-monteiro-lona) · [E-mail](mailto:dudulona07@gmail.com) · [GitHub](https://github.com/Dudulonabr)
