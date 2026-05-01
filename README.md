# struktur-data-linear
Algoritma (MODUL 2)


data = [10,20,30,40]

print(data[0])

data.append(50)

data.remove(20)

print(data)


class Node:
    def __init__(self, data):
        self.data = data
        self.next = None

n1 = Node(10)
n2 = Node(20)

n1.next = n2

print(n1.data)
print(n1.next.data)


stack = []

stack.append(10)
stack.append(20)

stack.pop()

print(stack)


from collections import deque
queue = deque()

queue.append(10)
queue.append(20)

queue.popleft()

print(queue)
