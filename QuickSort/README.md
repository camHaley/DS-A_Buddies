# This Week's Goals

- [ ] learn who/what/when/where/why/how
- [ ] get up to speed on the algorithm
- [ ] develop a project goal
- [ ] run through the project

## Complexity
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
___________________________________________________________________________________________________________________________________________

# ADS-B Aircraft/Interactive Map App 

## 1. User Stories
### Required Must-have Stories
 - [ ] View Real-time Flight Data on interactive Map: Users can view real-time flight data including aircraft position, altitude, and speed.
 - [ ] View Detailed Flight Information: Users can select/hover over a flight to view more detailed information.
 - [ ] Search for Specific Flights: Users can search for flights based on call signs, flight numbers, or airline.
 - [ ] Sort Flight Data: Users can sort flight data based on different parameters such as airline, destination, aircraft type, call sign using quicksort (or other sorting algos we determine) 

### Optional Nice-to-have Stories
 - [ ] Historical Flight Data: Users can access historical flight data for a specific date and time.
 - [ ] User Preferences: users can track and get notifications on specific tail #'s 

## 2. Screen Archetypes
### Home Screen
 - [ ] View Real-time Flight Data on Map
 - [ ] Text Bar to refine what map shows (airline, a/c type, specific tail #)
 - [ ] Details of flights revealed when hovered over

### Search Historical Data (were we implement sorting)
 - [ ] Users can search for flights by airline, type A/C , etc
 - [ ] Users can determine how they want their results sorted

### Favorites
 - [ ] Users can track a set of specific tail numbers

## 3. Navigation
### Tab Navigation (Tab to Screen)
 - [ ] Home Tab: Navigates to the Home Screen
 - [ ] Search Tab: Navigates to the search screen
 - [ ] Favorites: Navigates to the favorites screen

### Flow Navigations
 - don't really think that we need anything other than tabs
