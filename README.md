# DSA_notes
notes for dsa preprations


### string manipulation

```bash
        hourToMinute = int(time[:2]) * 60
        minute = int(time[3:])

gcdOfStrings(str1[len(str2):], str2)

word = list(s) converting word into list
return  " ".join(word) #to join the words

lent(string) #to get the length of specific string.

        # Reverse the list of words
        reversed_words = words[::-1]
```

### Linked list

```bash
    head = ListNode() #to intilize a code
    dummy = ListNode(None)

    current.next = ListNode(total % 10) #to create a node

for loop
   for r in range(len(s)):

dict
   
seen = { } #empty dict

functions

            return self.gcdOfStrings(str2, str1) # calling function in same object

dummy = slow = fast = ListNode(-math.inf)
```

### Lists

```bash
result = [ ] to start a list

[0] * len(nums)
```
numbers

```bash
math.inf (to the infinity sequence)
float('inf')

 sum(nums[:k])

for list_idx, node in enumerate(lists):
        
```

### hashmaps

```bash
freq = {}
freq[x] = freq.get(x,0) + 1


len(freq) == len(set(freq.values()))



```

### matrix

```bash
col = tuple(grid[i][c] for i in range(n))
row = tuple(grid[r])
```


### stack

```bash
    ans=[]
    ans.pop()
    ans+=[i]
    "".join(ans)


    stack = []
    stack.pop()

```

### queue

```bash
self.q = deque()
q = collections.deque()

        while q:
            level_sum = 0
            size = len(q)
            for _ in range(size):

self.q.append(t)

self.q[0] > 3000

self.q.popleft()


r_positions = deque([i for i, s in enumerate(senate) if s == 'R'])
d_positions = deque([i for i, s in enumerate(senate) if s == 'D'])
```


### priorityqueue

```bash

import heapq

        h = [(head.val, idx, head) for idx, head in enumerate(lists) if head is not None]

val, idx, node = heapq.heappop(h)

heapq.heappush(h, (last.next.val, idx, last.next))
```