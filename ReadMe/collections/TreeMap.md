# TreeMap
- The TreeMap in Java is used to implement Map interface and NavigableMap along with the AbstractMap Class. 
- The map is sorted according to the natural ordering of its keys, or by a Comparator provided at map creation time, depending on which constructor is used. 
- This proves to be an efficient way of sorting and storing the key-value pairs. 
- The storing order maintained by the treemap must be consistent with equals just like any other sorted map, irrespective of the explicit comparators. 
- The treemap implementation is not synchronized in the sense that if a map is accessed by multiple threads, concurrently and at least one of the threads modifies the map structurally, it must be synchronized externally. 
- TreeMap works same as HashMap
- https://www.geeksforgeeks.org/internal-working-of-treemap-in-java/
- 