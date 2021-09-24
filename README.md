# Freshmen-Immigration
#Reverse The Number 
#Author:	1★vicky002
#Editorial:	https://discuss.codechef.com/problems/FLOW007
#Tags:	vicky002
#Problem level:	Simple
#Date Added:	27-04-2015
#Time Limit:	100 secs
#Source Limit:	50000 Bytes
#Languages:	CPP14, C, JAVA, PYTH 3.6, PYTH, PYP3, CS2, ADA, PYPY, TEXT, PAS fpc, NODEJS, RUBY, PHP, GO, HASK, TCL, PERL, SCALA, LUA, BASH, JS, LISP sbcl, PAS gpc, BF, CLOJ, D, CAML, FORT, ASM, FS, WSPC, LISP clisp, SCM guile, PERL6, ERL, CLPS, ICK, NICE, PRLG, ICON, SCM chicken, PIKE, SCM qobi, ST, NEM

def reverse(n):
    listOfInt = list(str(n))
    listOfInt = listOfInt[::-1]
    rS = ""
    for i in listOfInt:
        rS += i
    reverseNum = int(rS)
    return reverseNum
    
 
