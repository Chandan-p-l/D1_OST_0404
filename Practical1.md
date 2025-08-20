# Practricle 1
## Linux command Line - File opeeratrions,Navigations,Permisions.

### Command Line Interface of Making flow of 
 * **NIMS** 
     * **CSE**
        * Data.SH
        * **D1**
           * Data.txt
# OPERATIONS:
````bash
/~> cd Desktop
/Desktop> mkdir NIMS
/Desktop> cd NIMS
/NIMS> mkdir CSE
/NIMS> cd CSE
/CSE> touch Data.sh
/CSE> mkdir D1
/CSE> cd D1
/D1> touch Data.txt
/D1> echo Hii>Data.txt
/D1> cat Data.txt
     HII (OUTPUT)
/D1> echo everyone>>Data.txt
/D1> cat Data.txt
     Hii
     everyone (OUTPUT)

````
#NEVIGATION:
```` bash
/D1> cd ../../..
/Desktop> cd NIMS/CSE/D1
/D1> cd ..
/CSE> mv Data.sh D1
/CSE> cd D1
/D1> ls
     Data.sh  Data.txt
````
#PERMISIONS:

``` bash
/~> cd Desktop
/Desktop> touch script.sh
/Desktop> vim script.sh

## inside Vim
## Enter I to Insert
## echo Hello world --- To write inside the sh file
## click esc --- To exit Insert mode
## enter :wq --- To exit Vim

/Desktop> chmod +x script.sh
/Desktop sh script.sp
## To see what the content was written in sh file
      Hello World (OUTPUT)
/Desktop> cat script.sh
## To see entire thing written inside sh file
      echo Hello World 

````
<img width="1068" height="771" alt="Screenshot 2025-08-20 194647" src="https://github.com/user-attachments/assets/eb501941-32ea-46dc-bcb8-d3a42aaa0903" />


