# Mector
coolest version of Vector, created by me

///Methods///

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

void Insert(int position, T object);
Inserts 'object' in position index in array

void Add_end(T object);
Adds an element to the end

void Add_start(T object);
Adds an element to the start
