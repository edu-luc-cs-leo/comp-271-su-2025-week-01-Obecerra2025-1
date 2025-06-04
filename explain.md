/**Explaining the use of arr.length as an index for array temporary in line 83 */

/*
* arr.length is the size of the original array so after copying all elements from arr to temporary, ->
* the next empty spot is at index arr.length.
* 
* Line temporary[arr.length] = value adds a new number at the end of the array.
*/