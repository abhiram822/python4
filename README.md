# python4
#flatted list
nest=[[1,2,3],[4,5],[6,7]]
flat=[item for sub in nest for item in sub]
print(flat)

#another way
nest=[[1,2,3],[4,5],[6,7]]
flat=[]
for sub in nest:
    for item in sub:
        flat.append(item)
print(flat)

