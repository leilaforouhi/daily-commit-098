def find_longest_word(text):
    words = text.split()
    longest = max(words, key=len)
    return longest

if __name__ == "__main__":
    sentence = "Consistency creates long term success"
    print(f"Sentence: {sentence}")
    print(f"Longest word: {find_longest_word(sentence)}")
