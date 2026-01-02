# studyflow-mvp
6.7. Entregable modelo (ejemplo): sistema de operaciones de StudyFlow
Proyecto: StudyFlow
Qué es: plataforma digital para organizar el estudio (tareas, calendarios, recordatorios y seguimiento de hábitos) con suscripción mensual.
Propuesta de valor: ayudar a estudiantes a estudiar mejor con un sistema simple, visual y con seguimiento.
________________________________________
Bloque 1. Proceso productivo (inputs → transformación → output)
Inputs (recursos de partida)
•	Equipo humano: 1 persona de desarrollo + 1 persona para atención al cliente (al inicio, parcial).
•	Tecnología: ordenadores, internet, herramientas de desarrollo, servidor en la nube.
•	Conocimiento/tiempo: programación, diseño de experiencia de usuario, pruebas, mejora continua.
•	Datos: feedback de usuarios, métricas de uso (funciones más utilizadas, errores).
Transformación (actividades clave)
•	Diseño y mejora de la app (interfaz, funciones, usabilidad).
•	Programación e implementación de cambios.
•	Pruebas internas antes de publicar actualizaciones.
•	Soporte al usuario y resolución de incidencias.
•	Actualización del contenido (tutoriales, guías, FAQs).
Output (lo que recibe el cliente)
•	Acceso a la plataforma (app/web) con funciones de planificación y seguimiento.
•	Servicio de atención básica y corrección de errores.
•	Actualizaciones periódicas que mejoran la experiencia.
________________________________________
Bloque 2. Aprovisionamiento y proveedores
En StudyFlow no hay materias primas físicas. El aprovisionamiento se centra en servicios digitales necesarios para operar.
Recursos críticos y proveedores principales
1.	Alojamiento/servidor en la nube (ej. proveedor tipo AWS, Google Cloud, OVH…)
o	Necesidad: mantener la plataforma accesible y rápida.
2.	Herramientas de desarrollo (repositorio, control de versiones, entorno de trabajo)
o	Necesidad: programar, colaborar y desplegar actualizaciones.
3.	Pasarela de pago (Stripe, PayPal…)
o	Necesidad: cobrar suscripciones de forma segura.
4.	Herramientas de comunicación (email de soporte, sistema de tickets)
o	Necesidad: responder incidencias y mantener confianza.
Criterios para elegir proveedor
•	Fiabilidad (menos caídas, soporte técnico eficaz).
•	Escalabilidad (poder aumentar recursos cuando crece el número de usuarios).
•	Coste controlado (empezar con planes básicos y subir solo cuando sea necesario).
•	Seguridad y cumplimiento (pagos y datos personales).
Riesgo principal
Dependencia de un proveedor clave (servidor o pasarela de pago).
Si falla, StudyFlow no puede operar o no puede cobrar.
Medida de prevención
•	Copias de seguridad programadas.
•	Opción de migración a otro proveedor.
•	Plan de contingencia: aviso rápido al usuario + canal alternativo de soporte.
________________________________________
Bloque 3. Inventario o capacidad operativa (stock/capacidad)
En StudyFlow el “stock” no son productos físicos, sino capacidad digital y capacidad humana.
Qué se considera stock/capacidad
•	Capacidad del servidor (usuarios simultáneos, almacenamiento, velocidad).
•	Capacidad del equipo de soporte (número de incidencias atendibles al día).
Decisión de capacidad inicial
•	Servidor con plan básico capaz de soportar un número moderado de usuarios.
•	Atención al cliente en horario reducido (por ejemplo, 2 horas al día al inicio).
Stock de seguridad (adaptado a digital)
•	Mantener margen de capacidad del servidor (no ir al límite).
•	Ejemplo: si el servidor funciona cómodo hasta X usuarios simultáneos, operar normalmente por debajo de ese límite para absorber picos.
Punto de pedido / disparador de ampliación (adaptado a digital)
No se pide mercancía, pero sí se “activa” la ampliación de recursos cuando se alcanza un umbral.
•	Ejemplo: si el uso medio supera un % del límite del servidor durante varios días, se sube el plan o se añade capacidad.
Qué ocurre si sube la demanda de forma inesperada
•	Si el servidor se satura: la app va lenta, se cae, los usuarios se frustran y se dan de baja.
•	Si el soporte se satura: las incidencias tardan, se pierde confianza y se dañan valoraciones.
Consecuencia económica
Una caída del servicio o mala atención puede provocar:
•	bajas de suscripción,
•	devoluciones,
•	pérdida de reputación (y menos clientes futuros).
________________________________________
Bloque 4. Prototipo y aprendizaje (técnica aplicada)
Tipo de prototipo elegido: MVP (mínimo producto viable) + prototipo digital.
Qué se quiere comprobar
•	Si el usuario entiende la interfaz sin explicación.
•	Si las funciones clave (tareas, calendario, recordatorios) realmente se usan.
•	Si la propuesta de valor es clara: “me ayuda a estudiar mejor”.
Cómo se implementa (evidencia mínima)
•	MVP con: crear tarea, plan semanal, recordatorio básico, estadísticas simples.
•	Prueba piloto con 10 estudiantes durante 7 días.
•	Registro de feedback con 3 preguntas:
1.	¿Qué función usaste más?
2.	¿Qué te resultó confuso?
3.	¿Qué cambiarías para usarla cada día?
Decisión tras el prototipo
•	Mantener solo funciones más usadas y simplificar el resto.
•	Mejorar la pantalla inicial si genera confusión.
•	Ajustar recordatorios si se consideran molestos.
________________________________________
Bloque 5. Decisión operativa clave (justificada)
Decisión: empezar con capacidad ajustada + escalabilidad, no con infraestructura grande desde el inicio.
Alternativa descartada
Contratar desde el principio un servidor potente y soporte completo “por si acaso”.
Por qué se descarta
•	Incrementa costes fijos antes de tener ingresos estables.
•	En una fase inicial, no se sabe aún si el producto encaja con el usuario.
Coste/riesgo de la decisión tomada
•	Riesgo de saturación si hay un pico de usuarios.
•	Si ocurre, afecta a experiencia y reputación.
Cómo se compensa el riesgo
•	Monitorización básica (métricas de carga y uso).
•	Umbral claro de ampliación (disparador).
•	Comunicación con el usuario si hay incidencias.
Qué pasa si no se alcanzan las ventas previstas
•	Con infraestructura mínima, el proyecto no se hunde por costes fijos altos.
•	Permite aguantar más tiempo, mejorar el producto con feedback y reajustar el modelo antes de abandonar.
________________________________________
Conclusión operativa (2–3 líneas)
StudyFlow funciona como un sistema de operaciones digital donde el valor se crea mediante desarrollo, soporte y mejora continua. La clave es mantener la capacidad suficiente para no fallar al usuario, pero sin sobredimensionar costes. El prototipado (MVP) permite aprender rápido y tomar decisiones con menos riesgo.
