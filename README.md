# 📄 Memorial de Cálculo – Viga Biapoiada com Cargas Concentradas

## 1. Dados da Viga

- **Tipo de estrutura:** Viga de madeira biapoiada (apoios A e D)
- **Comprimento total da viga:**

  \[
  L = 0{,}8 + 0{,}8 + 0{,}8 = 2{,}4 \, \text{m}
  \]

- **Cargas aplicadas:**
  - \( P_1 = 1{,}8 \, \text{kN} = 1800 \, \text{N} \) no ponto **B**, a 0,8 m do apoio **A**
  - \( P_2 = 3{,}6 \, \text{kN} = 3600 \, \text{N} \) no ponto **C**, a 1,6 m do apoio **A**

---

## 2. Cálculo das Reações nos Apoios

### Equilíbrio de momentos no apoio A:

\[
\sum M_A = 0 \Rightarrow R_D \cdot 2{,}4 - 1800 \cdot 0{,}8 - 3600 \cdot 1{,}6 = 0
\]

\[
R_D = \frac{(1800 \cdot 0{,}8) + (3600 \cdot 1{,}6)}{2{,}4} = \frac{1440 + 5760}{2{,}4} = \frac{7200}{2{,}4} = 3000 \, \text{N}
\]

### Equilíbrio das forças verticais:

\[
\sum F_y = 0 \Rightarrow R_A + R_D = 1800 + 3600 = 5400 \, \text{N}
\]

\[
R_A = 5400 - 3000 = 2400 \, \text{N}
\]

### ✅ Reações finais:

- \( R_A = 2400 \, \text{N} \)
- \( R_D = 3000 \, \text{N} \)

---

## 3. Diagrama de Esforço Cortante (V)

O esforço cortante varia em três trechos ao longo da viga:

- **Trecho 1** (0 ≤ x < 0,8 m):

  \[
  V(x) = R_A = 2400 \, \text{N}
  \]

- **Trecho 2** (0,8 ≤ x < 1,6 m):

  \[
  V(x) = R_A - P_1 = 2400 - 1800 = 600 \, \text{N}
  \]

- **Trecho 3** (1,6 ≤ x ≤ 2,4 m):

  \[
  V(x) = R_A - P_1 - P_2 = 2400 - 1800 - 3600 = -3000 \, \text{N}
  \]

---

## 4. Diagrama de Momento Fletor (M)

Calculado com base na integração do esforço cortante:

- **Trecho 1** (0 ≤ x < 0,8 m):

  \[
  M(x) = R_A \cdot x = 2400 \cdot x
  \]

- **Trecho 2** (0,8 ≤ x < 1,6 m):

  \[
  M(x) = R_A \cdot x - P_1 \cdot (x - 0{,}8)
  \]

- **Trecho 3** (1,6 ≤ x ≤ 2,4 m):

  \[
  M(x) = R_A \cdot x - P_1 \cdot (x - 0{,}8) - P_2 \cdot (x - 1{,}6)
  \]

---

## 5. Momento Fletor Máximo

O momento máximo ocorre entre os pontos B e C:

\[
M_{máx} = M(1{,}6^-) = 2400 \cdot 1{,}6 - 1800 \cdot (1{,}6 - 0{,}8)
\]

\[
M_{máx} = 3840 - 1440 = 2400 \, \text{N·m}
\]

---

## ✅ Conclusão

A análise da viga mostra que, sob as cargas aplicadas de 1,8 kN e 3,6 kN, a estrutura gera reações de **2400 N** e **3000 N** nos apoios **A** e **D**, respectivamente. O momento fletor máximo ocorre entre os pontos de carga, com valor de **2400 N·m**. Os diagramas de esforço cortante e momento fletor demonstram graficamente os esforços internos atuando ao longo da viga e foram construídos com base nos princípios de equilíbrio estático.

---

> Desenvolvido por [Seu Nome], para fins acadêmicos.  
> Engenharia Estrutural – Análise de Vigas

