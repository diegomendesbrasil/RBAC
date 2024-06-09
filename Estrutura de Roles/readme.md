Assim como a AzureML Workspace Admin dev VLI, nao consigo liberar a nova role customizada a nível de subscription para esse grupo de AD?
Crio uma nova custom chamada "AzureML Middleware DSV" com os outros acessos já a nível de subscription, sendo necessário solicitar inclusao apenas das roles:
    "AzureML Middleware DSV" 
    "AzureML Workspace Admin DEV VLI" 


************** ACESSOS ***************

GUF_AZURE_ML_MIDDLEWARE_DEV
    "AzureML Middleware DEV" 
    "AzureML Workspace Admin DEV VLI"  

GUF_AZURE_ML_MIDDLEWARE_PRD


GUF_AZURE_DATASCIENCE_DEV
    "AzureML Blob Access DEV"
    "AzureML Data Scientist"

    "AzureML Blob Access HML"
    

GUF_AZURE_DATASCIENCE_PRD


GUF_AZURE_DATAENGINEER_DEV
    "AzureML Blob Access DEV"
    "AzureML Blob Access HML"    