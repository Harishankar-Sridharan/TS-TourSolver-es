# 13. ¿Por qué tengo tiempo de espera en mi plan de ruta?

El algoritmo de optimización puede introducir tiempo de espera por estas razones:

1. El repartidor llega a la ubicación del cliente **antes del horario de apertura**.
2. El repartidor llega al depósito **antes de que esté operativo**.

Los horarios de apertura de clientes y depósitos son restricciones estrictas con alta prioridad, por lo que el algoritmo debe respetarlos.

**Consejo:** Para reducir el tiempo de espera innecesario, use la **Restricción de Inicio Automático** Esta función ajusta la hora de salida para que el repartidor comience más tarde y llegue al cliente o al depósito en el momento adecuado, minimizando los períodos de inactividad en ubicaciones desconocidas.
