# Atividade em Grupo-2

## Integrantes do Grupo: Fran, Aline Melissa, Amanda Santos, Daylane Maria, Gabriel Henrique, Inglide, Karlessandra Lima.

## Atividades do dia 16/09

### Neste desafio vocês terão 2hs para resolverem dois problemas de lógica. O primeiro envolve a construção da Tabuada de 1 a 10 conforme imagem abaixo. O resultado deve ser exibido no console do terminal do editor VSCode. Tabuada é o problema 1.


### ** Resultado**

```git
    for (let contador: number = 0; contador <= 10; contador++) {
        for (let x: number = 0; x <= 10; x++) {
            if (contador <= 10) {
                console.log(`${contador} X ${x} = ${contador * x}`);
            }
        }
        console.log("-------------------------------")
    }

```
### Problema 2. 
### Monte as expressões regulares para os documentos abaixo:
```
    CEP: 01311-100
    EMAIL: email@fiap.com.br
    CPF: 333.111.222-00
    CNPJ: 12.321.123/0001-02
    RG: 22.455.213-2
```

### Crie uma expressão regular onde o formato 123.456.abc.def seja válido, porém 2123.456.abc.def também pode ser válido.

### ** Resultado**
```

// /^[0-9]{5}\-[0-9]{3}$/  // CEP

// /^[a-z0-9.]+@[a-z0-9]+\.[a-z]+\.([a-z]+)?$/i; // EMAIL

// /^[0-9]{3}\.[0-9]{3}\.[0-9]{3}\-[0-9]{2}$/; //CPF

// /^[0-9]{2}\.[0-9]{3}\.[0-9]{3}\/[0-9]{4}\-[0-9]{2}$/ // CNPJ

// /^[a-z0-9]{1,2})\.([0-9]{3})\.([0-9]{3})\-([0-9]{1} $/i  // RG

// /^[0-9]{3,4}?\.[0-9]{3}\.[a-z]{3}\.[a-z]{3} $/i

```
