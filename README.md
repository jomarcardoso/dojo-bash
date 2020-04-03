# dojo-bash

Bem básico

## Princípios

#### Abrir outro bash

Cria uma nova instância com um novo escopo, sem acesso as variáveis locais do outro bash.

```bash
bash
```

## Variáveis

Locais e globais

### Globais

#### mostrar todas as variáveis globais

```bash
env
```

ou

```bash
printenv
```

#### Mostrar uma variável global específica

```bash
printenv nome_da_variável
```

### Locais

#### declarar uma variável

```bash
nome_da_variável=valor_da_variável
```

**obs:** ver tipos de variáveis

#### usar o valor de uma variável

Para usar uma variável é preciso colocar o "$" antes para dizer que é uma variável e não um texto.

```bash
echo $nome_da_variável
```

**Obs:** `echo` é o comando de print

#### Tornar uma variável local global

```bash
export nome_da_variável
```

## Array

### Criar um array

colocar o conteúdo dentro de parênteses com espaços entre os elementos

```bash
nome_da_variável=(laranja morando uva)
```

### Acessar o array

**todos os elementos**
```bash
echo ${nome_da_variável[*]}
```

**primeiro elemento**
```bash
echo ${nome_da_variável[0]}
```

### Mudar valor do elemento

```bash
nome_da_variável[index]=novo_valor
```

### Remover elemento

```
unset nome_da_variável[index]
```

### Adicionar elemento

```
nome_da_variável[tamanho_do_array]=novo_elemento
```

https://www.youtube.com/watch?v=cru9166Gfss
