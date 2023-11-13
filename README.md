# Challenge_Final
Proyecto final de la materia de Programación I
Para este proyecto analizaremos como se dividen o se generan cluster en una tienda de ventas por internet.
## Importación de datos

Este set de datos contiene transacciones ocurridas entre los años 2010 y 2011 para una empresa de e-commerce localizada en Reino Unido. El origen del set de datos puede ser consultado [aqui](https://archive.ics.uci.edu/dataset/352/online+retail).

Este set de datos tiene las siguientes variables:

* InvoiceNo (categórico)
* StockCode (categórico)
* Description (categórico)
* Quantity (numérico Entero)
* InvoiceDate (Fecha)
* UnitPrice (numérico Real)
* CustomerID (categórico)
* Country (categórico)

Basado en ejercicio de [Kaggle](https://www.kaggle.com/code/hellbuoy/online-retail-k-means-hierarchical-clustering)
## 1 En el ejericcio elegiremos las 3 variables de numero de dias desde la ultima compra, numero de transacciónes y cantidad todal gastada por cliente, para ver como se determinan nuestros clusters.
despues de ecalar los datos, generaremos un los cluster jerarquicos.
## 2 Clustering jerárquico Se elige una métrica euclídea con un método de enlace de Ward
como primera instancia generaremos un dendograma para ver cuales seria nuestra cantidad de clusters posibles
el resultado es que posiblemente hay 3 clusters pero para descartar utilzaremos el metodo del codo y verificaremos la cantidad
Corroborando con el metodo del codo podemos deducir que efectivamente podemos tener 3 clusters 

