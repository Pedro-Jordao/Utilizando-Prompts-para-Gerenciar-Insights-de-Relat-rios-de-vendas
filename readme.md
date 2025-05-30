Características
A empresa foca apenas em fabricação de consoles, deixando a distribuição e venda para terceiros.

Os produtos são vendidos globalmente.

Objetivos
 Consolidar todas as bases de terceiros para realizar uma análise.

 Transformar dados de vendas em informações relevantes para a fabricante.

 Identificar quais são os produtos mais populares em cada país.

 Otimizar o processo de transporte e logística até o momento da venda.

 Abaixo os resultados adquiridos:
Após as configurações do ambiente local (Visual Studio Code) e as análises realizadas, o primeiro passo foi criar o modelo gpt no chatgpt versão paga seguindo as configurações iniciais a seguir (as configurações podem ter mudado durante o desenvolver do laboratório):
![Criando o modelo gpt](https://github.com/user-attachments/assets/13790756-76d9-463a-adbe-260097e66ab0)

O segundo passo foi definir quais recursos estariam disponíveis para ele inicialmente:
![Recursos ativos para o modelo](https://github.com/user-attachments/assets/77bbd427-17a1-427e-91ab-2fd30353904b)

Então foram realizados os seguintes testes:
![Teste produto mais vendido01](https://github.com/user-attachments/assets/f61a0b04-144c-4a8d-82ce-7be832a7a354)

![Teste resumo de vendas01](https://github.com/user-attachments/assets/7caa2d5f-e63e-416d-acf8-5515c50d82d4)


Outros Prompts testados:
Ordene as vendas de produto do mais vendido para o menos vendido em cada país. Mostrando país, produto e quantidade vendida
Resultado:
![image](https://github.com/user-attachments/assets/d75cdce7-99f8-4a52-b1cb-2483261b3eba)

Me faça a ordem de produtos mais vendidos por idade (este me gerou um problema corrigido manualmente - ele considerou idades como 1 e 122 anos)
![image](https://github.com/user-attachments/assets/c1555330-33d8-42bc-82d8-47ad19e9bedc)

Me mostre os produtos mais vendidos por país (considerando apenas os países da base de dados) 
![image](https://github.com/user-attachments/assets/4c4046d9-418e-4a67-aafc-de1936bd4207)


