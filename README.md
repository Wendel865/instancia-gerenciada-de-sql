# instancia-gerenciada-de-sql
na plataforma azure
   az sql mi create \
          --name myManagedInstance \
          --resource-group myResourceGroup \
          --location eastus \
          --edition Standard \
          --sku-name Standard_DS2_v2 \
          --sql-version 2022

          
