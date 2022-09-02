# dotnet new  templates


> Remarks:
After updating template metadata you should execute the following command
    ````
    dotnet new --debug:rebuildcache
    ````
## Testing locally
The templates can be installed using the following:
````
dotnet new --uninstall .\
dotnet new --install .\
````
## Templates
- ELK-Stack Docker   
       To add the elk stack to your solution use the following:
        ````
        dotnet new elkdocker --indexname <your index name>
        ````
        
## Installation

Installing the templates using:
````
dotnet new -i WiesenwischerTemplates
````
