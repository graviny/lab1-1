# lab1-1
lab1-1_cal
def max(list):
    max=list[0]
    pos=0
    n=len(list)
    
    for i in range(1,n):
        if max<=list[i]:
            max=list[i]
            pos=i+1
            
    return print("최대값 %d는 리스트의 %d번째에 위치한다"  %(max,pos))
list=[4,7,9,2,4,9,5,6,7,9,4,6]
           

max(list)
