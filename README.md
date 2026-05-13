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
