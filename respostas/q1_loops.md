A. Java:

int k = (j + 13) / 27;
while (k <= 10) {
    k = k + 1;
    int i = 3 * k - 1;
}

B. Python

k = (j + 13) // 27
while k <= 10:
    k += 1
    i = 3 * k - 1

C. Haskell

let loop k = if k > 10 then k else loop (k + 1)

D. Switch

var k = (j + 13) / 27
while k <= 10 {
    k += 1
    let i = 3 * k - 1
}
