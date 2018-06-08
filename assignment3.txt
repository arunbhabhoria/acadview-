#Q1. Take input in list by user
a = input()
s = list(a.split())

#Q2. Add the following list to above created list
b = ['google','apple','facebook','microsoft','tesla']
s.extend(b)
print (s)

#Q3. Count frequency of objects in the list
print(s.count('4'))

#Q4. Create a list with numbers and sort it in ascending order
x = [1, 7, 4, 2, 0]
x.sort()

#Q5. Merge two arrays
list1 = [1, 2, 3, 4, 5, 6]
list2 = [-1, -2, -3, -4, -5, -6]
list1.sort()
list2.sort()
list3 = list1 + list2
list3.sort()

#Q6. Implement stack and queue with lists

#I. STACKS USING LIST
stack = ["Saurav", "Verma"]
stack.append("Arun")
stack.append("Praveen")
print(stack)
print(stack.pop())
print(stack)
print(stack.pop())
print(stack)

#II. QUEUES USING LIST
from collections import deque
queue = deque(["Dehradun", "Varanasi", "Nainital", "Bilaspur"])
print(queue)
queue.append("Chandigarh")
print(queue)
queue.append("New Delhi")
print(queue)
print(queue.pop())                 
print(queue.pop())
print(queue)
print(queue.popleft())
print(queue.popleft())
print(queue)

#Q7. Count odd and even numbers in the list
count_odd = 0
count_even = 0
print(list3)
for x in list3:
        if not x % 2:
    	     count_even+=1
        else:
    	     count_odd+=1
print("Total even numbers : "'%d'%count_even)
print("Total odd numbers : "'%d'%count_odd)
