# ILAGAN_2ECEA_PA_1

### The alphabet soup problem requires a function that takes a string and returns a string thats arranged alphabetically

def alphabet_soup(text):
return '' .join(sorted(text))    
// sorts the text alphabetically

print(alphabet_soup("hello")) 
print(alphabet_soup("hacker"))
print(alphabet_soup("Artifical")) 
print(alphabet_soup("Atomic"))

// prints the text in alphabetical order


### The emoticon problem requires a function that converts the words "Smile", "Grin", "sad", and "mad" into its emoticon version.

def emotify(face):
    face = face.replace("smile", ":)") 
face = face.replace("grin", ":D") 
face = face.replace("sad", ":((") 
face = face.replace("mad", ">:(") 
return face
// Replaces the words to be converted into the emoticon
    
print(emotify("Make me smile")) 
print(emotify("I am mad"))
print(emotify("You make me grin"))
print(emotify("Why are you sad ?"))
// Prints the phrases and replaces the word


### The Unpacking list problem requires creating a list and segregating them from first, the last, and everything in between 

list = [1, 2, 3, 4, 5, 6] 
first = print(list[0]) 
middle = print(list[1:-1]) 
last = print(list[-1])
// defines the list and prints it accordingly


color = ["red", "orange", "yellow", "green", "blue", "purple", "black", "white"] 
first = print(color[0]) 
middle = print(color[1:-1]) 
last = print(color[-1])
// the same as previous, just different elements of the list

