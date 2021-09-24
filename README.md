# Freshmen-Immigration

# Editorial:	https://discuss.codechef.com/problems/FLOW007

# Date Added:	27-04-2015

def reverse(n):
    listOfInt = list(str(n))
    listOfInt = listOfInt[::-1]
    rS = ""
    for i in listOfInt:
        rS += i
    reverseNum = int(rS)
    return reverseNum
    
 
