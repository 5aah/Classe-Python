class Pessoa:
  def __init__(self, nome, idade, sobrenome, profissao):
    self.nome = nome
    self.idade = idade
    self.sobrenome = sobrenome
    self.profissao = profissao

Pessoa1 = Pessoa('Sarah', 16, 'Santana', 'Estudante')

Pessoa2 = Pessoa('Nilson', 47, 'Alcides', 'Professor')

print(f'Nome completo: {Pessoa1.nome} {Pessoa1.sobrenome}')
print(f'Idade: {Pessoa1.idade}')
print(f'Profissão: {Pessoa1.profissao}')

print()

print(f'Nome completo: {Pessoa2.nome} {Pessoa2.sobrenome}')
print(f'Idade: {Pessoa2.idade}')
print(f'Profissão: {Pessoa2.profissao}')
