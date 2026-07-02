## Exercício 4: Função de Exemplo
 
!!! example "Enunciado"
    Crie um exemplo de código que ilustre uma função simples e inclua-o em uma explicação sobre como essa função pode ser utilizada.
 
```javascript title="media.js"
function calcularMedia(notas) {
  const soma = notas.reduce((total, nota) => total + nota, 0);
  return soma / notas.length;
}
```
 
!!! note "Como usar"
    A função `calcularMedia` recebe um array de números (notas) e retorna a média aritmética. Por exemplo, `calcularMedia([7, 8, 9])` retorna `8`. Ela é útil em sistemas acadêmicos para calcular a média final de um aluno a partir de suas notas.
 
---