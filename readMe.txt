// create myResourceGroupWindow via Azure browser

az appservice plan create --resource-group myResourceGroupWindow --name myWindowsPlan

az --% webapp create --resource-group myResourceGroupWindow --plan myWindowsPlan --name ancwebsite --runtime "DOTNETCORE|3.1" --deployment-local-git