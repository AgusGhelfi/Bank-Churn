# Bank-Churn
Análisis de clientes de un banco

Se plan teó como objetivo predecir aquellos clientes con mayor propensión a cancelar la tarjeta de crédito del banco, lo que se conoce como Churn. Los datos que se
utilizaron corresponden a los clientes de una tarjeta de crédito de un banco. En el mismo podemos identificar las siguientes columnas: 

  - CLIENTNUM: identificador único del cliente.
  - Attrition_Flag: Indica si el cliente sigue vigente o si ha cancelado la tarjeta. Columna que hay que predecir. 
  - Customer_Age: edad del cliente.
  - Gender: género del cliente.
  - Dependent_count: cantidad de dependientes que posee el cliente.
  - Education_Level: nivel educativo del cliente.
  - Marital_Status: estado civil del cliente.
  - Income_Category: categorización de ingresos del cliente.
  - Card_Category: tipo de tarjeta que posee el cliente.
  - Months_on_book: cantidad de meses desde que el cliente tiene la tarjeta de crédito.
  - Total_Relationship_Count: Cantidad de productos que tiene el cliente.
  - Months_Inactive_12_mon: Cantidad de meses inactivos en los últimos 12 meses.
  - Contacts_Count_12_mon: Cantidad de veces que se contactó al cliente en los últimos 12 meses.
  - Credit_Limit: límite de crédito de la tarjeta.
  - Total_Revolving_Bal: un saldo renovable es la parte del gasto de la tarjeta de crédito que no se paga al final de un ciclo de facturación.
  - Avg_Open_To_Buy: Promedio del saldo disponible.
  - Total_Amt_Chng_Q4_Q1: Cambios en los montos de las transacciones. 
  - Total_Trans_Amt: Monto total de transacciones.
  - Total_Trans_Ct: Cantidad total de transacciones.
  - Total_Ct_Chng_Q4_Q1: Cambios en la cantidad de transacciones.
  - Avg_Utilization_Ratio: promedio de utilización de la tarjeta.
  
Luego del análisis de dato con EDA se decide implentar diferentes modelos para predecir los clientes potenciales a cancelar la tarjeta de crédito, por lo que implemente:
  - Decision Tree
  - Support Vector Machine
  - KNN
  - Logistic Regression
  - Random Forest
Sobre los mismos se realiza un GridSearch para encontrar los mejores parámetros para cada uno y luego con esos parámetros se aplica Cross Validation visualizandose las 
medidas como: Accuracy, Recall, Precision, F1
