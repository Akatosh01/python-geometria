# Mi Proyecto de Geometría

Este proyecto contiene clases para representar figuras geométricas en Python.

## Estructura del Proyecto

- `src/`: Código fuente del proyecto.
- `README.md`: Descripción del proyecto.
- `requirements.txt`: Dependencias necesarias.
## Requisitos
Recomendar en el caso de Windows siempre usar powershell con permisos de Admin
Instalacion de Python

    - Win
        Instalar Chocolatey
        ```powershell
        Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
        ```
        Instalar Phyton
        ```powershell
        choco install python
        ```
        Comprobar si esta instalado
        ```powershell
        python --version
        ```

    - Mac
        Proceder a instalar
        ```bash
        brew install python
        ```
        Comprobar si esta instalado
        ```bash
        python --version
        ```

Instalar Poetry 


    - win
        Proceder a instalar 
        ```powershell
        (Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicP | python -
        ```
        Agregar al Path
        ```powershell
        setx PATH "%PATH%;C:\Users\<TuUsuario>\AppData\Roaming\Python\PythonXY\Scripts"
        ```

        Comprobar si esta instalado
        ```powershell
        poetry --version
        ```

    - Mac
        Proceder a instalar
        ```bash
        curl -sSL https://install.python-poetry.org | python3 -
        ```
        Agregar al Path
        ```bash
        export PATH="$HOME/.local/bin:$PATH"
        ```
        Recargar el Archivo
        ```bash
        source ~/.bash_profile 
        ```
        Comprobar si esta instalado
        ```bash
        poetry --version
        ```
Instalar Curl (necesario para instalar Poetry)
    
    - Win
        Instalar Chocolatey
        ```powershell
        Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.SecurityProtocolType]::Tls12; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
        ```
        Instalar Curl
        ```powershell
        choco install curl
        ```
        Comprobar si esta instalado
        ```powershell
        curl --version
        ```
    
    - Mac
        
        ```bash
        brew install curl
        ```
        Comprobar si esta instalado
        ```bash
        curl --version
        ```
        

        
## Cómo Ejecutar

Para ejecutar el programa, navega a la carpeta `src` y ejecuta:

    - Mac
        ```bash
        python3 src/main.py
        ```
    - Win
        ```
        python src/main.py
        ```
## Espero te haya servido de  ayuda