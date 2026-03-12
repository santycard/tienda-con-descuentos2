[ANALISIS DEL PROBLEMA.docx](https://github.com/user-attachments/files/25936407/ANALISIS.DEL.PROBLEMA.docx)
print("hola, soy una ayuda para ti")
#inicio
precio_original=float(input("digita el precio original"))
descuento_10= 0.10
descuento_20= 0.20
#calculos del descuento
ahorro_10= precio_original*descuento_10
ahorro_20= precio_original*descuento_20
precio_final_10=precio_original-ahorro_10
precio_final_20=precio_original-ahorro_20
#resultados
print("-"* 30)
print(f"precio original:${precio_original}")
print(f"precio con el 10% de descuento:$ {precio_final_10}")
print(f"precio con el 20% de descuento:${precio_final_20}")
