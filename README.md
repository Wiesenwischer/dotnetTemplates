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

To be able to read my nugets, add my nuget registry on github to your nuget sources using the following:
````
dotnet nuget add source https://nuget.pkg.github.com/Wiesenwischer/index.json --name wiesenwischer --username Wiesenwischer --password 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 --store-password-in-clear-text
````

Installing the templates using:
````
dotnet new -i WiesenwischerTemplates --nuget-source wiesenwischer
````
