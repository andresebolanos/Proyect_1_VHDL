# Proyecto 1 - VHDL

Este repositorio contiene el **Proyecto 1 de VHDL**, implementado en **Quartus II** para la simulación y síntesis en FPGA.  
El objetivo principal es diseñar y simular una **máquina expendedora** con diferentes módulos: control de monedas, inventario, contador general y visualización en displays de 7 segmentos.

---

## 📂 Contenido del repositorio

- **Proyect_1.7z** → Archivo comprimido con el proyecto completo listo para abrir en Quartus.
- **monedasdiagram.png** → Diagrama del módulo de monedas.
- **almacen.png** → Diagrama del módulo de inventario.
- **contador_general_diagram.png** → Diagrama del contador general (control del tiempo/LEDs).
- **diagrama-complete.png** → Diagrama de bloques del sistema completo.
- **component_credito.png** → Diagrama de bloques del credito

---

## ⚙️ Descripción de los módulos

- **Monedas**  
  Gestiona el ingreso de monedas (500 y 1000) y acumula el saldo disponible.

- **Inventario**  
  Verifica la disponibilidad del producto y entrega el precio del producto.

- **Reloj / Contador general**  
  Controla el tiempo de entrega y genera parpadeo en el LED rojo.

- **Decodificador BCD (Decoin_bcd)**  
  Convierte el saldo/vuelto en salidas para los displays de 7 segmentos.

- **Credito**
  Verifica si es posible la compra y la realiza, además de inicializar el contador general.
  

---

## ▶️ Cómo usarlo

1.Descarga este repositorio.

2.Descomprime Proyect_1.7z.

3.Encontraras 2 carpetas: componentes y maquina_expendedora.

4.Abre la carpeta maquina expendedora ahí encontraras el proyecto completo, si quieres observar los componentes abre componentes.

4.Compila y sintetiza.
