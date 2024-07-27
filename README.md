# count
# Define a function to count the occurrences of the word 'sand'
def count_sand(text):
    # Convert text to lowercase to ensure case-insensitive matching
    text = text.lower()
    # Count occurrences of 'sand'
    count = text.split().count('sand')
    return count

# Example text
text = "There is sand on the beach, and more sand around the dunes."

# Call the function and print the result
print("Number of 'sand' occurrences:", count_sand(text))
