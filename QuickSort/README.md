- [ ] learn who/what/when/where/why/how
- [ ] get up to speed on the algorithm
- [ ] develop a project goal
- [ ] run through the project

# Complexity
  - Best case time complexity of Quicksort is **O**(n*log*n), while the worst case time complexity is **O**(*n*)^2
  - the space complexity is **O** *log*(n) in the best case, but can become **O***n* in the worst case

## Pivot Selection
  - choice of pivot significantly affects the algorithm's performance. Poor pivot choices can lead to more recursive calls, which can lead to worst-case complexity
  - strategies for choosing a pivot include picking the first or last element, the median, or a random element

## Variants
  - **Randomized Quicksort** Involves selecting a random element as the pivot for each partitioning.
  - **Three-way Partitioning** used when an array contains many duplicate elements. partitions into lessthan/equalto/greater than

## Advantages and Disadvantages
  - Quicksort is very efficient for large datasets and has good cache performance
  - It is a complex algorithm and can be unstable (it can change the order of equal elements)
