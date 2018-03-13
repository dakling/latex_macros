Create semantic syntax for my latex source files. 
Split into global file for generic macro definition and local file for document-specific settings
Path to global file should be set using the environment variable $LatexGlobalConfig. 
However, if a global config file is present in latex source directory, this file takes precendence.
