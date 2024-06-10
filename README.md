This program will open a file containing a dump of text and build a binary tree 
for the frequencies of characters. For example, in the string “cadabcdaa”, 
the frequencies of characters are:
a: 4
b: 1
c: 2
d: 2

And the corresponding binary tree will be:

Notice that the tree is sorted by the order of characters and not the numbers. 
For example, since ‘c’ was observed first, it is made the root node.

Output: Once your program is done, do an inorder traversal of the tree, 
outputting the data in the following format:
a : 4
b : 1
c : 2
d : 2

Additional Notes:
(1) Ignore any characters (including newlines) other than alphabets (a to z and A to Z).
(2) Ensure that any file handling errors are dealt with, such as the file not 
existing or a read not working.

Below is a sample code structure:

struct node{
 char character;
 int count;
 node *left;
 node *right; 
}

void add_node(char character){
 // ToDo
}

void print_inorder(){
 // ToDo
}
// Note: You may also create a class called BTree and have all the functions inside.

int main (){
 // ...
 // Create a tree root
 // Read file character by character and build the tree
 // call print_inorder();
 // ...
}
