# Descrição formal

- Q são os estados = {q0,q1} 
- Σ é o alfabeto aceito = {0,1}
- δ é Função de transição você pode escrever como conjunto de pares (formal) ou como tabela
- q0 é o estado inicial = q0
- F são os estados aceitos = {q1}

# ✅ EXEMPLO


```
AUTOMATO = (Q, Σ, δ, q0, F)

Q = {q1, q2, q3}
Σ = {a, b}
q0 = q1
F = {q3}

δ(q1, a) = q2
δ(q1, b) = q1
δ(q2, a) = q2
δ(q2, b) = q3
δ(q3, a) = q2
δ(q3, b) = q1
```

---

## δ como tabela se preferir

| δ  | a  | b  |
| -- | -- | -- |
| q1 | q2 | q1 |
| q2 | q2 | q3 |
| q3 | q2 | q1 |
