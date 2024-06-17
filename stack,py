class Stack:
    def __init__(self):
        self.items = []

    def is_empty(self):
        return len(self.items) == 0

    def push(self, item):
        self.items.append(item)

    def pop(self):
        if self.is_empty():
            return None
        return self.items.pop()

    def peek(self):
        if self.is_empty():
            return None
        return self.items[-1]

    def size(self):
        return len(self.items)

    def __str__(self):
        return str(self.items)

# Example usage
if __name__ == "__main__":
    stack = Stack()
    print("Stack created:", stack)

    stack.push(1)
    stack.push(2)
    stack.push(3)
    print("Stack after pushing 1, 2, 3:", stack)

    print("Peek top item:", stack.peek())
    print("Stack size:", stack.size())

    print("Pop item:", stack.pop())
    print("Stack after pop:", stack)

    print("Is stack empty?", stack.is_empty())

    stack.pop()
    stack.pop()
    print("Stack after popping all items:", stack)
    print("Is stack empty?", stack.is_empty())
