# 📄 Memorial de Cálculo – Viga Biapoiada com Cargas Concentradas

## 1. Dados da Viga

- **Tipo de estrutura:** Viga de madeira biapoiada (apoios A e D)
- **Comprimento total da viga:**
  - L = 0,8 + 0,8 + 0,8 = **2,4 m**
- **Cargas aplicadas:**
  - P₁ = **1,8 kN** = 1800 N no ponto **B**, a 0,8 m do apoio **A**
  - P₂ = **3,6 kN** = 3600 N no ponto **C**, a 1,6 m do apoio **A**

---

## 2. Cálculo das Reações nos Apoios

### Equilíbrio de momentos no apoio A:

R_D × 2,4 − 1800 × 0,8 − 3600 × 1,6 = 0

R_D = (1800 × 0,8 + 3600 × 1,6) / 2,4  
R_D = (1440 + 5760) / 2,4 = 7200 / 2,4 = **3000 N**

### Equilíbrio das forças verticais:

R_A + R_D = 1800 + 3600 = **5400 N**

R_A = 5400 − 3000 = **2400 N**

### ✅ Reações finais:

- R_A = **2400 N**
- R_D = **3000 N**

---

## 3. Diagrama de Esforço Cortante (V)

Dividimos a viga em três trechos:

- **Trecho 1 (0 ≤ x < 0,8 m):**  
  V(x) = R_A = **2400 N**

- **Trecho 2 (0,8 ≤ x < 1,6 m):**  
  V(x) = R_A − P₁ = 2400 − 1800 = **600 N**

- **Trecho 3 (1,6 ≤ x ≤ 2,4 m):**  
  V(x) = R_A − P₁ − P₂ = 2400 − 1800 − 3600 = **−3000 N**

---

## 4. Diagrama de Momento Fletor (M)

Equações por trecho:

- **Trecho 1 (0 ≤ x < 0,8 m):**  
  M(x) = 2400 × x

- **Trecho 2 (0,8 ≤ x < 1,6 m):**  
  M(x) = 2400 × x − 1800 × (x − 0,8)

- **Trecho 3 (1,6 ≤ x ≤ 2,4 m):**  
  M(x) = 2400 × x − 1800 × (x − 0,8) − 3600 × (x − 1,6)

---

## 5. Momento Fletor Máximo

O momento máximo ocorre entre os pontos B e C:

M(1,6) = 2400 × 1,6 − 1800 × (1,6 − 0,8)  
M(1,6) = 3840 − 1440 = **2400 N·m**

---

## ✅ Conclusão

A análise mostra que, com as cargas aplicadas de 1,8 kN e 3,6 kN, a estrutura desenvolve reações de **2400 N** e **3000 N** nos apoios A e D, respectivamente.  
O momento fletor máximo de **2400 N·m** ocorre entre os pontos de carga.  
Os diagramas de esforço cortante e momento fletor ajudam a visualizar os esforços internos atuantes na viga.

---

