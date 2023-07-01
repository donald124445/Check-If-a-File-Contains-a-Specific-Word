# Check-If-a-File-Contains-a-Specific-Word
with open("example.txt", "r") as file:
    has_word = "test" in file.read()
    if has_word:
        print("The file has the word 'test'")
