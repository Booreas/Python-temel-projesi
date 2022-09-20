#Patika.dev temel python flatten fonksiyon projesi

list = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

flat_list = []


def flatten(n):

    makeflat = [flatten(i) if isinstance(i, type(list)) else flat_list.append(i) for i in n] 
    

flatten(list)

print(flat_list)

-----------------------------------------------------------------------------------------------------------------------------------


#Patika.dev temel python reverse fonksiyon projesi

list =[[1, 2], [3, 4], [5, 6, 7]]

def reverse(list):

  list=list[::-1]
  

  reverselist = [list[i][::-1] for i in range(len(list)) ]
  
  return reverselist
  

print(reverse(list))

