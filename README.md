# Word-Counter-
# Program to count words in string using python

# Step 1: Take input from user
text = input("Enter your text: ")
print("You have entered the text:" + text)

# Step 2: Convert text into list
list = text.split()

# Step 3: Find the length of the list
length = len(list)

# Step 4: Print the length
print("Total number of words are:" +str(length))
