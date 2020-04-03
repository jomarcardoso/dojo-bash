# dojo-bash

Bem básico

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

