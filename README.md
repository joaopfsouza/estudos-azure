# Azure Cloud

## Azure CLI

Mostra conta default do azure
```
az account show

```

Mostra todas subscrições
```
az account list
```

Trocar account default 
```
az account set [-s | --subscription] ["Nome Subscription" | "a50e7b76-8ea5-492c-bf17-97d652fc3ce9"] 
```

Mostra os arquivos de configurações 
```
az configure
```

Mostra help do comando vm
```
az vm --help
```

Restart maquina
```
az vm restart -g "ResourceGroup" -n "Nome da VM"
```