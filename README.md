# For_loop_Iterate_over_the_item

x = [21, "salma,", "azaz", 23, "34", "afjal"]

def iterateitem(x):
    item = []
    for items in x:
        if str(items).isnumeric():
            item.append(items)
    return item

iterateitem(x)
