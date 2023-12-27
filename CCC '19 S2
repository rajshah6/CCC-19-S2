def prime(n):
    for i in range(2, int(n**0.5)+1):
        if n % i == 0:
            return False
    return True

n = int(input())

for _ in range(n):
    N = int(input())
    for i in range(2, 2*N-1):
        if prime(i) and prime(2*N-i):
            print(i, 2*N-i)
            break
