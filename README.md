# Programação Orientada a Objeto

## Introdução
oiee, boa tarde! vou apresentar o trabalho que fiz referente à Programação Orientada a Objetos.
Antes, vou explicar o que os códigos significam.

## Explicação do Código:
def __init__(self,modelo) - __init__ é um método especial chamado automaticamente quando você cria um novo objeto da classe.

self representa a própria instância do objeto (é obrigatório como primeiro parâmetro nos métodos de instância).

modelo é um parâmetro que você pode passar ao criar o objeto, para inicializar um atributo.


print(f"{self._modelo} <comentário>") - f"..." cria uma f-string, que permite inserir variáveis e expressões dentro de {}.


self._modelo é um atributo da instância (por isso o self).

O texto que não está entre {} será impresso literalmente.

f"..." cria uma f-string, que permite inserir variáveis e expressões dentro de {}.

self._modelo é um atributo da instância (por isso o self).

O texto que não está entre {} será impresso literalmente.

## Meu Código
Agora, vou mostrar o código que fiz.

#  O Primeiro código que fiz

1.  class Aviao:
   2. def __init__(self,modelo):
      3.  self._modelo=modelo
       4. self.velocidade=0

 5.  def acelerar(self):
  print(f"{self._modelo} está acelerando")

 6.  def frear(self):
  print(f"{self._modelo} está freando")
  
7.   def voar(self):
  print(f"{self._modelo} está voando")
  

# O segundo código que fiz  

 1. class Freezer:
  2. def __init__(self,modelo):
   3.     self._modelo=modelo
     4.   self.temperatura=-25

 5.  def gelar(self):
  print(f"{self._modelo} está gelando")

  6. def congelar(self):
  print(f"{self._modelo} está congelando")

   7.  def descongelar(self):
     print(f"{self._modelo} está descongelando")  

# O terceiro código que fiz  

 1. class Telefone:
 2.  def __init__(self,modelo):
 3.       self._modelo=modelo
 4.       self.telefonema=0

 5.  def tocar(self):
  print(f"{self._modelo} está tocando")

 6.  def chamada(self):
  print(f"{self._modelo} está chamando")

 7.  def emitir (self):
  print(f"{self._modelo} está emitindo a voz")
    
  
  # Encerramento
  Essa foi minha apresentação, espero que tenham gostado!!
