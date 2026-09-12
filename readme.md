""Algorithm for Bubble and Pointers""

Basic Algorithm

constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)

Starter Code
- Declare values with 9 integers.
- print "Before: /n" and call printValues(values).
- Declare test integers x and y and print them.
- Call swap(&x, &y).
- Call sort(values).
- print "After:" and call printValues(values).

int main(){
  int values[] = {7, 3, 9, 4, 6, 1, 2, 8, 5};
  printf("Before: \n");
  printValues(values);

  // test swap
  int x = 3;
  int y = 5;
  printf("x: %d, y: %d \n", x, y);
  swap(&x, &y);
  printf("x: %d, y: %d \n", x, y);

  sort(values);
  printf("After: \n");
  printValues(values);

  return(0);
} // end main

what can I do with the void variables void printValues(int*); , void sort(int*); , void swap(int*, int*);

void printvalues(int*); 
- make some brackets so that the numbers can stay in line.
- make a loop that each of the elements in the array that have each number go through.
- print a closing bracket.

void sort(int*);
- create a loop involving i and j.
- make a loop that gets i from 0 to MAX.
- make some arrays involving i and j as well.
- 

void swap(int*, int*);
- Create a variable called temp.
- make a way for temp to get involved with addresses with possible other variables.

