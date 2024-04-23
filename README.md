# ChromeExtension.Web.Template
Template for creation new chrome extension project via dotnet new command

Install 
```
dotnet new install ChromeExtension.Web.Template
```

```
dotnet new chromeextension -h
Chrome Extension Solution
Author: Andrey Vorobiev

Usage:
  dotnet new chromeextension [options] [template options]

Options:
  -n, --name <name>      The name for the output being created. If no name is specified, the name of the output
                         directory is used.
  -o, --output <output>  Location to place the generated output.
  --dry-run              Displays a summary of what would happen if the given command line were run if it would result
                         in a template creation.
  --force                Forces content to be generated even if it would change existing files.
  --no-update-check      Disables checking for the template package updates when instantiating a template.
  --project <project>    The project that should be used for context evaluation.

Template options:
  -p, --projectName <projectName>   Type: string
                                    Default: Chrome Extension
  -de, --description <description>  Type: string
                                    Default: Chrome Extension Description
```
Options                                | Description
-------------------------------------- | ------------------------------------------------------
`-p, --projectName <projectName>`      | The argument is optional. If you don't pass a default value, the default value is `Chrome Extension`.
`-de, --description <description>`     | The argument is optional. If you don't pass a default value, the default value is `Chrome Extension Description`.
