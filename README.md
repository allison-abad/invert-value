# invert-value

Code War, Innvert Value asked me to solve the following question. "Given a set of numbers, return the additive inverse of each. Each positive becomes negatives, and the negatives become positives."
invert([1,2,3,4,5]) == [-1,-2,-3,-4,-5]
invert([1,-2,3,-4,5]) == [-1,2,-3,4,-5]
invert([]) == [] 


## How It's Made:

**Tech used:** Javascript , 
I made a local array within the invert function, followed by using a for loop method to iterate throught the array. I then created a conditional to verify whether the integer would be equal to 0, if that integer is 0 then it will be placed onto the result array. If the answer if not 0 then we'd have to multiply by -1 and push it into the array. Lastly we will return the result.


While working on this code war I took away that it's very essential to write out Pseudo code for one's work. It allows better understanding and makes it more accessible to debug your code when there happens to be errors. 
