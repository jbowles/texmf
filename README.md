#Texmf
The `texmf` direcotry is for placing template configuration settings for compiling special LaTeX formatting.
It is also a place to archive images for compiliation. For example, `texmf/tex/mysty/myarticle/paperc.sty` contains custom stylings for writing research papers; I simply include it as package and compile.
Additionally, `texmf/tex/gix` contains image files that I can include accross any LaTeX document.

## File System Location for texmf
In order to compile natively accross any LaTeX document the `texmf` directory needs to be accessible to the compiler. The location can depend on how you are compiling and which TeX tools you are using.
Currently I'm using the Tex application toolset provided for Mac Lion (see `/Applications/TeX`; I'm specifically using `/Applications/TeX/TeXworks.app`). This requires the location `/Users/jbowles/Library/texmf`.
On other operating systems or when using a different toolset for compilation you can put the `texmf` directory in other places (i.e, `$HOME/`)
