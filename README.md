import math

# Este programa calcula a área de um círculo com base no seu raio.

def calcular_area_circulo(raio):
  """
  Calcula a área de um círculo.

  Argumentos:
  raio -- o raio do círculo (float)

  Retorna:
  A área do círculo (float)
  """
  if raio < 0:
    return "O raio não pode ser um valor negativo."
  else:
    area = math.pi * (raio ** 2)
    return area

# Exemplo de uso:
raio_do_circulo = 5
area_calculada = calcular_area_circulo(raio_do_circulo)

print(f"O raio do círculo é: {raio_do_circulo}")
print(f"A área do círculo é: {area_calculada}")
