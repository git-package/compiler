# HTML Compiler

This software is a simple html, css and js compiler built on a simple runtime and lightning fast compiling

## Installation

Click [install](https://git-package.github.io/compiler/v3/compiler.zip) to install the script or use the bash command below.

```bash
New-Item -Path "C:\Program Files\" -Name "Compiler" -ItemType "directory"
Invoke-WebRequest https://git-package.github.io/compiler/v3/index.html -OutFile C:\Program Files\Compiler/index.html
Invoke-WebRequest https://git-package.github.io/compiler/v3/main.js -OutFile C:\Program Files\Compiler/main.js
Invoke-WebRequest https://git-package.github.io/compiler/v3/.gitignore -OutFile C:\Program Files\Compiler/.gitignore
Invoke-WebRequest https://git-package.github.io/compiler/v3/package.json -OutFile C:\Program Files\Compiler/package.json
Invoke-WebRequest https://git-package.github.io/compiler/v3/styles.css -OutFile C:\Program Files\Compiler/styles.css
```

## Run

```bash
python num-13.py
```

## How to use

When you run the script it will request the number. once input the script will output the numbers status.

Updates will be released to improve the script.

## License

[MIT](https://choosealicense.com/licenses/mit/)
