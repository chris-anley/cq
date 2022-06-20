# cq

Code Query, a universal code security scanning tool.

CQ is Code Query, or Sécurité, or CQD, or "Seek You".

## Intended Purpose

CQ is intended to be used in a consultancy context by human experts. It is not intended for use in automated scenarios, 
although it might be applied in that context. 

CQ outputs plain text files, with typically one finding per line, using the convention full path:line number to 
represent locations in the codebase. This format is used to allow for ease of manipulation using the standard unix 
command line utilities, such as grep, wc, sed and similar, and the line-based facilities of many editors 
such as vi, Sublime Text, Atom and Visual Studio Code.

The focus on reporting all items of interest results in a tool that will find many points of interest in 
almost any codebase, but which will also report a large number of 'false positives'. These false positives can be 
removed from the results either by inspection or in an automated fashion, due to the line-based reporting method.  

Little to no explanation of issues is provided; it's assumed that you are aware of the context, impact and 
characteristics of the issues reported.


