# Web-cloning-info

After looking into it a bit more this wget command seems to be much eaiser than downloading htttrack but htttrack has alot more options depending on how big of a projct it is.  Also depending on what os you are on it might be easier. 
'''
wget --mirror --convert-links --adjust-extension --page-requisites --no-parent <https://website.estension>
'''
## Some helpful tips with the command: 

| --accept pdf,jpg / --reject| only specific file types |
|---level=2| limits the depth of links it will go |
| --user=\<username\> --password=\<password\> | not guarenteed to work with every website but worth a shot |

## Examples 
https://doc.rust-lang.org/book/title-page.html
https://github.com/BenjaminDLowry/Web-cloning-info/blob/main/doc.rust-lang.org.zip
'wget --mirror --convert-links --adjust-extension --page-requisites --no-parent https://doc.rust-lang.org/book/title-page.html'

## htttrack 

https://www.httrack.com/page/2/en/index.html
https://www.httrack.com/html/step.html
