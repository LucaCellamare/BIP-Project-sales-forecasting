# BIP-Project-sales-forecasting
0. train e validation. Sia per train set che per test set  ho usato  con scope=0, TRAIN: inizio dati fino a 12/2018. VALIDATION: 12/2018 fino alla fine
1.salesW-1 è molto significativo, anche salesW-2
2.price è significativo
3.con la regressione Rollign Windows di 1 e 5 sono significative
4. prodotti correlati nel train set sono molto significativi, ma solo pochi sono correlati. (Con regressione considero prod con corrPearson>0.6, mi ha dato perfprmance migliore)
