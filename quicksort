import random

list_sort = [5, 7, 8, 3, 9, 4, 8, 3, 8, 2, 8, 9, 4, 7, 6, 1, 0, 4, 8] #you can add or remove any numbers in this list


b = False

while not b:
    b = all(list_sort[i] <= list_sort[i + 1] for i in range(len(list_sort) - 1))
    bottom_list = []
    top_list = []
    random_number = random.randrange(len(list_sort))
    pivot = list_sort[random_number]
    [bottom_list.append(i) for i in list_sort if i <= pivot]
    [top_list.append(i) for i in list_sort if i > pivot]
    list_sort = bottom_list + top_list

print(list_sort)
