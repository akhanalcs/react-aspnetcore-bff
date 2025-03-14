# react-aspnetcore-bff
Production ready ASP.NET Core BFF with a React frontend.

## Helpful links
1. https://auth0.com/blog/the-backend-for-frontend-pattern-bff/ (Great article, read it!)

## Sample apps
1. David Fowler's [BFF example](https://github.com/davidfowl/TodoApp)
   - Clone it and run it to see how it works.
   - Make sure you have `dotnet-ef` tool installed.
     - This command is run by the AppHost project automatically so you don't really have to run it.
       
       `dotnet tool install --global dotnet-ef`
     - Make sure you add `dotnet-ef` tool to your PATH.
       - `export PATH="$PATH:$HOME/.dotnet/tools"`
     
         <img width="650" alt="image" src="screenshots/dotnet-ef-install.png">
       - More info on adding to PATH: https://stackoverflow.com/a/77428269/8644294
     - Make sure `DOTNET_ROOT` environment variable is set for `dotnet-ef` tool to work.
       - Check using `echo $DOTNET_ROOT`.
       - If not set, add it to your `.bash_profile` file.
         ```bash
         # Set DOTNET_ROOT environment variable
         export DOTNET_ROOT="$HOME/.dotnet"
         ```
     - Check if `dotnet-ef` is properly installed using `dotnet ef --version` or `dotnet-ef --version`.
     
