# Projeto TypeScript: Funções de Multiplicação e Saudação

Este projeto contém duas funções simples escritas em TypeScript.

## Funções

### Função de Multiplicação

A função `multiplicar` recebe dois números como argumentos e retorna a multiplicação deles.

```typescript
function multiplicar(num1: number, num2: number): number {
    return num1 * num2;
}
```

### Função de Saudação

A função `saudacao` recebe um nome como argumento e retorna uma saudação personalizada.

```typescript
function saudacao(nome: string): string {
    return "Olá " + nome;
}
```

## Uso

Para usar essas funções, você pode chamar elas diretamente no seu código. Aqui está um exemplo de como você pode fazer isso:

```typescript
console.log(multiplicar(2, 5));  // Output: 10
console.log(saudacao("Sanderson"));  // Output: Olá Sanderson
```

Espero que você ache este projeto útil! 😊
