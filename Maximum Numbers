def find_max(node):
    if node is None:
        return float('-inf')
    left_max = find_max(node.left)
    right_max = find_max(node.right)
    return max(node.value, left_max, right_max)

# Test the max value function
print("\nMaximum value in the tree:", find_max(root))
