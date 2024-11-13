# Desafio: Sucessor Par

### 📝 Descrição
Dado um número inteiro \( X \), o objetivo é encontrar o menor número **par** que seja **maior** do que \( X \). O desafio é simples, mas serve como uma preparação para problemas mais complexos.

---

### 📥 Entrada
A entrada contém um único número inteiro \( X \):
```
0 < X < 10^7
```

---

### 📤 Saída
A saída deve conter o menor número par que seja maior do que \( X \).

---

### 💡 Exemplos de Entrada e Saída

#### Exemplo 1
**Entrada:**
```
1
```
**Saída:**
```
2
```

#### Exemplo 2
**Entrada:**
```
8
```
**Saída:**
```
10
```

---

### 🚀 Explicação da Solução
Para encontrar o menor número par maior que \( X \):
1. Se \( X \) já for um número par, o próximo número par será \( X + 2 \).
2. Se \( X \) for ímpar, o próximo número par será \( X + 1 \).

---

### 🛠️ Implementação em Python

```python
# Leitura do valor de X
X = int(input())

# Verifica se X é par ou ímpar e calcula o sucessor par
if X % 2 == 0:
    print(X + 2)
else:
    print(X + 1)
```

---

### 🏅 Explicação do Código
- A função `input()` lê o valor de \( X \).
- O operador `%` (módulo) é usado para verificar se \( X \) é par.
- Se \( X \% 2 == 0 \), então \( X \) é par, e o próximo par é \( X + 2 \).
- Se \( X \% 2 != 0 \), então \( X \) é ímpar, e o próximo par é \( X + 1 \).

---

### 🏷️ Tags
- Matemática
- Condicionais
- Lógica Simples

---

### 🏆 Complexidade
A complexidade da solução é **O(1)**, pois envolve apenas uma verificação e uma operação de adição, tornando-a extremamente eficiente.

---

### 📂 Licença
Distribuído sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.
