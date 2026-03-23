<div align="center">

# 🛡️ Prevenção de Perdas
## Guia de Erros Comuns e Como Evitá-los

</div>

<br>

---

<div align="center">

<img src="./assets/img/bigbox.PNG" alt="Logo BigBox" width="300" style="margin: 0 20px;"/>
<img src="./assets/img/ultrabox.PNG" alt="Logo Ultrabox" width="300" style="margin: 0 20px;"/>

</div>

---

<br>

<div align="center">

## 🔍 Navegação Rápida

**[🔢 Erro de Multiplicador](#-erro-de-multiplicador)** | **[🍺 Cervejas](#-cervejas)** | **[🍫 Achocolatados](#-achocolatados)** | **[🧃 Produtos com Sabores](#-produtos-com-sabores-diferentes)**

**[⬅️ Voltar ao Índice](README.md)**

</div>

---

<br>

<div align="center">

## 🔢 Erro de Multiplicador

</div>

> ⚠️ **Descrição do problema:** O erro ocorre quando o cliente está levando **X unidades**, mas o operador não presta atenção e lança outra quantidade diferente.

<br>

### 📦 Erro Geral

**Exemplo 1:**
```
✅ CORRETO: 3 und Batata Palha
❌ ERRADO:  33 und Batata Palha  ← Operador digitou a mais
```

**Exemplo 2:**
```
✅ CORRETO: 4 und Cerveja Eisenbahn
❌ ERRADO:  54 und Cerveja Eisenbahn  ← Operador digitou a mais
```

> 💡 **Consequência:** Na maioria dos casos, nem o cliente nem o operador percebem a tempo, finalizando a compra e causando prejuízo para o cliente.

<br>

---

<div align="center">

## 🍺 Cervejas

</div>

> ⚠️ **Atenção especial:** Cervejas são geralmente os **maiores erros**, pois existem muitas variantes com quantidades diferentes.

**Variações comuns:**
- Pacote com 6 unidades
- Pacote com 8 unidades
- Pacote com 12 unidades
- Pacote com 15 unidades

> 💡 **Dica:** Sempre confirme a quantidade do pacote antes de multiplicar.

**Exemplos de erro:**
```
Cliente levou:
  ✅ 2 pacotes de 12 und Heineken = 2 × 12 = 24 cervejas

Operador digitou:
  ❌ 12 und Heineken (registrou apenas 12 em vez de 2 pacotes)
```

<br>

---

<div align="center">

## 🍫 Achocolatados

</div>

> ⚠️ **Dois tipos de erro possíveis:** Existem 2 variantes principais que geram confusão.

**Variações:**
- **Italakinho:** 24 unidades por pacote
- **Quatorzinho, Chocomil, etc.:** 27 unidades por pacote

> 💡 **Dica:** Verifique sempre a embalagem para confirmar a quantidade exata.

**Exemplos de erro:**
```
Cliente levou:
  ✅ 1 pacote Italakinho = 24 und

Operador digitou:
  ❌ 1 pacote Italakinho = 27 und (confundiu com Quatorzinho)
```

<br>

---

<div align="center">

## 🧃 Produtos com Sabores Diferentes

</div>

> ⚠️ **Clássico dos erros:** Cliente leva o mesmo produto em sabores variados, mas o operador registra tudo com o mesmo sabor.

**Exemplo do erro:**
```
Cliente levou:
  5 und Suco de Uva
  5 und Suco de Limão
  5 und Suco de Maçã
  5 und Suco de Laranja
  5 und Suco de Pêssego
  5 und Suco de Morango
  ─────────────────────
  30 und TOTAL

Operador registrou:
  30 und Suco de Uva  ← ERRO! Todos como mesmo sabor
```

<br>

### 🚨 Por que isso é um problema?

Mesmo que o preço seja igual, isso gera **erro no controle de estoque**:

```
📊 No sistema:
  ✅ Suco de Uva:    -30 und (excesso de saída)
  ❌ Suco de Limão:   0 und (deveria ser -5)
  ❌ Suco de Maçã:    0 und (deveria ser -5)
  ❌ Suco de Laranja: 0 und (deveria ser -5)
  ❌ Suco de Pêssego: 0 und (deveria ser -5)
  ❌ Suco de Morango: 0 und (deveria ser -5)

Resultado:
  • Suco de Uva mostra falta no estoque
  • Outros sabores mostram excesso no estoque
  • Inventário fica incorreto
  • Reposição fica prejudicada
```

> 💡 **Dica:** Sempre bipe ou digite cada sabor separadamente, mesmo que tenha o mesmo preço.

<br>

### 📋 Outros produtos comuns com esse erro:

| Categoria | Exemplos |
|-----------|----------|
| **Sucos** | Del Valle, Ades, Sufresh, Tial |
| **Refrigerantes** | Coca-Cola, Fanta, Sprite (sabores) |
| **Iogurtes** | Danone, Nestlé, Itambé (sabores) |
| **Sorvetes** | Kibon, Nestlé (sabores) |
| **Chocolates** | Lacta, Garoto (recheios) |
| **Biscoitos** | Oreo, Club Social (sabores) |

<br>

---

<div align="center">

## 📌 Checklist de Prevenção

</div>

Antes de finalizar a compra, sempre verifique:

- [ ] A quantidade digitada corresponde ao que o cliente levou?
- [ ] Se for cerveja, conferiu quantas unidades tem no pacote?
- [ ] Se for achocolatado, qual é a variante? (24 ou 27 und)
- [ ] Produtos com sabores estão todos registrados corretamente?
- [ ] Conferiu visualmente os itens no carrinho antes de finalizar?

> ⚠️ **Lembre-se:** 90% dos erros acontecem por falta de atenção. Uma conferência rápida evita prejuízos!

<br>

---

<div align="center">

### 📌 Informações do Documento

**Última atualização:** `Março de 2026`  
**Versão:** `1.3`  
**Responsável:** `[Jessica Ferreira]`

---

**BigUltra** | Prevenção de Perdas  
_Documento de uso interno_

**[⬅️ Voltar ao Índice](README.md)** | **[👥 Ver Procedimentos Fiscais](FISCAL.md)**

</div>
