# Javscode

Command Line Tool for exporting vscode java projects to [netbeans](https://netbeans.org/)

## Usage

```bash
powershell main.ps1 <project-name> <main-class>
```

## Sample

```bash
powershell main.ps1 sample Main
```

## Adding it to your powershell profile

- Copy the content of `main.p1`, and then paste it where your `Microsoft.Powershell_profile.ps1` is located, create one if you don't have it with `PS> New-Item –Path $Profile –Type File –Force`.

    > Usually in $HOME/Documents/WindowsPowerShell/

- Now, call the script with `export`, like:

    ```bash
    export <project-name> <main-class>
    ```
