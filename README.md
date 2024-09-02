# Elementwise-Sum
#Create a function that takes two tuples and returns a tuple containing the element-wise sum of the input tuples

def tuple_elementwise_sum(tuple1, tuple2):
    
    result = []
    
    for i in range(len(tuple1)):
        
        
        result.append(tuple1[i] + tuple2[i])
            
       # if index[i] = index[j]:
        #    empty_tuple = tuple1[i] + tuple2[j]
    return tuple(result)
    
    #return tuple(map(sum, zip(tuple1, tuple2)))
