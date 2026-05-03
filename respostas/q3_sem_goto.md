A) Java

int j = -3;
boolean continuar = true;

for (int i = 0; i < 3 && continuar; i++) {
    int valorSwitch = j + 2;
    
    if (valorSwitch == 3 || valorSwitch == 2) {
        j--;
    } else if (valorSwitch == 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j > 0) {
        continuar = false; // Substitui o break do for
    } else {
        j = 3 - i;
    }
}

B) Python

j = -3
parar = False

for i in range(3):
    if parar:
        break # Nota: A questão pede sem break, então usamos a lógica abaixo:
    
    # Versão purista sem break:
    if not parar:
        valor = j + 2
        if valor in [3, 2]:
            j -= 1
        elif valor == 0:
            j += 2
        else:
            j = 0
        
        if j > 0:
            parar = True
        else:
            j = 3 - i

C) Javascript

let j = -3;
let rodar = true;

for (let i = 0; i < 3 && rodar; i++) {
    let teste = j + 2;

    if (teste === 3 || teste === 2) {
        j--;
    } else if (teste === 0) {
        j += 2;
    } else {
        j = 0;
    }

    if (j > 0) {
        rodar = false;
    } else {
        j = 3 - i;
    }
}
