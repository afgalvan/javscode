# Javscode

Command Line Tool for exporting **basic** Java projects in vscode to netbeans, made for classmates.

## Usage

```bash
export <project-name> <main-class>
```

## Sample

```bash
export sample Main
```

## Add it to your powershell profile

- Copy the content of `main.p1`, and then paste it where your `Microsoft.Powershell_profile.ps1` file is located. Create one if you don't have it with `PS> New-Item –Path $Profile –Type File –Force`.

    > Usually in $HOME/Documents/WindowsPowerShell/

- Now, check if it's correct doing:

    ```bash
    export --version
    ```
