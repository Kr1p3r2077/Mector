# Mector
coolest version of Vector, created by me

///Methods///

///VERSION 1.0///

Constructor(int size = 0, T default_value);
default values are present, T - custom type

[] operator overloading

int getSize();
returns size of array

void Resize(int newSize);
resize the array

void Print(bool endline);
if 'endline' == true a transition to the next line is added
default value is false

void Insert(int position, T object); T - custom type
Inserts 'object' in position index in array

void Add_end(T object); T - custom type
Adds an element to the end

void Add_start(T object); T - custom type
Adds an element to the start

void Del(int position);
Removes element at position

void Del_end();
Removes element at end

void Del_start();
Removes element at start

void Del_end_count(int k);
Removes 'k' elements from the end

void Del_start_count(int k);
Removes 'k' elements from the start

void Del_fromto(int k, int n);
Removes elements from 'k' index to 'n' index, 
'k' does not have to be greater than 'n'

void Reverse();
Flips the array

void Reverse_fromto(int k, int n);
Flips an array from 'k' index to 'n' index

void Sort_asc();
Sorts in ascending order if the array type has overloads < , >, <=

void Sort_desc();
Sorts in descending order if the array type has overloads < , >, <=

void SetDefaultValue(T object); T - custom type
Sets the default value in array.
It is used during array cleanup.

void Clear();
Clears the array

void Append(Mector m);
Adds another array to the main array
(may not work correctly, I will fix it soon)

int FindCountOf(T object); T - custom type
Finds the count of occurrences of a given element in an array, if the array type has the == operator overloading

///VERSION 1.04///
int getSizeofType();
Returns the sizeof(T - custom type)

int getSizeofArray();
Returns the sizeof(T - custom type) multiplyed by size

void DeleteDynamicMemory(); aka DDM
Сlears dynamic memory

~Mector();
Вoes the same as DDM
