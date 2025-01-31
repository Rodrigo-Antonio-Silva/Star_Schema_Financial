# Modelagem e Transformação de Dados com a linguagem M no Power BI

---

 ## 📚 Estrutura do Modelo Dimensional (Star Schema)

### ✨ **Tabela Fato (f_vendas)**
Contém os principais eventos das transformações de vendas.

- Date - Data da venda
- Units Sold - quantidade vendida
- Sale Price - preço unitário do produto na venda
- Gross Sale - total da venda
- Discounts - valor do desconto aplicado
- Sales - valor da venda descontado o valor do desconto
- Profit - lucro obtido na venda
- IdProduct - identificador do prroduto
- IdSegment - identificador do segmento
- IdCountry - identificador do país
- IdDiscount - identificador da faixa de desconto

## **Tabelas Dimensão** 
Contém as variáveis que compoem a tabela f_fato

### ✨ **d_product**
- IdProduct - identificador do produto
- Product - nome do produto
- Manufacturing Price - custo unitário do produto

### ✨ **d_segment**
- IdSegment - identificador do segmento
- Segment - nome do segmento

### ✨ **d_discount**
- IdDiscount - identificador do desconto
- Discount - descrição do desconto
- Discount Band - faixa de desconto

### ✨ **d_country**
- IdCountry - identificador do país
- Country - nome do país

### ✨ **d_calendar**
- Date - lista de datas contínuas
- Year - ano
- Month - número do mês
- MonthYear - mês ano
- Quarter - núemro do trimestre
- QuarterYear - trimestre ano
- OrderMonthYear - para ordenação correta no visual
- OrderQuarterYear - para ordenação correta no visual

---

🤝  **Desenvolvido por Rodrigo**🚀


 
