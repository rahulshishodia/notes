## Data Structures & Algorithm using Java
List of Data Structures using Java

 1. [Arrays](#arrays)
 2. [Linked List](#linked-list)
 3. [Stack](#stack)
 4. [Queue](#queue)
 5. [Binary Tree](#binary-tree)
 6. [Binary Search Tree](#binary-search-tree)
 7. [Heap](#heap)
 8. [Hashing](#hashing)
 9. [Graph](#graph)

### Arrays
1. Linear Data Structure
2. Elements are stored in contiguous memory locations
3.Can access elements randomly using index
4. Stores homogeneous elements i.e, similar elements

**Syntax:**
*Array declaration*
```java
    datatype varname[] = new datatype[size];  
    datatype[] varname = new datatype[size];  
    // Can also do declaration and initialization at once
    Datatype[] varname = {ele1, ele2, ele3, ele4};
```
**Advantages**

 1. Random access Easy sorting and iteration 
 2. Replacement of multiple variables 

**Disadvantages** 

 1. Size is fixed 
 2. Difficult to insert and delete If capacity is more and occupancy less, most of the array gets wasted
 3. Needs contiguous memory to get allocated

**Applications**
1. For storing information in a linear fashion
2. Suitable for applications that require frequent searching

### Linked List
1. Linear Data Structure
2. Elements can be stored as per memory availability
3. Can access elements on linear fashion only
4. Stores homogeneous elements i.e, similar elements
5. Dynamic in size
6. Easy insertion and deletion 
7. Starting element or Node is the key which is generally termed as head.

**Advantages**
1. Dynamic in size
2. No wastage as capacity and size is always equal
3. Easy insertion and deletion as 1 link manipulation is required
4. Efficient memory allocation

**Disadvantages**
1. If head Node is lost, the linked list is lost
2. No random access possible

**Applications**
1. Suitable where memory is limited 
2.  Suitable for applications that require frequent insertion and deletion
