# Learning-log
# 1. Estructura de una función
def nombre(hueco1, hueco2=valor_por_defecto):
    return calculo_usando_hueco1_y_hueco2

nombre(5)        # usa el valor por defecto para hueco2
nombre(5, 10)    # hueco2 = 10

# 2. Redondear
round(x, 2)    # 2 decimales       → 3.14
round(x, -3)   # a miles           → 338000

# 3. Operaciones
a + b    # sumar
a - b    # restar
a * b    # multiplicar
a / b    # dividir
a % b    # resto de dividir (lo que sobra) → 91 % 3 = 1
a ** 2   # al cuadrado

# 4. Paréntesis = se hace primero
(a + b + c) / 3   # media ✅
