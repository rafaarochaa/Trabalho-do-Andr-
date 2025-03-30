# Trabalho-do-André-
programação de coisas e objetos:
 
class Carro:
    def _init_(self, marca, modelo, ano):
        self.marca = marca
        self.modelo = modelo
        self.ano = ano

    def exibir_info(self):
        print(f"Carro: {self.marca} {self.modelo}, Ano: {self.ano}")

# Criando um objeto da classe Carro
meu_carro = Carro("Toyota", "Corolla", 2022)

# Invocando o método do objeto
print(meu_carro.exibir_info())
