# 14. ¿Cómo puedo priorizar ciertos intervalos de tiempo?

A veces, la experiencia del cliente tiene prioridad sobre la reducción de kilómetros o las emisiones de CO₂. Por ejemplo, los clientes premium pueden requerir entregas en horarios específicos para garantizar su satisfacción, incluso si esto resulta en rutas más largas.

Para imponer estos intervalos de tiempo prioritarios en **TourSolver**, use el **intervalo fijo** como restricción. Esto bloquea el intervalo de tiempo especificado para el cliente, asegurando que reciba su entrega en el horario deseado.\
**Nota:** Usar Intervalo Fijo reduce la flexibilidad del algoritmo de optimización, ya que limita las permutaciones de rutas. Sin embargo, garantiza que los clientes premium sean atendidos en el momento adecuado.
