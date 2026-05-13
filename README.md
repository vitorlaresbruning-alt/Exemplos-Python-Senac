# Sistema de Notas em Python

Este projeto foi desenvolvido em Python para classificar a nota de um aluno de acordo com seu desempenho.

## Funcionalidade

O programa solicita uma nota ao usuário e retorna o conceito correspondente:

- A → Excelente
- B → Muito bom
- C → Bom
- D → Regular
- F → Reprovado

## Código

```python
nota = int(input('Digite a nota do aluno: '))

if nota >= 90:
    print('A - Excelente')
elif nota >= 80:
    print('B - Muito bom')
elif nota >= 70:
    print('C - Bom')
elif nota >= 60:
    print('D - Regular')
else:
    print('F - Reprovado')
```

## Como executar

1. Instale o Python.
2. Abra o terminal.
3. Execute o arquivo:

```bash
python nome_do_arquivo.py
```

## Tecnologias utilizadas

- Python
- Visual Studio Code



# Aula de Informática - Programação Python

## Informações

- **Aluno:** Victor Hugo  
- **Professor:** Dieimes Nunes  

## Sobre o projeto

Este programa em Python solicita a nota de um aluno e mostra o conceito correspondente.

## Conceitos

- A → Excelente
- B → Muito bom
- C → Bom
- D → Regular
- F → Reprovado

## Código

```python
nota = int(input('Digite a nota do aluno: '))

if nota >= 90:
    print('A - Excelente')
elif nota >= 80:
    print('B - Muito bom')
elif nota >= 70:
    print('C - Bom')
elif nota >= 60:
    print('D - Regular')
else:
    print('F - Reprovado')
```

## Como executar

```bash
python nome_do_arquivo.py
```


# Aula de Informática - Programação Python

## Informações

- **Aluno:** Victor Hugo  
- **Professor:** Dieimes Nunes  

## Sobre o projeto

Este programa em Python verifica se existe curso à tarde.  
Se houver curso, o programa informa que o usuário não vai.  
Caso contrário, informa que ele vai.

## Código

```python
curso_a_tarde = input("Tem curso à tarde? (sim/não): ").strip().lower()

if curso_a_tarde == "sim":
    print("Então não vou.")
else:
    print("Então eu vou.")
```

## Como executar

1. Instale o Python.
2. Abra o terminal na pasta do projeto.
3. Execute:

```bash
python nome_do_arquivo.py
```

## Exemplo de uso

```text
Tem curso à tarde? (sim/não): sim
Então não vou.
```

## Tecnologias utilizadas

- Python
- Visual Studio Code
