def xor_gate(x1, x2):
    return x1 ^ x2  # XOR operation
test_inputs = [
    [0, 1],
    [0, 1],
    [0, 0],
    [1, 1]
]
print("XOR Problem Test Case Results:")
for x in test_inputs:
    output = xor_gate(x[0], x[1])
    print(f"Input: {x} => Output: {output}")

    output:
    XOR Problem Test Case Results:
Input: [0, 1] => Output: 1
Input: [0, 1] => Output: 1
Input: [0, 0] => Output: 0
Input: [1, 1] => Output: 0
