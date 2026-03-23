<div align="center">

# 👥 Fiscais de Caixa Remoto
## Procedimentos e Funções - Guia Completo

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

**[⌨️ Atalhos](#️-atalhos-do-teclado)** | **[🛒 Funções](#-funções-do-sistema)** | **[💳 POS](#-procedimento-pos)** | **[📝 Procedimentos](#-o-que-fazer)** | **[🚨 Erros Comuns](#-erros-comuns)**

**[⬅️ Voltar ao Índice](README.md)**

</div>

---

<br>

<div align="center">

## ⌨️ Atalhos do Teclado

</div>


### 🔹 Navegação Básica


| Tecla | Função | Descrição |
|:-----:|--------|-----------|
| **`F4`** | **Estorno** | Realiza estorno de operação |
| **`F`** | **Esc (voltar)** | Retorna ao menu anterior |
| **`U`** | **Função** | Acessa menu de funções |
| **`T`** | **Total** | Finaliza e totaliza cupom |
| **`C`** | **Consulta Preço** | Consulta preço de produto |


### 🔹 Operações de Cupom


| Tecla | Função | Descrição |
|:-----:|--------|-----------|
| **`X`** | **Reimprimir Cupom** | Reimprime último cupom fiscal |
| **`G`** | **Gaveta** | Abre gaveta do caixa |
| **`P`** | **Pagamento** | Inicia processo de pagamento |
| **`O`** | **Pagamento (cartão)** | Pagamento via cartão |
| **`R`** | **Sangria** | Realiza sangria do caixa |


### 🔹 Operações Especiais


| Tecla | Função | Descrição |
|:-----:|--------|-----------|
| **`ALT`** | **CPF no cupom** | Adiciona CPF no cupom fiscal |
| **`D`** | **Devolução Vale** | Processa devolução de vale |
| **`S`** | **Cancelamento de TEF** | Cancela transação TEF |
| **`Z`** | **Cancelamento Cupom** | Cancela cupom em andamento |
| **`V`** | **Encerramento de Turno** | Encerra turno do operador |

<br>

---

<div align="center">

## 🛒 Funções do Sistema

</div>

### 🟢 Compra em Andamento


| Código | Descrição | Aplicação |
|:------:|-----------|-----------|
| **Função 02** | Abrir Gaveta | Abre gaveta sem venda |
| **Função 11** | Cancelamento de Cupom | Cancela cupom atual |
| **Função 12** | Estorno de Item | Remove item do cupom |
| **Função 13** | Cancelamento de TEF | Cancela transação TEF |
| **Função 19** | Consultar Preço | Verifica preço sem adicionar |
| **Função 29** | Divergência de Preço | Registra divergência |

<br>


### 🔵 Menu Principal


| Código | Descrição | Aplicação |
|:------:|-----------|-----------|
| **Função 11** | Cancelamento de ValeCredito | Cancela vale crédito |
| **Função 34** | Corresponde Bancário | Pagamento de fatura |
| **Função 42** | Devolução de Produto | Processa devolução |
| **Função 43** | Devolução de Preço | Ajuste de preço |
| **Função 44** | Devolução de ValeCredito | Estorna vale crédito |
| **Função 81** | Recarga de Celular | Recarga telefônica |
| **Função 88** | Reimpressão de Comprovante | Reimprime comprovante |
| **Função 89** | Reimpressão de Documento | Reimprime documento |
| **Função 99** | Saída Temporária | Saída temporária do sistema |

<br>


### 🟡 Pagamento


| Código | Descrição | Aplicação |
|:------:|-----------|-----------|
| **Função 17** | Estorno de pagamento | Cancela pagamento realizado |

<br>


### 🔴 Devolução


| Código | Descrição | Aplicação |
|:------:|-----------|-----------|
| **Função 05** | Cancelamento de ValeCredito | Cancela vale crédito |
| **Função 17** | Imprimir Devolução | Imprime comprovante |
| **Função 28** | Reimprimir Devolução | Reimprime devolução |

<br>

---

<div align="center">

## 💳 Procedimento POS

</div>


### 📊 Informações da Transação


| Campo | Formato | Exemplo |
|-------|---------|---------|
| **BIN** | Bandeira e final do cartão | `MASTER / VISA: ****1234` |
| **NSU** | Número Sequencial Único | `DOC: 000123` |
| **Código de Autorização** | Código da transação | `AUT: 123456` |

> **💡 Dica:** Sempre anote esses dados em caso de necessidade de estorno ou contestação.

<br>

---

<div align="center">

## 📝 O que fazer?

</div>

### 🔄 Estorno de TEF

**Passo a passo:**

1. **Função 13** → Acesse a função de estorno de TEF
2. **Selecione o tipo de TEF** → Escolha entre Cartão ou Pix
3. **Insira o Valor da Transação** → Ex: `R$ 178,90`
4. **Insira a Data** → Ex: `01/02/2026`
5. **Insira o CV/NSU** → Ex: `000123456`

> 💡 **Importante:** Tenha em mãos o comprovante da transação original para localizar o NSU.

<br>

### 📦 Devolução de Produto

**Passo a passo:**

1. **Função 42** → Acesse devolução de produto
2. **Bipa o produto** → Escaneie o código de barras
3. **Insira os dados da nota fiscal**, Data, DOC/COO & Série
   `EX: Data 01/02/2026 | DOC: 01234 | Série: 216008`
> 💡 **Dica:** A série sempre será numero da loja seguido do numero do caixa.
5. **Selecione o tipo de devolução:**
   - Arrependimento
   - Defeito
   - Impróprio
   - Insatisfação
6. **Função 17** → Confirma e imprime a devolução

> 💡 **Importante:** Sempre verifique a nota fiscal original antes de processar a devolução.

<br>

### 💰 Desconto sobre Desconto

**Cálculo e procedimento:**

1. **Função 29** → Acesse divergência de preço
2. **Calcule o novo valor:**
   - Preço da etiqueta/cartaz **×** Quantidade
   - **+** Valor do desconto já aplicado no produto
   - **÷** Quantidade

**Exemplo VNC:**
```
7894900011159	      x	      COCA COLA TRAD LT 310ML
3,000UN x 	                  3,99	    |	    8,34
Desconto no item 1 	          30,3%		       -3,63
```

**Exemplo prático:**
```
3 Cocas de R$ 3,99 (já está R$ 2,78, no cartaz está R$ 2,59)

Cálculo:
(2,59 × 3) + 3,63 ÷ 3 = Novo preço unitário
```

> ⚠️ **Atenção:** Sempre confira o cartaz/etiqueta antes de aplicar o desconto adicional.

<br>

---

<div align="center">

## 🚨 Erros Comuns

</div>

---

### ⚖️ Erro na Pesagem

> ⚠️ **Descrição do problema:** O sistema contabilizava 1kg independente da quantidade real pesada pelo cliente (ex: 200g ou 4kg).

**Cálculo e procedimento:**

#### 📉 Peso menor que 1kg

1. **Verifique o peso na balança** → Ex: `0,234 kg`
2. **Calcule:** Peso × Preço/kg → Ex: `0,234 × R$ 8,99 = R$ 2,10`
3. **Faça a divergência** usando a **Função 29**

**Exemplo:**
```
Peso na balança: 0,234 kg
Cálculo: 0,234 × 8,99 = R$ 2,10
```

<br>

#### 📈 Peso maior que 1kg

1. **Verifique o peso na balança** → Ex: `2,855 kg`
2. **Fracione em partes inteiras + resto:**
   - `2,855 kg` → separa em `2 kg` inteiros + `0,855 kg` restante
3. **Calcule o restante:** Peso × Preço/kg → Ex: `0,855 × R$ 8,99 = R$ 7,68`
4. **Registre 1 kg** no sistema
5. **Aplique desconto no 1º item** para ajustar ao valor calculado
6. **Registre o restante inteiro** → Ex: `2 kg`

**Exemplo:**
```
Peso na balança: 2,855 kg
Fracionamento: 2,855 → 2kg inteiros + 0,855kg restante
Cálculo: 0,855 × 8,99 = R$ 7,68

Passo a passo no sistema:
  1. Registra 1kg com desconto → R$ 7,68
  2. Registra 2kg → valor normal
```

> 💡 **Dica:** Sempre confira o peso exibido na balança antes de registrar e, se necessário, chame o supervisor para validar.

<br>

---

### 🏷️ Erro no Cartaz

> ⚠️ **Descrição do problema:** O cartazista especificou o preço por unidade em vez de por quilograma (ex: *Costelinha R$ 18,99 und*), fazendo o cliente acreditar que o preço é por peça e não por kg.

**Cálculo e procedimento:**

1. **Pegue o preço do cartaz e divida pelo peso** do produto
2. **Multiplique o resultado pelo peso novamente** — se chegar ao mesmo valor do cartaz, o cálculo está correto
3. **Use o primeiro resultado na Função 29** para registrar o preço correto por kg

**Exemplo prático:**
```
CUPIM BOVINO 1,522 KG × R$ 39,99 = R$ 60,86

Passo 1 — Preço por kg:
39,99 ÷ 1,522 = 26,2746... → (26,28)

Passo 2 — Validação:
26,28 × 1,522 = 39,998... → (≈ 39,99) ✔

Passo 3 — Registrar na Função 29: R$ 26,28/kg
```

> 💡 **Dica:** O arredondamento de centavos é normal. Se o resultado da validação ficar próximo ao valor do cartaz (diferença de centavos), o cálculo está correto.

<br>

---

### 🔌 Erro de Conexão — Vale Crédito

> ⚠️ **Descrição do problema:** Ao Validar / Devolver / Cancelar o vale crédito, o sistema retorna **"Sem conexão com servidor remoto"**.

**Passo a passo:**

1. **Chame um Fiscal ou Encarregado**
2. **Libere o valor do vale em dinheiro** ao cliente
3. **Peça para o operador retornar em algumas horas**
4. Quando o sistema voltar, utilize a **Função 44** para abater o valor do vale no caixa
5. **Caso o sistema ainda esteja com erro:**
   - Peça ao Fiscal/Encarregado para enviar uma **nota para a tesoureira** junto com o vale crédito no malote
   - A tesoureira irá validar no seu expediente para **evitar quebra indesejada**

> 💡 **Resumo do fluxo:**

```
Erro "Sem conexão com servidor remoto"
              ↓
  Chamar Fiscal / Encarregado
              ↓
  Liberar valor em dinheiro ao cliente
              ↓
        Sistema voltou?
       ↙             ↘
     SIM              NÃO
      ↓                ↓
 Função 44      Nota + Vale no malote
 Abater vale    Tesoureira resolve no
  no caixa          expediente
```

<br>

---

<div align="center">

### 📌 Informações do Documento

**Última atualização:** `Março de 2026`  
**Versão:** `1.3`  
**Responsável:** `[Jessica Ferreira]`

---

**BigUltra** | Fiscais de Caixa Remoto  
_Documento de uso interno_

**[⬅️ Voltar ao Índice](README.md)** | **[🛡️ Ver Prevenção de Perdas](PREVENCAO.md)**

</div>
