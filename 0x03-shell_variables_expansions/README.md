-------------------------------0x03 SHELL VARIABLES EXPANSIONS ----------------------------- 


--Task 0 :

simple alias assignment

--Task 1 :

use echo with the variable $USER which refers the curent user to print 'hello $USER'

--Task  2 :

to add ./action to the end fo PATH we just overide PATH with it s own value + ':./action' using export :: export PATH="$PATH:./action"

--Task 3 :

to countnumber of directories in PATH we first read it using <echo $PATH> then remove any duplicate ':' with <tr -s ":"> then replace ':' with new line character \n using <tr ":" "\n"> and finally count the line <wc -l>>

--Task 4 :

simple task use <printenv>
