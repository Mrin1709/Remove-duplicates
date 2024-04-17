def remove_duplicates(lst):
    seen = set()
    return [x for x in lst if not (x in seen or seen.add(x))]

example_list = [1, 2, 3, 4, 2, 3, 5, 6, 4]

result = remove_duplicates(example_list)

print("List after removing duplicates:", result)
