<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Calculadora Simples em JavaScript</title>
</head>
<body>
  <h1>🧮 Calculadora Simples em JavaScript</h1>
  <p>Abra o console do navegador (F12 → Aba "Console") para ver os resultados.</p>

  <script>
    // Solicita entrada de dados
    let num1 = Number(prompt("Digite o primeiro número:"));
    let num2 = Number(prompt("Digite o segundo número:"));

    // Operações aritméticas básicas
    let soma = num1 + num2;
    let subtracao = num1 - num2;
    let multiplicacao = num1 * num2;
    let divisao = num1 / num2;
    let resto = num1 % num2;

    // Exibe os resultados no console
    console.log("📌 Resultados das operações:");
    console.log(`Soma: ${num1} + ${num2} = ${soma}`);
    console.log(`Subtração: ${num1} - ${num2} = ${subtracao}`);
    console.log(`Multiplicação: ${num1} * ${num2} = ${multiplicacao}`);
    console.log(`Divisão: ${num1} / ${num2} = ${divisao}`);
    console.log(`Resto: ${num1} % ${num2} = ${resto}`);

    // Utilizando operadores de atribuição
    let resultado = soma; // começa com a soma
    console.log(`\n🔄 Operadores de atribuição:`);
    console.log(`Valor inicial (soma): ${resultado}`);

    resultado += subtracao; // resultado = resultado + subtracao
    console.log(`Após += subtração: ${resultado}`);

    resultado -= multiplicacao; // resultado = resultado - multiplicacao
    console.log(`Após -= multiplicação: ${resultado}`);

    resultado *= divisao; // resultado = resultado * divisao
    console.log(`Após *= divisão: ${resultado}`);

    resultado %= resto; // resultado = resultado % resto
    console.log(`Após %= resto: ${resultado}`);
  </script>
</body>
</html>

