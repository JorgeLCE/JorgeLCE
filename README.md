- 👋 Hi, I’m @JorgeLCE
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
JorgeLCE/JorgeLCE is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class Producto:
    def __init__(self, nombre, precio, cantidad):
        self.nombre = nombre
        self.precio = precio
        self.cantidad = cantidad


class Factura:
    def __init__(self, cliente):
        self.cliente = cliente
        self.productos = []

    def agregar_producto(self, producto):
        self.productos.append(producto)

    def calcular_total(self):
        total = 0
        for producto in self.productos:
            total += producto.precio * producto.cantidad
        return total

    def generar_factura(self):
        print("Factura para:", self.cliente)
        print("-----------------------------")
        for producto in self.productos:
            print(producto.nombre, "\t$", producto.precio, "\tCantidad:", producto.cantidad)
        print("-----------------------------")
        print("Total: $", self.calcular_total())


# Ejemplo de uso
cliente = "Juan Pérez"
factura = Factura(cliente)

producto1 = Producto("Camisa", 25, 2)
producto2 = Producto("Pantalón", 40, 1)

factura.agregar_producto(producto1)
factura.agregar_producto(producto2)

factura.generar_factura()![Aretes de acero color negro](https://github.com/JorgeLCE/JorgeLCE/assets/137324241/9b5f5480-ac20-4d37-9176-d6096aedf9e1)

![Conjunto de letra D](https://github.com/JorgeLCE/JorgeLCE/assets/137324241/c8833461-a174-495d-b468-622103892cc5)
