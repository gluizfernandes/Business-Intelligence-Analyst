## FÓRMULAS DAX UTILIZADAS ## 
### 1. CRIAÇÃO DA TABELA DCALENDARIO ###
```sql
Equipe Dedicada = 
CALCULATE(
    COUNTROWS(dListaFuncionarios), dListaFuncionarios[Gerência]="OPARM", dListaFuncionarios[Departamento]="Inventário") + 
CALCULATE(
    COUNTROWS(dListaFuncionarios), dListaFuncionarios[Gerência]="OPARM", dListaFuncionarios[Departamento]="Estocagem /Chave Externa") +
CALCULATE(
    COUNTROWS(dListaFuncionarios), dListaFuncionarios[Gerência]="OPARM", dListaFuncionarios[Departamento]="Gestão Equipamentos (5S)")
```
