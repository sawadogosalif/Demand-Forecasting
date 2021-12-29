# Demand-Forecasting

Pour chaque segment, nous découvrirons comment le volume d’une référence 
SKU particulière dépend de l’assortiment actuel (produits d’ECCBC disponible dans 
le Pdv), des caractéristiques et des facteurs externes (par exemple, météo, événements 
spéciaux). En effet, nous modélisons la performance des SKUs (capturée par les ventes
observées représentées) à partir d’un modèle de demande à effet fixe (contrôle du 
volume de sortie habituel). Un input important au modèle est une matrice signalant la 
cannibalisation entre les marques et les saveurs. Pour simplifier la compréhension, cidessous le modèle par SKU pour un cluster donné s’écrira comme suit :
