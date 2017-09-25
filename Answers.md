 <h1>What is the complexity of each of the four search methods in terms of array or list size n?
  
    *Comlexity of findTeamposition (array) = O(n) 
    *Complexity of findTeamPosition (list) = O(n) 
    *Complexity of findTeamMinFunding (array) = O(n) 
    *Complexoty of findTeamMinFundingFast = O(log(n))
  
 <h1>What happens in the case of binary search if the array is not sorted?
 
   >If the array is not sorted, the target item might not be found, as the binary search could search the incorrect half based on the values to left and right of the middle value. If the value to the right is less than the middle, then the binary search would search the values to the right, assuming the target item is less than the middle, but it's possible that the target item is not in this half. If the value to the left is greater than the middle, the binary search would search the values to the left, assuming the target item is greater than the middle, but again, its possible that the target item is not in this half.
    
 <h1>What is the purpose of constructor argument validity checking?
 
  >The purpose of constructor argument validity checking is to ensure that the arguments that are being passed in a method  make sense so that they dont cause errors that may be harder to identify in other areas of the code. 
  
 <h1>What is the purpose of using the keyword final with variables and arguments?
 
  >The use of keyword final with variables and arguments is to ensure that they are not changed. 
 
 <h1>What are alternatives to using Optional and how do they compare?
 
  >An alternative to using Optional could be using if-statements to check if values are non-null and then throw exceptions. Compared to Optional, through this alternative, we would have to explain how to check if a value is null through if-statements and then tell the program what to do if that is the case, while we can use Optional to do that for us, as Optional contains methods that deal with cases in which a value is null/not present or when it is non-null/present.
