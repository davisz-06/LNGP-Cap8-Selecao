1) C++

int n = 100, sum = 0;
for (int i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

2) Go (Golang)

n := 100
sum := 0
for i, j := 0, 17; i < n; i, j = i+1, j-1 {
    sum += i * j + 3
}

3) Javascript

let n = 100, sum = 0;
for (let i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

4) C#

int n = 100, sum = 0;
for (int i = 0, j = 17; i < n; i++, j--) {
    sum += i * j + 3;
}

5) Python

n = 100
sum_val = 0
# i vai de 0 a 99, j começa em 17 e diminui
for i, j in zip(range(n), range(17, 17 - n, -1)):
    sum_val += i * j + 3
