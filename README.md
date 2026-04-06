# M-dia-de-nota-de-alunos
Projeto simples de calcular nota média de alunos
print('-='*50)
nome = str(input('Digite o nome do aluno:'))
n1 = float(input('Digite a primeira nota:'))
no2 = float(input('digite a segunda nota:'))
m = (n1 + no2)/2
print('sua Média é: {}!' .format(m))
if m >= 7:
    print('aprovado, Parábens!')
elif m < 7 and m >= 4:
    print('Recuperação!')
else:
    print('Reprovado!')
print('-=' * 50)
