# Reccomendation
## Ruby Documentation

### Reccomendation
>### YARD
YARD is the standard code documentor for Ruby programs. YARD draws from RDoc and for many purposes is very similar. It is easy to use in the terminal and when writing Ruby, the commenting is pretty strait forward to use the self documentor. It also supports tagging within comments that can be traced. Outputs a HTML file that is saved in "doc" folder where documentation takes place. 
	
	>>#### Installation
	>>>YARD is available as a ruby gem
		>>>>gem install yard

	>>#### Use
	>>>There are many uses of YARD but the main tool is documentation.
		>>>>yard doc "file_name||directory||repo"
		>>>>yardoc "file_name||directory||repo"

### Other Options
#### RDoc
>RDoc was the base for YARD and when documenting code, they do the exact same thing. However, they do not support tagging and the generally useability of the resutling HTML is far more complicated than YARD.  

### Rocco
>Rocco is vert simular to shocco, which works, but borrows heavily on Docco which is old and not super great visually and requires a very specific commenting pattern and the resulting HTML is not very responsive. It is available as a RubyGem and easily installed and used. From there it is easy to use but only does one file at a time.

## Shell Documentation

### Reccomendation
### shocco
>shocco is the best option for generating documentation of shell scripts. It is not great and comments must be formatted very specifically in order for it to document well, but it can document scripts in a way that makes sense and is easy to read. Another drawback that can be worked around is that it outputs HTML directly to the terminal, so the output must be saved in an HTML file.
	
	>>#### Installation
	>>>shocco is available as a Hombrew recipe.
		>>>brew install shocco

	>>#### Use
	>>>shocco only wokrs with one file at a time :face_with_rolling_eyes:.
		>>>shocco "file name" > "file name".html

### There are not very many other options for bash shells
