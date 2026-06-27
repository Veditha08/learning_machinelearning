# numpy- numerical python
- it is the lib used for numerical computing
- gives speed and can efficiently make large scale operations with its extra features
- in normal python we use lists, they r slow
- uses contigious memory unlike lists whose each value is stored in diff diff locations
- its a MATLAB replacement
- useful in plotting(matplotlib)
- used in backend(pandas, connect 4, digital photography)
- can be used to store pngs
- used in ML


The Analogy: Think of a Python list like a messy duffel bag where you can throw in clothes, books, and snacks all mixed together; it takes time to rummage through it. A NumPy array is like a perfectly organized egg carton: every slot is exactly the same size, holds exactly the same type of item, and sits right next to the other. Because of this rigid structure, your computer's processor can access and perform math on this data at lightning-fast speeds.

defining the numpy array: b = np.array([1,2,3], [2,4,5])

### Vectorization:
In standard Python, if you want to modify every item in a list (e.g., adding bonus points to scores), you typically have to write a for loop to look at each item one by one.
With NumPy, you can apply math operations to the entire array at once. This is called Vectorization.\
eg: lap_times = np.array([1,2,3,4])\
#in minutes:\
lap_in_secs = lap_times * 60\
print(lap_in_secs)         //output: [ 60 120 180 240]

### Broadcasting:
If two arrays are the exact same size, NumPy performs element-by-element math. But NumPy can also perform operations on arrays of different sizes using a mechanism called Broadcasting. NumPy virtually stretches or duplicates the smaller array so it matches the shape of the larger one.\
eg: import numpy as np\
base_scores = np.array([10, 15, 20])\
team_bonus = 5\
final_scores = base_scores + team_bonus\
print("Final Scores:", final_scores) //Output: [15, 20, 25]






