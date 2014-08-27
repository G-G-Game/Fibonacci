Fibonacci
=========

Create a Fibonacci pattern

parents, babies = (1, 1)
while babies < 100:
    print "This generation has {0} babies".format(babies)
    parents, babies = (babies, parents + babies)


    #Antalet babies plussas ihop med föregående värde, t.ex. 1+2= 3 babies och 13+21=34 babies. Fibonacci mönster.
pennah
