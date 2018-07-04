# Create semantic syntax for my latex source files. 

# Different files
- definGlobal.tex: contains the macros. Should be seen as a system-wide configuration valid for all Latex projects
- definLocalExample.tex: contains project-specific settings, should be present in every Latex project directory
- example.tex: not really needed, just shows some examples to simplify understanding what the macros do

# step by step
- git clone https://www.github.com/dakling/latex_macros
- copy the file definLocalExample.tex to your project directory (maybe rename it to definLocal.tex)
- put \input{definLocal.tex} into your main Latex source document 
- definLocal.tex loads definGlobal.tex. Possibly adapt definLocal.tex to make sure that it finds definGlobal.tex
