# 📋 CASO 1 - La planta esta produciendo yogurt de fresa

### Lo que ya se tiene

- Sensores
- PLC
- SCADA
- Alarmas
- Variables del proceso

### El jefe de produccion pregunta:

Se producen 7000/dia envases de 150 g.

1. **Cuantas unidades buenas producimos?** 6800 envases
2. **Cuantas fueron rechazadas y por que?** 200 por fallas de empaquetamiento, calidad del envase
3. **Que lote se fabrica y con que materias primas?** Lote: . Materias primas: Leche, leche en polvo, pulpa, azucar, cultivo y estabilizante
4. **Cuanto tiempo estuvo detenida la linea y por que?** 
5. **Cumplimos la orden de produccion?**
6. **Cual fue el OEE?**

#### OEE

OEE = Disponibilidad x Rendimiento x Calidad.

Disponibilidad = Tiempo de Funcionamiento / Tiempo de Producción Planificado

Tiempo de Funcionamiento = Tiempo de Producción Planificado - Tiempo de Parada

Rendimiento = (Tiempo de Ciclo Ideal × Total de piezas) / Tiempo de Funcionamiento

Pregunta clave: **PLC+SCADA son suficientes para responder todo de manera integrada?**

Todo esto es tener claro el MES