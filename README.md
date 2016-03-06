# Panagrams

a= str(raw_input())
b= a.lower()
k ="abcdefghijklmnopqrstuvwxyz"
n=26
for i in range(26):
    for j in range(len(a)):
        if b[j]==k[i]:
            n=n-1
            break
        else :
            n=n
     
if n==0:
    print "pangram"
else:
    print "not pangram"
