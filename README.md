# Nearly-Sorted-Algorithm
Python Programming

for i in range(int(input())):
    x=[int(x) for x in input().split(" ")]
    print(*sorted(list(map(int,input().strip().split(" ")))))
