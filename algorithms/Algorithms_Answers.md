Add your answers to the Algorithms exercises here.

Exercise I

a) time complexity is O(n).

b)time complexity is O(log(n)).

c)time complexity is O(sqrt(n)).

d)inner loop will run for n times and the outer loop run for O(log(n)). Overall time complexity is O(nlog(n)).

e)time complexity is O(n^3).

f)time complexity of recursive function is O(n).

g)time complexity in worst case situation is O(n).

Exercise II:

a) def max_value(array):
    max = 0
    min = 0
    for i in arr:
       if i > max:
         max = i
       if element < i:
         min = i

    return max - min
     
b)let's assume f = n/2 and begin finding the optimum value of f based on the result.
def find_f(n):
    f = n/2
    while (i >= 1):
      res = throw(f)
      if (res == "broken"):
        f -= 1
      elif(res == "not broken")
        f += 1
    return f      
     
Exercise III
a) In case of sorted array, all the elements are added to greater and O(n) times comparisons are performed each time. Hence, overall complexity is O(n^2).

b)if the pivot element is always median, then the elements are equally distributed in both greater and less. comparisons are performed O(n) times and quicksort runs for O(logn) times. Hence, overall time complexity is O(nlogn).

  
