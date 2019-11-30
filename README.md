# Sorting-algorithm-Visualiser
sorts the random numbers generated using different sorting algorithms and is visualised using animation.

## Sorting Algorithms
- Bubble Sort
- Selection Sort
- Merge sort
- quick sort
- Insertion sort

# Algorithms Description

## Bubble sort
  begin BubbleSort(list)
   for all elements of list
      if list[i] > list[i+1]
         swap(list[i], list[i+1])
      end if
   end for  
   return list
 end BubbleSort

## selection sort
   Step 1 − Set MIN to location 0
   Step 2 − Search the minimum element in the list
   Step 3 − Swap with value at location MIN
   Step 4 − Increment MIN to point to next element
   Step 5 − Repeat until list is sorted
   
## Merge sort 
   Step 1 − if it is only one element in the list it is already sorted, return.
   Step 2 − divide the list recursively into two halves until it can no more be divided.
   Step 3 − merge the smaller lists into new list in sorted order.

## Quick sort 
   Step 1 − Choose the highest index value has pivot
   Step 2 − Take two variables to point left and right of the list excluding pivot
   Step 3 − left points to the low index
   Step 4 − right points to the high
   Step 5 − while value at left is less than pivot move right
   Step 6 − while value at right is greater than pivot move left
   Step 7 − if both step 5 and step 6 does not match swap left and right
   Step 8 − if left ≥ right, the point where they met is new pivot

## Insertion sort 
   Step 1 − If it is the first element, it is already sorted. return 1;
   Step 2 − Pick next element
   Step 3 − Compare with all elements in the sorted sub-list
   Step 4 − Shift all the elements in the sorted sub-list that is greater than the value to be sorted
   Step 5 − Insert the value
   Step 6 − Repeat until list is sorted
