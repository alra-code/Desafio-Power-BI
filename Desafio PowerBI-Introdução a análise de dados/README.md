
# Dashboard Acompanhamento de vendas - EmpowerData

## Roteiro da Atividade

- Este relatório teve como objetivo principal, realizar a análise exploratória dos dados e em seguida criar a Visualização do dados facilitando a tomada de decisão.  

## Indicadores

- Faturamento;
- Total de Pedidos;
- Ticket Médio;
- Faturamento por período; 
- Detalhamento de Faturamento por loja;
- Geolocalização das loja.


## Medidas
O dashboard ACOMPANHAMENTO DE VENDAS contém as seguintes medidas.

### Faturamento
```javascript
Faturamento = SUM(pedidos[valor_venda])
```
 
### Qtde de Pedidos
```javascript
Qtde_pedidos = COUNTROWS(pedidos)
```

### Ticket Médio 
```javascript
Ticket_medio = DIVIDE([Faturamento],[Qtde_pedidos],"N/A")
```

## Ferramentas

- Power BI

## Compartilhamento

Para acessar o dashboard, basta abrir o arquivo no power BI Desktop.
 

## Uso

O uso do dashboard é intuitivo e fácil de entender. Cada visualização é interativa e permite filtrar dados e visualizar informações de diferentes maneiras. Basta selecionar a visualização desejada e começar a explorar os dados.

## Visualização do Dashboard

![Acompanhamento de Vendas Desktop](https://github.com/user-attachments/assets/aa949e03-94d5-43a5-83c3-688f8fa633d6)

<div align="center">

  <img src="https://github.com/user-attachments/assets/aa156231-bf34-41ed-a0a7-7272202cb5dc" alt="Acompanhamento de vendas Mobile">
  
</div>

