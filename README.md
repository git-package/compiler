# HTML Compiler

This software is a simple html, css and js compiler built on a simple runtime and lightning fast compiling. Click [HERE](https://git-package.github.io/compiler/demo) to run demo.

## Installation

Click [install](https://git-package.github.io/compiler/v3/compiler.zip) to install the script or use the bash command below.

```bash
New-Item -Path "C:\Program Files\" -Name "Compiler" -ItemType "directory"
Invoke-WebRequest https://git-package.github.io/compiler/v3/index.html -OutFile C:\Program Files\Compiler\index.html
Invoke-WebRequest https://git-package.github.io/compiler/v3/main.js -OutFile C:\Program Files\Compiler\main.js
Invoke-WebRequest https://git-package.github.io/compiler/v3/.gitignore -OutFile C:\Program Files\Compiler\.gitignore
Invoke-WebRequest https://git-package.github.io/compiler/v3/package.json -OutFile C:\Program Files\Compiler\package.json
Invoke-WebRequest https://git-package.github.io/compiler/v3/styles.css -OutFile C:\Program Files\Compiler\styles.css
```

## Run

Just run the html file or use the command below.

```bash
start chrome <your_filename_path>
```

## How to use

It's straightforward just enter your code then click "run."

There will be updates in the future to assis with coding.

## License

[MIT](https://choosealicense.com/licenses/mit/)
