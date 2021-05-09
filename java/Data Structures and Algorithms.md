## Data Structures & Algorithm using Java
List of Data Structures using Java

 1. [Array](https://github.com/rahulshishodia/notes/new/main#arrays)
 2. Linked List
 3. Stack
 4. Queue
 5. Binary Tree
 6. Binary Search Tree
 7. Heap
 8. Hashing
 9. Graph

### Arrays
1. Linear Data Structure
2. Elements are stored in contiguous memory locations
3.Can access elements randomly using index
4. Stores homogeneous elements i.e, similar elements

**Syntax:**
*Array declaration*

    datatype varname []=new datatype[size];  
    datatype[] varname=new datatype[size];  
    Can also do declaration and initialization at once
    Datatype varname [] = {ele1, ele2, ele3, ele4};

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

**Demonstration of Array**
```java
    import java.util.*;
    
    class JavaDemo {
    	public static void main (String[] args) {
    	    int[] priceOfPen= new int[5];
    	    Scanner in=new Scanner(System.in);
    	    for(int i=0;i<priceOfPen.length;i++)
    	        priceOfPen[i]=in.nextInt();
    
    	    for(int i=0;i<priceOfPen.length;i++)
    		    System.out.print(priceOfPen[i]+" ");
    	}
    }

    Input:
    23 13 56 78 10
    
    Output:
    23 13 56 78 10 
   ```
