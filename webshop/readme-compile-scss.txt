how to compile scss to css (teacher guide)

this project uses scss files:
- scss/_variables.scss (colors only)
- scss/main.scss (imports variables and contains styles)

output css file expected by html:
- css/main.css

option a: dart sass (recommended)

1) install sass globally (one time):
   npm install -g sass

2) from the project root folder (lab1) run:
   sass scss/main.scss css/main.css

3) to auto recompile on changes:
   sass --watch scss/main.scss:css/main.css

option b: vscode extension

1) install an scss compiler extension (for example: live sass compiler)
2) set output path to: css/main.css
3) start watching/compiling.

note:
- do not edit css/main.css manually (it is generated)
- open index.html in a browser to view the pages.
