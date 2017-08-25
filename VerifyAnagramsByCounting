def verify_anagrams(first_word, second_word):
     if get_counts(first_word)== get_counts(second_word):
         return True
     else:
         return False
    
def get_counts(string):
    counts_tuple = []
    alphabetical = sorted("".join(string.split()).upper())
    for index in range(len(alphabetical)):
        letter, counter = alphabetical[index], alphabetical.count(alphabetical[index])
        tuple = (letter, counter)
        counts_tuple.append(tuple)
    return counts_tuple
