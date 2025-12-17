# Devfest2025



##NVIDIA NEMO 

# NVIDIA NIM: Optimized AI Models Run up to 5x faster.


# NVIDIA provides the building blocks for agentic AI.

- [NVIDIA Blueprints](https://github.com/NVIDIA-AI-Blueprints/rag?tab=readme-ov-file)

---

# GOOGLE CLOUD - Arquitectura para desarrollo.
Startup venta de boletos.

- **Escalado vertical** En caso de saturación.
- **Escalado hotizontal** A que estancia conecta a cada usuario.
- **Balnceador de carga**
  - Distribuir el tráfico de forma inteligente-
  - Detectar instancias sanas y enfermas
  - trabajar con el auto scaling
  - ser el punto estable del sistema.
 
- El autoescalado es la capacidad de un sistema para ajustar automaticamente el númer de instancias según la carga.

- El balancedor recibe todo el tráfico.
- El autoescalado observa métricas (CPU,requests, latencia)
- cuando hay picos, nacen instancias.
- cuando bajan, mueren instancias.

## El problema de la velocidad.
-

## Cache y CDNs
- CDN evita que el request llegue al backend.
- Cache evita que el backend llegue a la base de datos.

Lecturas rápidas para todos.

**CDN**
Sirve contenido desde el punto más cercano al usuario.
- imagenes del evento.

**CACHE**
Es guardar datos en memoria para no calcularlos o consultarlos cada vez.
- información del evento
- precios
- disponibilidad aproximada de asientos.

## Cuandoun cambio mata todo
- actualización de redondeo de números.

## Microservicios
Microservicios es dividirr el sistema en servicios pequeños, cada uno dueño de una responsabilidad y su propio ritmo de escalado.



## Ejemplo - Evento

**Mundial de futbol**
- problema de saturación.
- Los servicios escalan, pero la base de datos no.
- Celebrity Problem

  -**Celebrity Proble**

BD disitribuida/sharing
Es dividir una base de datos grande en varias más pequeñas para repartir la carga.
Cada fragmento (shard) guarda solo una parte de los datos.

*No todos los datos necesitan vivir juntospara funcionar*

## El


## Cola(queue)

La cola desacopla lo que recibes de lo que puedes procesar.
1. Aceptas rápido
2. Procesas después
3. Respetar el limite del tercero.

Una cola es un mecanismo de control de flujo.

 **El día en quepapaypal cayó**

 - Dependencia externa falla
 - tolerancia a fallos
 - reintentos inteligentes
 - ningun usuario pierde su compra

## Manejor de errores.
Un punto unico de fallo es un componente que si falla, detene o degrada fuertemente todo el rpoceso.

## Tolerancia al fallo.

Mensaje de esto,

1. No todo es código también son estrategias.
2. Divide y venceras.
3. Piensa en que todo puede fallar.


## EJERCICIO.
Sabrina carpenter anuncia concierto.
[En fotos]

Google cloud Services

---

# Aprende a prototipar en segundos.

**Firebase studio**
[Farebase studio](https://firebase.studio/)

Es un entorno de desarrollo 

**¿Qué  puedes hacer en firebase studio?**

## Prototyper.

**¿Qué se necesita saber?**
- Prompt Engineering.

## Interfaz
<img width="685" height="432" alt="image" src="https://github.com/user-attachments/assets/b3427ea2-586f-428e-a78a-b4c311ab9aaa" />

<img width="596" height="342" alt="image" src="https://github.com/user-attachments/assets/463d86ae-54e7-4d5f-bb36-49cbda45f4be" />

---

# El triangulo de progress entre 

La dimensión del potencia
- Google Cloud
- Google Cloud platform
- Google Clooud skills

---

# WEB PERFORMANCE (Workshop)

- Aprender sobre web performance
- Conocer los core web vitals.
- Analizar una escena del crimen... we.
- Desarrollo end to end con Gemini.

  **¿Qué es el web performance?**
  La interacción de un usuario con una página.
  Es la medida de que tan rápido carga una página y que tan fluida es la respuesta al usuario.

  *Un usuario abandona un sitio 32% si la página carga de 1 a 3seg.*

## 4 impactos del mal performance.

- Pierdes dinero.
- Google te esconde.
- Pagas más por publicidad.
- Generas desconfianza.

## ¿Cómo mejora el performance de nuestra web?"**

  **Core Web Vitals**
  Nos ayudan a medir que tan buena es una página.

  Por ejemplo: [Core Web Vitals report](https://support.google.com/webmasters/answer/9205520?hl=en)

  - **LPC(Largest Contenful Paint)**
Marca el momento exacto en el que el elemento de contenido más grande (generalmente una imagenprincipal, un video oun bloque de texto grande) se vuelve invisible al usuario.

  - **INP(Interaction to Next Paint)**
Mide la responsividad o capacidad de respuesta. Mide cuánto tiempo pasa desde que el usuario interactúa (hace clic, toca la pantalla o presiona una tecla) hasta que el navegador sea capaz de pintar la última imagen.

  - **CLS( Cumulative Layout Shift)**
Marca el momento exacto  en el que el elemento contenido más grande (generalmente una imagen principal, un video o un bloque de texto grande) se vuelve visible         dentro de la pantalla.

## Caso de estudio.

Iniciar el modo incognito de chrome.

abrir página BBVA e inspeccionar la página.  
<img width="1365" height="725" alt="image" src="https://github.com/user-attachments/assets/2cc82ec7-024f-4297-a154-cf3260667e64" />

Cambiar la velocidad y recargar la página. 
<img width="1366" height="725" alt="image" src="https://github.com/user-attachments/assets/6c21f00c-34b5-437a-9a8f-0f821bee4926" />

 **Metricas (performance)**
 <img width="1366" height="718" alt="image" src="https://github.com/user-attachments/assets/708ba91b-9b05-4610-8f5e-6f589bfccc5b" />

<img width="1364" height="723" alt="image" src="https://github.com/user-attachments/assets/a8b662c7-7365-40f2-8e6d-64b76c65c5b7" />


 **Lighthouse**
 Usar herramienta lighthouse que taammbién está en la inspección de la página. 
 (Puntuación de rendimiento)[https://developer.chrome.com/docs/lighthouse/performance/performance-scoring?utm_source=lighthouse&utm_medium=devtools&hl=es-419
<img width="1366" height="727" alt="image" src="https://github.com/user-attachments/assets/f139fa9e-2105-4b01-9907-e2140ae8e6e3" />]


Se puede analizar con otras herramientas cómo antigravity mediante el chat que tiene la IA, así como optimizar el código.

---

# Crea tu pripio equipo de agentes en 30 minutos.

## Los LLMs NO RAZONAN, 
pero podemos simular su razonamiento.

## Un solo prompt no escala.
- Ni en complejidad.
- Ni en calidad.
- Ni en control.

 ## El problema
 Usamos LLMs como si fueran humanos pero se compartan como maquinas de autocompletado

 ## La intuición equivocada
 Solo dame un promt más largo
 Hazo todo.

 ## Workflog basado en LLM!=Agente
 un workflow ejecuta pasos fijos. 
 Un ajgente decidio que hacer.

 ## Workflow con LLM
 - Pasos explicitos
 - Control total de flujo
 - Fácil de debuggear
 - Poco Flexible.

 - ## Agente

 - - Obejetivo, no pasos
   - Autonomia limitada o alta.
   - Usa herramientas cuando las necesita.
   - Puede fallar... de formas interesantes.
  
   ## Entre más autonmia mas "agentic"

   ## ¿Por qué no darle todo a un sólo agente?

   - Contexto demasiado grande
   - Objetivos mezclados
   - La calidad se diluye.
  
   ## Seguro te ha pasado

   - ChatGPT se desvía.
   - La conversación se "contamina"
   - Pierdes control del resultado
   - Terminas abriendo otro chat.
  
   ## Thinking, fast and slow.

   Sistema 1: Rapido automático.
   Sistema 2: Lento, deliberado.

   ## Técnicas para simular razonamiento.

   - Chain of thought
   - Tree of Thought
   - Reflexión
   - Agentes  (nO ES UN PROMT)
  
   ## AGENTES = ARQUITECTURA, NO PROMPTING.

   ## Divide y vencerás aplicado a LLMS.
   un problema grande se convierte en problemas pequeños y claros.

   ## Sistemas multi-agente en la práctica.

   - Multiples agentes
   - Roles claros.
   - Colaboración explicita.

     ## ¿Por qué CrewAI?

   - Modelo mental simple
   - Python
   - Opiniones claras
   - Bajo overhead conceptual
  
   ## CrewAI Modelo mental.
   Piensa en un equipo de trabajo.

   ## Conceptos clave
   - Crew -> equipo
   - Agent -> rol especializado
   - Task -> Trabajo concreto
   - Process -> Cómocolaboran.
  
   ## Cómo funciona.

   - Definir roles
   - Define tareas
   - Defines la forma de colaborar
   - Ejecutas.

   [Insertar imagen de código python]

   ### Definición de una tarea:
   [Segunda imagen de código]
   ### Definir Crew
   [Agregar segunda imagen de código python]

   ## Process
   - El Process es la "regla del juego" que define como colaboran los agentes.
   - Decide orden, handoffs, y (en hierarchical) quien asigna el trabajo.
   - Piensa en esto como el patrón de orquestación del equipo.
  
   ### Definir el process.
   [Tercera foto]

   ### Definir el processo con un manager.
   [CUARTA FOTO]


   ## Arquitectura > prompts

   ## ¿Cuándo usar multi-agente?
   Cuando el problema tiene multiples roles.

   ## Buenos casos
   - Research + sintesis
   - Planeación + ejecución
   - Análisis + validación
   - Code review automatización
  
   ## Malos casos
   - Preguntas triviales
   - Latencia ultra baja
   - Costos estrictos
  
   ## Más agentes != No es un mayor sistema.

   [DEMO]

   
---

# Aeroespacial

## SGI

REGIÓN -> Satélite -> Tiempo -> Limpieza -> Variables -> Análisis.

Generar un gee de una serie temporal. 

