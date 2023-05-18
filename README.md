Method1:-
def reverse_string(str):  
    str1 = ""   # Declaring empty string to store the reversed string  
    for i in str:  
        str1 = i + str1  
    return str1    # It will return the reverse string to the caller function  
Method2:-
str = "123abcd"    # Given String       
print("The original string is: ",str)  
print("The reverse string is",reverse_string(str)) # Function call  

str = "123abcd" #  string variable  
print ("The original string  is : ",str)   
reverse_String = ""  # Empty String  
count = len(str) # Find length of a string and save in count variable  
while count > 0:   
    reverse_String += str[ count - 1 ] # save the value of str[count-1] in reverseString  
    count = count - 1 # decrement index  
print ("The reversed string using a while loop is : ",reverse_String)# reversed string

Method3:-

def reverse(str):   
    str = str[::-1]   
    return str   
    
s = "samchandu143"  
print ("The original string  is : ",s)   
print ("The reversed string using extended slice operator  is : ",reverse(s))  
