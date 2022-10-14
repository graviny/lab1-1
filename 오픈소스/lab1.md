
def sort_insertion(a):

    for j in range(1,len(a)):
        i=0
        
        while(a[j] > a[i]):
            i+=1
        m=a[j]
        for k in range(0, j-i):
            a[j-k]=a[j-k-1]
        a[i]=m
        print(a)
    return a
