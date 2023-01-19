## texto

### EntradaCDI
#### Parâmetros de entrada
| **Parâmetros** | **Descrição** | **Tipo** |
| --- | --- | --- |
| Data operação | Trata-se da data de abertura do contrato. | LocalDate |
| Data posição | É a data limite para atualização monetária, ou seja, até quando corrigir os valores da operação. | LocalDate |
| Percentual CDI | É o percentual da taxa DI aplicado na atualização monetária da operação sem atraso.| Double |
| Percentual CDI Atraso | É o percentual da taxa DI aplicado na atualização monetária da operação em atraso.| Double |
| Parcelas Entrada | Lista com o cronograma de parcelas. | List<ParcelaEntrada> |

### Parcelas Entrada
| **Parâmetros** | **Tipo** |
| --- | --- |
| Número da parcela | int |
| Data de vencimento | LocalDate

### Enum Situação da parcela
| **Parâmetros** | **Descrição** |
| --- | --- |
| VINCENDA | A parcela vincenda não foi paga, mas ainda não venceu. |
| EM_ATRASO | A parcela em atraso não foi paga, mas já venceu. |
| LIQUIDADA | A parcela liquidada já foi paga: antecipadamente, no vencimento ou posteriormente. |



## texto
