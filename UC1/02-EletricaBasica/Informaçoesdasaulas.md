# 🔋 Pilhas, Baterias e Fontes de Computador

## 🔹 Pilhas e Baterias
- **Pilha**: Sempre **1,5 V** ⚡  
- **Bateria**: Qualquer coisa **acima de 1,5 V** é considerada **bateria** 🔋

## 🖥️ Fonte de Computador (ATX)
- **Amarelo → 12 V** 🟡  
- **Vermelho → 5 V** 🔴  
- **Laranja → 3,3 V** 🟠  

## 📝 Observação
Fontes de **alto desempenho** geralmente utilizam **apenas cabos pretos e brancos** ⚫⚪ para organização e estética.

# 🧑‍🏫 Aulas — 05/09/2025

## ⚡ Tensões de Tomada
- **AC / CA** = Corrente Alternada  
- **Padrões**: 127 V / 220 V  
- **Hz (frequência)** = ciclos por segundo da corrente alternada  
- **Pico de tensão**: queima as peças instantaneamente  
- **Queda de tensão**: desgasta as peças aos poucos  

---

## 🔋 Tensões DC (CC)
- **DC / CC** = Corrente Contínua  
- Tensões comuns: **3,3 V / 5 V / 12 V**

---

## 🧮 Cálculos

### Primeira Lei de Ohm
\[
U = R \cdot I
\]
- **U** = Tensão (V = volts)  
- **R** = Resistência (Ω = ohms) — *componente mais importante*  
- **I** = Corrente (A = ampère)  

**Triângulo da Lei de Ohm**  
- Vertical = divisão (de cima para baixo)  
- Horizontal = multiplicação  

> ⚠️ **A corrente nunca será maior que a tensão.**  
> Se for maior ou igual, ocorre curto-circuito.

---

### Potência Elétrica
- **P** = Potência (W = watts)

Relação básica:
\[
P = U \cdot I
\]

---

## 🖥️ Informações sobre Fontes de Computador
- **PSU** = *Power Supply Unit* → Fonte de alimentação  
- **PFC** = *Power Factor Correction* → Correção do fator de potência  
- **80 Plus** = Certificação de eficiência da fonte  
- **Full Range** = Aceita 127 V / 220 V automaticamente  
- **Limite de corrente (exemplo)**: O computador aguenta no máximo **10 A**  

---

## 💡 Cálculo do Resistor para LED
- Todo LED tem uma corrente característica.  
- Corrente padrão: **0,02 A (20 mA)**  
- LED branco: **3 V**

**Fórmula:**
\[
R_{LED} = \frac{V_{\text{fonte}} - V_{\text{LED}}}{I_{\text{LED}}}
\]

**Exemplo:**  
- \( V_{\text{fonte}} = 5\,\text{V} \)  
- \( V_{\text{LED}} = 3\,\text{V} \)  
- \( I_{\text{LED}} = 0{,}02\,\text{A} \)  

\[
R_{LED} = \frac{5 - 3}{0{,}02} = 100\,\Omega
\]

Use um resistor de **100 Ω** (ou valor comercial próximo).

---

## 📌 Resumo
- AC/CA: 127/220 V — Hz = frequência  
- DC/CC: 3,3 V • 5 V • 12 V  
- Lei de Ohm: \( U = R \cdot I \)  
- Potência: \( P = U \cdot I \)  
- Fonte: PSU • PFC • 80 Plus • Full Range  
- LED: \( R = \frac{V_{\text{fonte}} - V_{\text{LED}}}{I_{\text{LED}}} \)

 
