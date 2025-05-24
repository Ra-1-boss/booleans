# booleans
# Boolean basics in Python
is_active = True  # Direct assignment
is_closed = False
x, y = 10, 5

# Comparisons
is_greater = x > y  # True
is_equal = x == y   # False

# Logical operations
can_proceed = is_active and not is_closed  # True
has_data = [1, 2] or []  # Truthy list [1, 2]

# Control flow with truthy/falsey
data = [] if is_equal else ["result"]  # Falsey condition -> ["result"]

# Chained comparison
is_in_range = 3 < x < 15  # True

# Output
print(f"Greater: {is_greater}, Can Proceed: {can_proceed}, Data: {has_data}, In Range: {is_in_range}")
# Output: Greater: True, Can Proceed: True, Data: [1, 2], In Range: True
