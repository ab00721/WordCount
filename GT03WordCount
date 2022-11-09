def average_word_length(my_string):
    try:
        result = character_count(my_string)/word_count(my_string)
        if result == 0:
            return "No words"
        else:
            return result
    except ZeroDivisionError:
        return "No words"
    except TypeError:
        return "Not a string"


def character_count(my_string):
    count = 0
    try:
        for i in my_string:
            if i in "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz":
                count += 1
        return count
    except TypeError:
        return "No words"

def word_count(my_string):
    try:
        substring = my_string.split()
        count = len(substring)
        return count
    except AttributeError:
        return "Not a string"

a_string = "Hello, my name is Anna."
result = average_word_length(a_string)
print("Average word length:", result)