---

# **PPT 00: Introducción a la Ingeniería de Software**

## **1\) Idea central del tema**

El mensaje de fondo del PPT 00 es que el software no puede entenderse **solo como código**, y por eso **saber programar no alcanza**. El software profesional involucra programas, documentación, personas, procesos, calidad, cambios, versiones y mantenimiento. Cuando el desarrollo crece en tamaño y complejidad, aparecen problemas de coordinación, planificación, requerimientos, calidad y evolución, y ahí es donde surge la **ingeniería de software** como disciplina.

La clase refuerza esta idea con una advertencia clara: confundir software con código lleva a subestimar los problemas reales de proyecto. El parcial suele evaluar justamente esta diferencia entre "programar" y "hacer ingeniería de software".

## **2\) Qué es software y por qué no es solo código**

El PPT define software como un conjunto de programas y la documentación que los acompaña, y distingue tres tipos básicos:

* **software de sistema**;
* **utilitarios**;
* **software de aplicación**.

Sommerville amplía esta definición: en software profesional no se trabaja solo con ejecutables, sino también con configuraciones, documentación técnica, documentación de usuario y otros artefactos asociados.

La conclusión teórica clave es esta:

**software = código + artefactos + decisiones + contexto de uso.**

## **3\) Por qué no conviene comparar software con manufactura**

El bloque de clase insiste en cinco motivos para no equiparar software con una línea de producción tradicional:

* es **menos predecible**;
* no hay verdadera producción en masa de productos idénticos;
* no todas las fallas son equivalentes a "defectos de fabricación";
* el software **no se gasta** como un objeto físico;
* no está regido por leyes físicas de la misma forma que un producto industrial.

La transcripción además subraya una idea muy examinable: incluso dos productos "parecidos" suelen divergir porque cambian requerimientos, contexto y usuarios. Por eso en software pesa más la **gestión de cambio** que la repetición mecánica.

## **4\) Crisis del software y nacimiento de la disciplina**

El PPT ubica hitos históricos (NATO 1968, *The Mythical Man-Month*, Structured Analysis, *No Silver Bullet*, CMM/CMMI, Manifiesto Ágil, Lean Software Development) para explicar que la disciplina nace como respuesta a una crisis persistente: proyectos tarde, caros y con resultados por debajo de lo esperado.

Sommerville y Brooks convergen en el mismo punto: cuando los sistemas crecen, el problema deja de ser "escribir código" y pasa a ser coordinar trabajo **multipersona**, **multiversión** y con alta complejidad conceptual.

## **5\) Problemas típicos del desarrollo y factores de éxito/fracaso**

El PPT destaca problemas recurrentes:

* la versión final no satisface al cliente;
* baja extensibilidad y adaptabilidad;
* documentación deficiente;
* calidad insuficiente;
* sobrecostos y retrasos.

En paralelo, marca factores de **éxito** (involucramiento de usuarios, apoyo gerencial, requerimientos claros, planificación adecuada, expectativas realistas) y de **fracaso** (requerimientos incompletos, poco involucramiento del usuario, recursos insuficientes, expectativas irreales, cambios no gestionados).

McConnell refuerza esta lectura: los desbordes de plazo/costo no suelen deberse a una sola causa técnica, sino a una combinación de decisiones pobres de producto, proceso, gestión y coordinación.

## **6\) Ingeniería de software como disciplina**

Sommerville define la ingeniería de software como una disciplina interesada en **todos los aspectos** de la producción y mantenimiento del software, desde especificación inicial hasta evolución en operación.

El PPT organiza la materia en tres grupos de disciplinas:

* **técnicas**: requerimientos, análisis/diseño, construcción, pruebas, despliegue;
* **de gestión**: planificación, monitoreo y control;
* **de soporte**: configuración, aseguramiento de calidad, métricas.

Esta estructura permite justificar por qué en el parcial aparece la afirmación central:

**saber programar no es suficiente para construir software profesional.**

## **7\) Proceso de software: qué es y por qué importa**

El PPT define proceso de software como un conjunto estructurado de actividades para desarrollar un sistema, y aclara que debe **modelarse explícitamente** si se quiere administrar.

Sommerville resume cuatro actividades comunes a la mayoría de procesos:

* **especificación**;
* **desarrollo**;
* **validación**;
* **evolución**.

La clase aporta un matiz importante: proceso no es solo secuencia de tareas; incluye personas, métodos, herramientas, habilidades, entrenamiento y motivación.

## **8\) Procesos definidos vs empíricos**

### **Proceso definido**

Parte de la idea de repetibilidad y control por predictibilidad: mismas entradas, mismo proceso, salidas similares.

### **Proceso empírico**

Asume complejidad y variabilidad: el control se logra por **inspección frecuente** y **adaptación**.

El PPT y la clase usan esta distinción para preparar el puente hacia enfoques ágiles. En software, muchos contextos no se gobiernan bien solo con predicción; requieren ciclos de feedback.

## **9\) Ciclos de vida**

El ciclo de vida se presenta como serie de pasos por los que progresa un proyecto o producto. El PPT remarca que un ciclo de vida es una **representación del proceso** y clasifica en:

* **secuencial**;
* **iterativo/incremental**;
* **recursivo**.

Complemento bibliográfico:

* Sommerville: modelos como cascada, incremental y reutilización;
* McConnell (*Rapid Development*): variantes como waterfall, spiral, staged delivery y evolutionary prototyping.

La idea importante para parcial: no existe un único ciclo de vida universalmente superior; su utilidad depende de contexto y tipo de problema.

## **10\) Relación proceso / ciclo de vida / proyecto / producto**

Aunque el desarrollo detallado de "componentes de proyecto" aparece luego, el PPT 00 deja planteada la relación base:

* **proceso**: cómo se trabaja (actividades, métodos, roles, herramientas);
* **ciclo de vida**: cómo se representa y ordena ese trabajo en fases;
* **proyecto**: esfuerzo temporal que ejecuta el proceso;
* **producto**: resultado que luego evoluciona en operación.

En forma sintética:

**el proceso organiza, el ciclo de vida estructura, el proyecto ejecuta y el producto materializa el resultado.**

## **11\) No Silver Bullet (sección clave del parcial)**

*No Silver Bullet* es central en el parcial porque explica por qué no existe una técnica "milagrosa" que elimine de una vez los problemas del software.

Brooks distingue entre:

* **dificultad accidental**: derivada de herramientas/lenguajes/entornos;
* **dificultad esencial**: propia de la naturaleza del software.

Dentro de la dificultad esencial destaca cuatro propiedades:

* **complejidad**;
* **conformidad**;
* **cambiabilidad**;
* **invisibilidad**.

La consecuencia conceptual es fuerte:

**mejorar herramientas ayuda, pero no elimina el núcleo duro del problema.**

Por eso, la mejora real exige combinación de ingeniería de requerimientos, diseño conceptual, validación, gestión y disciplina de equipo, no una sola "bala de plata".

## **12\) Ejemplos emblemáticos y sentido de esos ejemplos**

El material usa casos para mostrar impacto real del software:

* ejemplos de proyectos exitosos (como Apollo/Margaret Hamilton);
* ejemplos de fallas con consecuencias fuertes (la clase menciona casos como Ariane y sistemas críticos en transporte).

La cátedra no busca memorizar anécdotas aisladas, sino extraer la lectura conceptual:

* en casos exitosos, pesan disciplina, integridad conceptual y calidad;
* en casos fallidos, escalan errores de requerimientos, validación, diseño, control de cambios y gestión.

## **13\) Qué conviene aprender bien de memoria conceptual**

Para este tema, conviene dominar estas ideas:

* el software profesional **no es solo código**;
* no conviene equipararlo sin más con manufactura;
* la crisis histórica del software explica el surgimiento de la disciplina;
* **saber programar no alcanza**;
* la ingeniería de software integra técnicas, gestión y soporte;
* el proceso de software debe modelarse para ser administrable;
* hay diferencia entre procesos definidos y empíricos;
* el ciclo de vida representa el proceso y ordena fases;
* proceso/ciclo/proyecto/producto están relacionados pero no son sinónimos;
* *No Silver Bullet* explica por qué no hay soluciones mágicas.

## **Lecturas recomendadas para complementar**

### **Nivel 1: base obligatoria para este PPT**

**Sommerville - *Ingeniería de Software***

* Cap. 1 (introducción);
* Cap. 2 (procesos de software);
* Cap. 3 (desarrollo ágil).

**Brooks - *No Silver Bullet***

* dificultad esencial vs accidental;
* complejidad, conformidad, cambiabilidad e invisibilidad;
* límites de las mejoras "milagrosas".

**McConnell - *Rapid Development***

* classic mistakes;
* risk management;
* lifecycle planning;
* estimation y scheduling.

### **Nivel 2: complemento útil**

**Software's Ten Essentials**

* enfoque de buenas prácticas globales de proyecto.

**The Mythical Man-Month**

* gestión de proyectos grandes;
* integridad conceptual y coordinación multipersona.

**Manifiesto Ágil + Scrum Guide (solo como puente conceptual)**

* contexto empírico, feedback, adaptación.

## **Posibles preguntas de parcial, con respuesta modelo**

### **1\. Por qué saber programar no es suficiente?**

Porque el software profesional incluye requerimientos, diseño, validación, evolución, calidad, configuración y coordinación de equipos, no solo codificación.

### **2\. Por qué no conviene comparar software con manufactura?**

Porque el software es menos predecible, no se produce en masa de forma idéntica, no se desgasta como objeto físico y su dificultad principal es conceptual.

### **3\. Qué es ingeniería de software?**

Es la disciplina de ingeniería que aborda todos los aspectos de producción y mantenimiento de software, desde especificación inicial hasta evolución en operación.

### **4\. Qué es un proceso de software?**

Es un conjunto estructurado de actividades para construir software. Incluye personas, métodos, herramientas y productos asociados, y debe explicitarse para poder gestionarlo.

### **5\. Qué diferencia hay entre proceso definido y empírico?**

El definido se apoya en predictibilidad y repetición; el empírico en inspección y adaptación frente a variabilidad y complejidad.

### **6\. Qué relación hay entre proceso y ciclo de vida?**

El ciclo de vida es una representación del proceso en fases y orden temporal; no reemplaza al proceso como concepto más amplio.

### **7\. Qué relación hay entre proceso, ciclo de vida, proyecto y producto?**

Proceso: cómo se trabaja. Ciclo de vida: cómo se ordena ese trabajo. Proyecto: esfuerzo temporal que lo ejecuta. Producto: resultado que se entrega y luego evoluciona.

### **8\. Cuál es la idea clave de No Silver Bullet?**

Que no existe una técnica única capaz de resolver de manera drástica y universal la complejidad del software, porque gran parte de esa dificultad es esencial.

## **Mini resumen final para repetir antes del examen**

La **ingeniería de software** surge porque el software profesional es complejo, cambiante y multipersona, y no puede gobernarse solo con codificación. El software no es solo código: integra artefactos, procesos, decisiones y contexto de uso. Por eso no conviene compararlo de forma lineal con manufactura. La disciplina combina técnicas, gestión y soporte para enfrentar problemas de requerimientos, calidad, coordinación y evolución. En este marco, el **proceso** define cómo se trabaja, el **ciclo de vida** organiza fases, el **proyecto** ejecuta y el **producto** materializa el resultado. *No Silver Bullet* cierra la idea: no hay soluciones mágicas; la mejora real viene de disciplina de ingeniería, buen diseño conceptual, validación y gestión continua del cambio.

---

# **PPT 01: Software Configuration Management (SCM)**

## **1\) Idea central del tema**

La idea más importante del ppt es esta:

**SCM existe porque el software cambia todo el tiempo, y si esos cambios no se identifican, controlan, registran y auditan, el proyecto entra en caos.** El propio ppt arranca mostrando que el software no es solo código, sino un conjunto de programas, procedimientos, reglas, documentación y datos, y que todos esos artefactos evolucionan con el tiempo. Cuando en enero tenías una versión de requerimientos, diseño, fuentes y objetos, en febrero ya puede haber cambios parciales, inconsistencias o dudas sobre cuál es “la” versión correcta. Ahí aparece SCM como disciplina de soporte transversal.

Bersoff dice algo muy parecido: SCM creció como una de las disciplinas que surgieron en respuesta a los fracasos del software de los años 70, cuando las aplicaciones se volvieron demasiado complejas para seguir manejándolas “a mano”. Su idea central es que SCM ayuda a construir y mantener la **integridad del producto**, no solo a guardar archivos.

El *Little Book of Configuration Management* lo resume de forma brutal y muy memorizable: **sin CM, el proyecto queda plagado de caos, errores, daño permanente, baja productividad y evolución inmanejable**. Incluso afirma una especie de “ley fundamental”: si hacés mal la configuración, olvidate de mejorar el proceso de desarrollo.

---

## **2\) Qué es SCM**

El ppt da una definición clásica tomada de **ANSI/IEEE 828 (1990)**: SCM es una disciplina que aplica dirección y monitoreo administrativo y técnico para **identificar y documentar** las características funcionales y técnicas de los ítems de configuración, **controlar cambios**, **registrar y reportar** esos cambios y su estado de implementación, y **verificar** la correspondencia con los requerimientos.

Eso ya te marca cuatro verbos clave:

* identificar,  
* controlar,  
* registrar/reportar,  
* verificar.

El *Little Book* lo formula de un modo muy claro: el propósito fundamental de CM es **establecer y mantener la integridad y el control de los productos de software a lo largo de todo el ciclo de vida**. Y agrega que esto incluye identificar la configuración en puntos dados del tiempo, controlar sistemáticamente cambios y mantener integridad y trazabilidad.

O sea: **SCM no es solo Git**. Git puede ser una herramienta dentro de SCM, pero SCM como disciplina incluye proceso, roles, auditoría, reportes, líneas base, control formal de cambios y trazabilidad. El mismo subtítulo del ppt lo sugiere: “más allá del commit y update”.

---

## **3\) Por qué SCM es necesario**

El ppt enumera varias fuentes de cambio en el software:

* cambios del negocio y nuevos requerimientos,  
* soporte a cambios de productos asociados,  
* reorganización de prioridades,  
* cambios de presupuesto,  
* defectos a corregir,  
* oportunidades de mejora.

Ese punto es importante: el cambio **no es una anomalía**, es la condición normal del software. Por eso el slide 14 habla de que el software es un **“blanco móvil”**. La integridad del producto depende de que el sistema siga satisfaciendo necesidades del usuario, sea rastreable, cumpla criterios de performance y expectativas de costo, aun mientras evoluciona.

Bersoff refuerza esto definiendo la **product integrity** como un producto que satisface necesidades reales del usuario, puede rastrearse completamente durante su ciclo de vida, cumple criterios de performance y satisface expectativas de costo y entrega. En la figura 1 de su paper, eso aparece literalmente como la idea de integridad del producto.

El ppt también te muestra los problemas típicos de no hacer SCM:

* pérdida de componentes,  
* pérdida de cambios,  
* falta de sincronía fuente–objeto–ejecutable,  
* regresión de fallas,  
* doble mantenimiento,  
* superposición de cambios,  
* cambios no validados.

Todo eso se entiende mejor con una frase del *Little Book*: CM puede mejorar productividad porque reduce uno de los grandes consumidores de esfuerzo en software, que es el **rework**. Si no controlás bien qué cambió, quién lo cambió y contra qué baseline estás trabajando, terminás rehaciendo trabajo o arreglando problemas que vos mismo creaste por falta de control.

---

## **4\) SCM como disciplina de soporte**

El ppt presenta a SCM como una **actividad paraguas**, transversal a todo el proyecto y relevante para el producto durante todo su ciclo de vida. Además la ubica junto con otras disciplinas de soporte como aseguramiento de calidad, pruebas, control de calidad de proceso y de producto. En el diagrama del slide 10 se ve esta idea de que SCM envuelve y sostiene esas otras actividades.

Bersoff lo pone en un marco todavía más rico. En su figura 2 aparece el **triángulo disciplinar**: por un lado la gestión, por otro el desarrollo, y por otro la aseguración de producto. Dentro de esta última ubica **QA, test y evaluación, validación y verificación, y configuration management**. La idea fuerte es que SCM no reemplaza a QA ni a testing, pero sí aporta **visibilidad, control e integridad** al desarrollo.

Entonces, si te preguntan en examen dónde encaja SCM, la respuesta no es “en versionado” sino:

**SCM es una disciplina de soporte que ayuda a mantener la integridad, trazabilidad y control del producto y de sus artefactos durante todo el ciclo de vida.**

---

## **5\) Conceptos clave: ítem de configuración, versión, variante, configuración**

### **Ítem de configuración (CI o SCI)**

El ppt define el **ítem de configuración** como todo artefacto que forma parte del producto o del proyecto, que puede sufrir cambios o necesita compartirse entre miembros del equipo, y sobre el cual necesitamos conocer su estado y evolución. Da ejemplos amplísimos: requerimientos, arquitectura, código fuente, casos de prueba, plan de calidad, plan de proyecto, manuales, prototipos, gráficos, instaladores, documentos de despliegue, etc.

Esto es importantísimo porque SCM no controla solo “source files”. Controla **todo lo que sea relevante para reproducir, validar, liberar o mantener el producto**. El *Little Book* también insiste en esto cuando enumera planes, especificaciones, código, build scripts, manuales, test plans, test cases, COTS y hasta compiladores o herramientas del entorno como objetos a considerar bajo CM.

### **Versión**

El ppt dice que una **versión** es la forma particular de un artefacto en un instante o contexto dado. El control de versiones se refiere a la evolución de un único CI, y esa evolución puede representarse como un grafo. En el slide 19 aparece una evolución lineal simple.

### **Variante**

Una **variante** es una versión que evoluciona por separado. Representa configuraciones alternativas. El ppt da el ejemplo típico de diferentes plataformas o funciones opcionales. En el slide 20 aparece el grafo ramificado de una variante.

### **Configuración del software**

La **configuración** es el conjunto de ítems de configuración con sus versiones correspondientes en un momento determinado. O sea: no es un archivo aislado, sino una **foto coherente del sistema** en cierto punto del tiempo.

Esto conecta directo con Bersoff: él explica que SCM trabaja tomando “snapshots” o instantáneas del sistema en puntos discretos del ciclo de vida para poder controlar cambios, mantener integridad y conservar trazabilidad.

---

## **6\) Repositorio**

El ppt define el **repositorio** como una base de información que contiene los ítems de configuración, mantiene su historia, atributos y relaciones, y sirve para evaluar impacto de cambios propuestos. Incluso aclara que puede ser una o varias bases de datos. En el slide 24, el diagrama muestra el flujo de checkout, construcción, objetos y checkin.

Después distingue dos modelos:

### **Repositorio centralizado**

Un servidor contiene todos los archivos y versiones. Tiene más control centralizado, pero si el servidor cae, quedás muy comprometido. El ppt lo resume bastante crudamente: si falla el servidor, “estamos al horno”.

### **Repositorio descentralizado**

Cada cliente tiene una copia completa del repositorio. Si un servidor falla, la recuperación es más simple y además permite workflows que no existen tan fácilmente en un modelo centralizado.

Para examen, esto te sirve para explicar por qué Git distribuido no agota SCM, pero sí resuelve una parte muy importante del problema de repositorio e historial.

---

## **7\) Línea base (baseline)**

Este es uno de los conceptos más examinables del tema.

El ppt dice que una **línea base** es una configuración que fue **revisada formalmente** y sobre la cual se alcanzó un acuerdo. A partir de ahí sirve de base para desarrollos posteriores y solo puede cambiarse mediante un **procedimiento formal de control de cambios**. Además permite volver atrás en el tiempo y reproducir el entorno de desarrollo de un momento del proyecto.

El slide 29 es muy bueno para entenderlo: muestra componentes A, B, C, D, luego un cambio y una nueva baseline con A, B, D, E. O sea, una baseline no es “la última versión de todo”, sino una **configuración sancionada** y conocida.

El ppt aclara también que puede haber líneas base de:

* **especificación**, como requerimientos o diseño,  
* **producto**, luego de pasar ciertos controles de calidad.

Bersoff suma una precisión muy buena: una baseline es parte de una jerarquía de SCI y updates, y el rol de SCM es proveer etiquetas, documentación y rastro histórico para conectar esas instantáneas a lo largo del ciclo de vida.

En lenguaje simple:

**una baseline es una versión oficialmente congelada y aceptada de una configuración.**

---

## **8\) Ramas y merge**

El ppt dedica varias diapositivas a las **ramas**. Dice que existe una rama principal (trunk o master), que las ramas sirven para bifurcar desarrollo, pueden tener semántica, permiten experimentación y pueden descartarse o integrarse.

La integración de ramas se hace por **merge**. El merge lleva cambios hacia la rama principal, puede generar conflictos y esos conflictos se resuelven comparando diferencias. La diapositiva remarca una idea sana: las ramas deberían eventualmente **integrarse o descartarse**, no quedar vivas para siempre sin criterio.

En el parcial probablemente no te van a tomar Git profundo, pero sí les interesa que entiendas que las ramas son una forma de gestionar **variantes temporales del desarrollo** y que sin una política clara de integración pueden convertirse en una nueva fuente de caos.

---

## **9\) Las cuatro actividades fundamentales de SCM**

El ppt lo resume en la diapositiva 36 y después desarrolla cada una:

1. **Identificación de ítems**  
2. **Control de cambios**  
3. **Informes de estado**  
4. **Auditorías de configuración**

Bersoff usa prácticamente la misma estructura y nombra como componentes de SCM: **identification, control, auditing y status accounting**.

Estas cuatro actividades son el corazón del tema.

---

## **10\) Identificación de ítems de configuración**

El ppt dice que identificar ítems implica:

* identificación unívoca de cada CI,  
* convenciones y reglas de nombrado,  
* definición de la estructura del repositorio,  
* ubicación dentro de esa estructura.

En el ejemplo del slide 39 se ve que hay ítems de distintos niveles:

* de **producto**: ERS, arquitectura, código, manual,  
* de **proyecto**: plan de proyecto, cronograma,  
* de **iteración**: plan de iteración, reporte de defectos.

El *Little Book* insiste mucho con esto: la identificación tiene que arrancar temprano, y debe cubrir tanto deliverables como artefactos internos, entorno, herramientas, casos de prueba, build scripts y productos externos que impactan el sistema. También advierte que la entrada de artefactos a CM debe estar sincronizada con las fases del proyecto.

La idea conceptual es:

**si no sabés exactamente qué artefactos controlás, no podés controlar nada.**

---

## **11\) Control de cambios**

### **Qué es**

El ppt dice que el control de cambios nace a partir de un **requerimiento de cambio** sobre uno o varios ítems que están en una línea base. Y aclara que es un **procedimiento formal** que involucra diferentes actores y una evaluación del impacto del cambio.

El diagrama del slide 41 muestra el flujo: línea base, propuesta de cambio, análisis de impacto, revisión por partes, aceptación o rechazo, notificación y comité de control de cambios.

### **Qué se evalúa**

En el slide 42 se ve más detalle: se analiza impacto técnico, efectos colaterales, costos del proyecto, impacto general, criterios de auditoría y revisión, y luego la decisión del comité genera una orden de cambio o lo manda a cola de cambios.

Bersoff muestra exactamente lo mismo en la figura 5 del paper: la precipitación del cambio, su preparación, el ECP, la evaluación por el CCB, la aprobación o rechazo y la incorporación del cambio.

### **Comité de Control de Cambios (CCB)**

El ppt dice que el **Comité de Control de Cambios** está formado por representantes de análisis, diseño, implementación, testing y otros interesados.

El *Little Book* profundiza muchísimo esto: el CCB/ERB debe asegurar que solo se implementen cambios necesarios, que estén bien clasificados, que se evalúen impactos, que se definan necesidades de test y retest, y que los roles y responsabilidades de cada participante estén documentados. Incluso enumera acciones posibles como rechazar, asignar estudio, asignar corrección, reanalizar, diferir, aprobar build/release o cerrar el problema.

### **Idea para parcial**

**El control de cambios no busca frenar todo cambio; busca que el cambio sea evaluado, autorizado, trazable y consistente con el resto del sistema.**

---

## **12\) Auditorías de configuración**

Este bloque también es central.

El slide 45 del ppt es muy bueno: muestra requerimientos, producto construido y documentación, unidos por una matriz de trazabilidad, y separa **auditoría física** de **auditoría funcional**.

### **Auditoría física de configuración (PCA)**

Verifica que lo que está indicado para cada ítem en la línea base o su actualización **existe realmente**. Es más de “correspondencia física/documental”.

### **Auditoría funcional de configuración (FCA)**

Es una evaluación independiente que controla que la funcionalidad y performance reales de cada ítem sean consistentes con la especificación de requerimientos.

El ppt además enlaza esto con **validación** y **verificación**:

* **Validación**: asegura que se resolvió apropiadamente el problema y que el usuario obtiene el producto correcto.  
* **Verificación**: asegura que el producto cumple con los objetivos definidos en la documentación de baseline.

Bersoff desarrolla el mismo punto: la auditoría de configuración sirve para dar **visibilidad** y **trazabilidad** durante el ciclo de vida. Explica que hacer auditorías temprano evita rework costoso en etapas tardías y permite descubrir nuevas necesidades o problemas de diseño antes de que sean demasiado caros.

En una frase:

**la auditoría te responde si el producto construido coincide con lo que debía construirse, y si además resuelve correctamente lo que el usuario necesitaba.**

---

## **13\) Registro e informe de estado (status accounting)**

El ppt dice que el informe de estado se ocupa de mantener registros de la evolución del sistema, manejar mucha información —normalmente automatizada— e incluir reportes de rastreabilidad de todos los cambios hechos a las líneas base durante el ciclo de vida.

Después pone ejemplos de preguntas que debería poder responder:

* ¿cuál es el estado del ítem?  
* ¿un cambio fue aprobado o rechazado por el CCB?  
* ¿qué versión implementa cierto cambio aprobado?  
* ¿cuál es la diferencia entre una versión y otra?

Bersoff define **software configuration status accounting** como el mecanismo que registra cómo fue evolucionando el sistema, qué cambios se hicieron realmente y dónde está el sistema respecto de lo que aparece en documentación y acuerdos de baseline.

El *Little Book* lo vuelve todavía más concreto: el status accounting debe mantener estado de productos, estado de cambios, quién tiene qué producto, trazabilidad, problemas abiertos y cerrados, y descripción exacta de lo liberado, idealmente con documentos de versión.

O sea:

**si el control de cambios decide, el status accounting deja evidencia y visibilidad.**

---

## **14\) Plan de Gestión de Configuración**

El ppt dice que la gestión de configuración **también se planifica**. El plan debería incluir:

* reglas de nombrado de los CI,  
* herramientas a utilizar,  
* roles e integrantes del comité,  
* procedimiento formal de cambios,  
* plantillas de formularios,  
* procesos de auditoría.

El *Little Book* dedica varias páginas a esto y propone que el CM Plan incluya introducción, organización, fases y milestones del proyecto, identificación de configuración, gestión de interfaces, status accounting, auditorías y gestión de subcontratistas. También dice algo importante: el plan y los procedimientos de CM deben desarrollarse **desde el inicio del proyecto**, igual que un software development plan.

Esto es bastante examinable porque expresa una idea general de la materia:

**las disciplinas de soporte no se improvisan al final; se piensan desde el arranque.**

---

## **15\) SCM en Agile**

Acá el ppt hace un giro muy importante: muestra que SCM no desaparece en Agile, sino que **cambia de estilo**.

Las diapositivas finales dicen que en Agile, SCM:

* sirve al equipo y no al revés,  
* coordina y da seguimiento en lugar de controlar a los desarrolladores,  
* responde al cambio en lugar de evitarlo,  
* busca transparencia y baja fricción, automatizando lo más posible,  
* promueve coordinación rápida y frecuente,  
* elimina desperdicio,  
* apunta a documentación lean y trazabilidad,  
* da feedback continuo y visible sobre calidad, estabilidad e integridad.

El documento **“SCM & the Agile Manifesto”** encaja perfecto con eso. Relaciona cada valor del manifiesto con SCM:

* **Individuals and interactions over processes and tools**: los procesos y herramientas de SCM deben apoyar la forma de trabajo del equipo, no imponer una rigidez inútil.  
* **Working software over comprehensive documentation**: SCM puede automatizar políticas y procedimientos mediante scripts y conocimiento ejecutable, en vez de depender solo de documentos.  
* **Customer collaboration over contract negotiation**: SCM puede dar visibilidad del estado del proyecto y facilitar interacción entre stakeholders.  
* **Responding to change over following a plan**: SCM trata de facilitar el cambio, no de impedirlo.

Esto es clave porque rompe un prejuicio clásico: pensar que SCM es “burocracia antiágil”. En realidad, el enfoque ágil no elimina SCM; elimina **SCM mal diseñado**.

El ppt además agrega tips concretos:

* es responsabilidad de todo el equipo,  
* hay que automatizar lo máximo posible,  
* educar al equipo,  
* y embutir tareas de SCM dentro del trabajo normal del sprint.

---

## **16\) Despliegues modernos como extensión práctica de SCM**

El ppt mete como referencia un artículo de Harness sobre **blue-green** y **canary deployments**. Eso no parece ser el centro teórico del parcial, pero sí es una buena forma de ver cómo SCM se extiende hoy hacia **release management y control de despliegue**.

El artículo explica que:

* **blue-green deployment** usa dos ambientes idénticos; el tráfico se conmuta del ambiente viejo al nuevo, lo que hace rollback más simple pero cuesta más infraestructura;  
* **canary deployment** libera gradualmente una nueva versión a un subconjunto de usuarios o infraestructura, reduciendo el riesgo y permitiendo rollback rápido;  
* los despliegues básicos son los más riesgosos;  
* y las estrategias donde conviven versión vieja y nueva suelen ser más seguras.

Si querés una lectura moderna de por qué SCM hoy también roza CI/CD, esta referencia sirve. Pero para el parcial, yo la tomaría como **complemento actual**, no como núcleo del tema.

---

# **Qué estudiar sí o sí para el parcial**

## **Definiciones y conceptos que tenés que poder explicar**

Tenés que saber explicar con tus palabras:

* qué es SCM,  
* por qué es necesaria,  
* qué es un ítem de configuración,  
* qué es una versión,  
* qué es una variante,  
* qué es una configuración,  
* qué es un repositorio,  
* qué es una línea base.

## **Actividades fundamentales**

Tenés que saber desarrollar:

* identificación de ítems,  
* control de cambios,  
* auditorías,  
* informes de estado.

## **Parte ágil**

Tenés que poder defender la idea de que:

**SCM en Agile no desaparece; se vuelve más automática, menos friccional, más orientada al equipo y al cambio.**

---

# **Lecturas recomendadas para complementar**

## **Imprescindibles**

### **1\. PPT 01**

Es el mapa del tema. Ahí está todo el esqueleto conceptual.

### **2\. Bersoff – *Elements of Software Configuration Management***

Muy bueno para:

* entender SCM en contexto,  
* relacionarla con QA, V\&V y testing,  
* reforzar la idea de product integrity,  
* y entender identificación, control, auditing y status accounting como estructura clásica.

### **3\. *Little Book of Configuration Management***

Excelente porque traduce la teoría en reglas, best practices y preguntas concretas. Te sirve para:

* ver cómo se arma un CM Plan,  
* entender por qué CM es de todos,  
* y fijarte qué preguntas debería poder contestar un proceso de configuración bien hecho.

## **Muy útiles**

### **4\. *SCM & the Agile Manifesto***

Lectura corta, ideal para cerrar la parte ágil. Te sirve muchísimo para una respuesta oral o escrita de examen.

### **5\. Harness – blue-green y canary**

Solo como ejemplo actual de cómo el control de configuración, releases y despliegues seguros hoy se conectan con DevOps.

---

# **Posibles preguntas de parcial con respuesta modelo**

## **1\. ¿Qué es SCM?**

Es una disciplina de soporte que identifica y documenta los ítems de configuración, controla sus cambios, registra y reporta su estado y verifica correspondencia con los requerimientos, para mantener la integridad del producto durante su ciclo de vida.

## **2\. ¿Por qué SCM es necesaria?**

Porque el software cambia continuamente. Sin un mecanismo para identificar configuraciones, controlar cambios, registrar versiones y auditar resultados, aparecen pérdida de componentes, regresión de fallas, cambios superpuestos, falta de sincronía y caos evolutivo.

## **3\. ¿Qué es un ítem de configuración?**

Es cualquier artefacto del producto o del proyecto que puede cambiar, compartirse o cuyo estado y evolución necesitan ser conocidos y controlados. No es solo código: también incluye requerimientos, diseños, casos de prueba, planes, manuales, instaladores y otros artefactos.

## **4\. ¿Qué es una línea base?**

Es una configuración revisada y acordada formalmente, que sirve de base para desarrollos posteriores y que solo puede modificarse mediante control formal de cambios.

## **5\. ¿Cuáles son las actividades fundamentales de SCM?**

Identificación de ítems, control de cambios, auditorías de configuración e informes de estado.

## **6\. ¿Qué diferencia hay entre auditoría física y funcional?**

La auditoría física verifica que lo especificado para cada ítem exista realmente en la configuración. La funcional verifica que la funcionalidad y performance reales sean consistentes con los requerimientos.

## **7\. ¿Qué hace el Comité de Control de Cambios?**

Evalúa propuestas de cambio, analiza su impacto, decide su aprobación, rechazo, postergación o corrección y coordina su incorporación controlada al sistema.

## **8\. ¿SCM contradice Agile?**

No. En Agile, SCM sigue siendo necesaria, pero debe apoyar al equipo, automatizarse al máximo, reducir fricción, facilitar el cambio, dar visibilidad y mantener trazabilidad sin burocracia innecesaria.

---

## **Mini resumen final para memorizar**

SCM es la disciplina que permite mantener la integridad del software en un contexto donde todo cambia. Para eso identifica ítems de configuración, define versiones y baselines, controla cambios, registra estado y realiza auditorías. No se limita al código: incluye todos los artefactos relevantes del producto y del proyecto. Su objetivo no es frenar cambios, sino hacer que los cambios sean controlados, trazables, verificables y coherentes con el resto del sistema. En contextos ágiles, SCM sigue existiendo, pero se orienta a automatización, transparencia, baja fricción y soporte al equipo.

Si querés, sigo con el **PPT 02 de Requerimientos Ágiles / User Stories** y te lo dejo con el mismo formato.

---

# **PPT 02: Requerimientos Ágiles y User Stories**

## **1\) Idea central del tema**

La idea de fondo del PPT 02 es que, en un enfoque ágil, los requerimientos no se intentan cerrar de forma completa, rígida y definitiva desde el comienzo, sino que se **descubren**, **priorizan**, **refinan** y **validan** de manera iterativa, siempre guiados por **valor** y **feedback**.

El enfoque ágil no se presenta como una metodología cerrada, sino como una forma de pensar el desarrollo basada en principios, empirismo, adaptación, entregas frecuentes, equipos autoorganizados, integración continua y testing concurrente. En este marco, los requerimientos dejan de verse como un documento estático y pasan a entenderse como una construcción progresiva, apoyada en conversación, validación y aprendizaje.

El ppt también insiste en una idea importante: **ser ágil no significa ser desprolijo**. No implica “hacer todo por partes” sin criterio, sino construir incrementos que entreguen valor real y que tengan sentido por sí mismos. La lógica no es fragmentar arbitrariamente, sino avanzar mediante entregas usables, coherentes y valiosas.

Mike Cohn complementa esto señalando que los proyectos no pueden predecirse por completo desde el inicio, porque a medida que los usuarios ven versiones tempranas cambian de opinión, aparecen nuevas ideas y las estimaciones se corrigen. Por eso, en lugar de concentrar todas las decisiones al principio, conviene distribuirlas a lo largo del proyecto y obtener información temprana y frecuente. Allí es donde adquieren sentido las **user stories**.

## **2\) Qué significa “ágil” en este contexto**

El ppt dice explícitamente que **Agile no es una metodología o un proceso**, sino una **ideología** o enfoque guiado por principios. También remarca que los métodos ágiles son **adaptables** en lugar de predictivos y **orientados a las personas** en lugar de estar centrados únicamente en el proceso.

Esto significa que Agile no equivale a ausencia de disciplina, ni a improvisación, ni a trabajar sin planificación. Lo que propone es un punto de equilibrio entre dos extremos:

* no trabajar sin proceso ni coordinación;  
* pero tampoco cargar al proyecto con un proceso excesivo, rígido y burocrático.

En este contexto, lo ágil implica:

* planificación continua;  
* entregas frecuentes;  
* equipos autoorganizados;  
* comunicación intensa;  
* adaptación al cambio;  
* aprendizaje progresivo;  
* foco en valor.

Esto conecta directamente con lo visto en el ppt 00 sobre **procesos definidos** y **procesos empíricos**. El desarrollo de software ocurre en contextos de incertidumbre, por lo que muchas veces tiene más sentido un enfoque basado en inspección, realimentación y ajuste que uno apoyado exclusivamente en un plan fijo.

## **3\) Los valores y principios ágiles que sostienen los requerimientos ágiles**

El ppt trae los **cuatro valores del Manifiesto Ágil**:

* **individuos e interacciones** sobre procesos y herramientas;  
* **software funcionando** sobre documentación extensiva;  
* **colaboración con el cliente** sobre negociación contractual;  
* **responder al cambio** sobre seguir un plan.

A partir de esos valores, el Manifiesto se concreta en **12 principios**, que funcionan como lineamientos operativos para orientar el trabajo ágil. En síntesis, esos principios establecen:

1. satisfacer al cliente mediante entrega temprana y continua de software con valor;  
2. aceptar cambios de requerimientos, incluso en etapas avanzadas;  
3. entregar software funcionando con frecuencia;  
4. lograr trabajo conjunto entre negocio y desarrollo;  
5. construir proyectos alrededor de individuos motivados;  
6. privilegiar la comunicación cara a cara;  
7. considerar al software funcionando como principal medida de progreso;  
8. promover un desarrollo sostenible;  
9. mantener atención continua a la excelencia técnica y al buen diseño;  
10. valorar la simplicidad, entendida como maximizar el trabajo no hecho;  
11. reconocer que las mejores arquitecturas, diseños y requerimientos emergen de equipos autoorganizados;  
12. reflexionar regularmente para ajustar y mejorar la forma de trabajo.

Ahora bien, no todos impactan con la misma fuerza en la gestión de requerimientos. La clase y el propio ppt remarcan especialmente algunos principios directamente vinculados con **requerimientos ágiles**:

* satisfacer al cliente con **releases tempranos y frecuentes**;  
* aceptar **cambios de requerimientos** incluso en etapas tardías;  
* hacer trabajar juntos a **técnicos y no técnicos** durante todo el proyecto;  
* privilegiar la **comunicación cara a cara**;  
* y reconocer que los mejores requerimientos emergen de **equipos autoorganizados**.

La idea conceptual importante es esta: los requerimientos ágiles no se entienden como un documento que se entrega una vez y queda congelado, sino como una **conversación continua** entre negocio y equipo, orientada por **valor**, **colaboración**, **feedback** y **adaptación al cambio**.

## **4\) Por qué aparecen los requerimientos ágiles**

### **El problema del BRUF**

El ppt critica el enfoque tradicional de **Big Requirements Up Front (BRUF)**, es decir, la idea de hacer un gran análisis de requerimientos completo al comienzo del proyecto. El gráfico de la diapositiva sobre costo del BRUF muestra algo muy importante: incluso en productos considerados exitosos, una gran parte de las funcionalidades desarrolladas termina usándose rara vez o directamente no se usa.

La conclusión es clara: **analizar y especificar demasiado temprano genera desperdicio**.

Por eso el enfoque ágil propone dos ideas centrales:

* analizar **cuando se necesite**, no antes;  
* construir solo lo **suficiente** para avanzar con valor.

Mike Cohn justifica esta crítica señalando que los grandes documentos de requerimientos suelen consumir mucho tiempo al comienzo, convertirse en un fin en sí mismos y además ser interpretados de formas diferentes por personas distintas. Frente a eso, propone trabajar con conversaciones frecuentes, validación progresiva y ajuste continuo.

La clase remarcó además dos ideas muy importantes:

* el criterio central de gestión de requerimientos ágiles es el **valor**;  
* y el detalle debe construirse **just in time**, es decir, **en el momento en que realmente hace falta y no antes**.

Esto significa que no tiene sentido invertir esfuerzo en analizar en profundidad algo que todavía no es prioritario, que incluso podría cambiar o desaparecer del backlog.

## **5\) Qué son los requerimientos ágiles**

El bloque “Requerimientos en Agile” del ppt resume la lógica en tres ideas:

* usar el **valor** para construir el producto correcto;  
* usar **historias y modelos** para mostrar qué construir;  
* determinar qué es **solo lo suficiente**.

En consecuencia, los requerimientos ágiles:

* no buscan describir exhaustivamente todo desde el inicio;  
* se priorizan según valor;  
* se detallan progresivamente;  
* se validan a medida que el producto evoluciona.

El ppt también sostiene que los requerimientos cambiantes pueden convertirse en una **ventaja competitiva**, siempre que exista un mecanismo de trabajo capaz de absorberlos. Por eso, en ágil, la cuestión no es evitar el cambio, sino administrarlo de manera controlada y orientada a valor.

## **6\) Tipos de requerimientos y niveles**

El ppt distingue cinco tipos de requerimientos, con distintos niveles de abstracción:

* **Requerimiento de negocio**: expresa el objetivo del negocio.  
  Ejemplo: disminuir cierto porcentaje del tiempo invertido en procesos manuales.  
* **Requerimiento de usuario**: expresa lo que el usuario necesita poder lograr.  
  Ejemplo: consultar en línea el estado de cuenta.  
* **Requerimiento funcional**: expresa comportamiento del sistema.  
  Ejemplo: generar reportes o enviar notificaciones.  
* **Requerimiento no funcional**: expresa restricciones o cualidades.  
  Ejemplo: seguridad, performance, formato de salida.  
* **Requerimiento de implementación**: expresa decisiones tecnológicas o de entorno.  
  Ejemplo: usar servidores en la nube.

El ppt los ubica además en una pirámide que diferencia el **dominio del problema** y el **dominio de la solución**. En términos simples:

* **negocio** \= por qué;  
* **usuario** \= qué necesita lograr;  
* **software** \= cómo se implementa o soporta.

Esta clasificación es útil porque evita mezclar objetivos de negocio con decisiones técnicas.

## **7\) Tradicional vs ágil en requerimientos**

La diapositiva “Tradicional vs. Ágil” muestra dos formas distintas de pensar la planificación.

En el enfoque más tradicional, el proyecto queda más dirigido por un **plan**, donde los **requisitos** se intentan fijar al comienzo y luego se estiman **recursos** y **tiempo**.

En el enfoque ágil, en cambio, lo que suele quedar más acotado son **tiempo** y **recursos**, mientras que el **alcance** se negocia y reprioriza según **valor**.

La consecuencia práctica es muy importante:  
**en ágil no se promete hacer absolutamente todo, sino maximizar el valor dentro de una capacidad real de tiempo y equipo**.

Esto explica por qué aparecen entregas frecuentes, iteraciones cortas y releases tempranos: el compromiso fuerte no está en congelar todo el alcance desde el principio, sino en trabajar dentro de un marco temporal claro y ajustar contenido según prioridad y aprendizaje.

## **8\) El rol de la comunicación**

El ppt dedica una diapositiva a la riqueza del canal de comunicación y sostiene que el **cara a cara** es el medio más efectivo porque permite que fluya información **vocal**, **subvocal** y **gestual**, con realimentación rápida.

Esto es central para requerimientos ágiles, porque el entendimiento correcto de una necesidad rara vez surge solo del texto escrito. La comunicación directa permite:

* aclarar ambigüedades;  
* detectar supuestos;  
* negociar alcance;  
* construir entendimiento compartido;  
* corregir malentendidos antes de que lleguen a implementación.

Cohn refuerza esta idea al decir que las user stories funcionan porque cambian el eje desde el documento hacia la **conversación**. El texto escrito es importante, pero no es lo principal; lo principal es la interacción entre negocio y desarrollo.

## **9\) Qué es una User Story**

El ppt explica que a las **user stories** se las llama “stories” porque se supone que cuentan una historia, y aclara que lo escrito en la tarjeta no es lo más importante; lo importante es lo que se habla alrededor de ella.

Cohn define la user story como una **descripción breve de funcionalidad** que será valiosa para un usuario o comprador del sistema. Esa descripción tiene tres dimensiones:

* una expresión escrita breve;  
* las conversaciones que desarrollan el detalle;  
* y las pruebas o confirmaciones que muestran cuándo está terminada.

Leffingwell lo resume con la tríada clásica de Ron Jeffries:

* **Card**  
* **Conversation**  
* **Confirmation**

En español:

* **Tarjeta**: representa la intención de manera breve.  
* **Conversación**: desarrolla el entendimiento.  
* **Confirmación**: define qué debe cumplirse para considerar la historia realizada.

## **10\) Las partes de una User Story**

Una user story se compone de:

* **tarjeta**;  
* **conversación**;  
* **confirmación**.

La tarjeta resume la intención. La conversación desarrolla el significado, los límites, los supuestos y el valor. La confirmación expresa las condiciones de satisfacción o aceptación.

La idea más importante acá es que **la historia no se agota en la frase escrita**. El texto es un disparador; el valor real aparece cuando ese texto permite una conversación y una posterior validación.

## **11\) Forma de expresar una historia**

El ppt propone la forma clásica:

**Como `<rol>`, yo puedo/quiero `<actividad>`, de forma tal que `<valor>`**

Esta estructura es potente porque obliga a explicitar:

* **para quién** es la funcionalidad;  
* **qué acción** se espera realizar;  
* **para qué** sirve, es decir, cuál es su valor o beneficio.

Ejemplo del ppt:  
**Como conductor quiero buscar un destino a partir de una calle y altura para poder llegar al lugar deseado sin perderme.**

La forma es útil porque conecta problema y solución dentro de una misma frase.

## **12\) Qué NO son las User Stories**

El ppt es explícito en este punto. Las user stories:

* **no son especificaciones detalladas** como un caso de uso completo;  
* son **expresiones de intención**;  
* no se desarrollan completamente desde el inicio;  
* requieren poco mantenimiento;  
* pueden descartarse luego de implementarse;  
* sirven junto con el código como base para documentación incremental posterior.

El *User Story Primer* refuerza esta idea diciendo que no son “shall statements” exhaustivos, sino expresiones negociables, pequeñas, reordenables y refinadas justo a tiempo.

En consecuencia, una user story no reemplaza una especificación exhaustiva línea por línea; reemplaza la necesidad de producir esa especificación **tan temprano** y **de esa manera**.

## **13\) Para qué sirven las User Stories**

El ppt presenta las user stories como artefactos multipropósito. Pueden funcionar como:

* una necesidad del usuario;  
* una descripción del producto;  
* un ítem de planificación;  
* un token para una conversación;  
* un mecanismo para diferir una conversación hasta el momento adecuado.

Cohn coincide en que sirven para:

* conversar;  
* estimar;  
* planificar releases e iteraciones;  
* validar con aceptación.

En consecuencia, las user stories sirven al mismo tiempo para **entender**, **priorizar**, **planificar** y **validar**.

### **Diferentes niveles de abstracción: tema, épica y user story**

La clase remarcó que no todo aparece directamente como una user story pequeña y lista para implementar. Existen distintos niveles de abstracción:

* **Tema**: agrupación amplia de necesidades o ideas relacionadas.  
* **Épica**: historia grande, todavía demasiado extensa para entrar directamente en una iteración.  
* **User story**: unidad más pequeña, más refinada y más adecuada para estimar y planificar.

Esto conecta con la idea de backlog progresivo: los ítems más lejanos suelen estar en forma más amplia, mientras que los más cercanos se refinan hasta llegar a historias suficientemente pequeñas y claras.

## **14\) Product Backlog y priorización**

El ppt muestra al **Product Owner** priorizando historias dentro del **Product Backlog**. Cada iteración toma los ítems de mayor prioridad; nuevos requerimientos pueden entrar; otros pueden salir; y los más prioritarios son los que reciben mayor detalle.

Cohn agrega que la priorización no depende solo del valor, sino también del costo estimado y de la capacidad del equipo.

La idea clave es:  
**el backlog no es una lista estática de pedidos, sino una cola dinámica de valor**.

## **15\) User stories como porciones verticales**

La diapositiva de “porciones verticales” es una de las más importantes del tema. Muestra que una buena historia no debería cortar solo una capa técnica, sino atravesar **interfaz**, **lógica de negocio** y **persistencia**, entregando funcionalidad usable de punta a punta.

Entonces:

* cortar **horizontalmente** \= dividir por capas técnicas;  
* cortar **verticalmente** \= dividir por funcionalidad usable y valiosa.

La segunda opción suele ser mejor porque permite entregar valor real antes y recibir feedback más útil.

## **16\) Modelado de roles, personas y proxies**

El ppt dedica una parte al **modelado de roles**. Incluye ejemplos como “reclutador interno” y agrega técnicas como:

* **personas**;  
* **personajes extremos**;  
* **usuarios representantes o proxies**.

La idea central es que pensar en “el usuario” como una figura genérica oculta diferencias importantes. En cambio, identificar roles, comportamientos y necesidades concretas ayuda a escribir historias más precisas y relevantes.

## **17\) Criterios de aceptación**

El ppt dedica varias diapositivas a los **criterios de aceptación**. Estos criterios:

* definen los límites de una historia;  
* ayudan a expresar el mínimo necesario para que exista valor;  
* construyen una visión compartida;  
* ayudan a derivar pruebas;  
* ayudan a saber cuándo detener el agregado de funcionalidad.

Por ejemplo, en la historia de búsqueda de dirección, los criterios incluyen condiciones como:

* la altura debe ser numérica;  
* la búsqueda no debe demorar más de 30 segundos.

Además, el ppt aclara que un buen criterio de aceptación:

* expresa una **intención**, no una solución;  
* es **independiente de implementación**;  
* se mantiene en un nivel relativamente alto.

## **18\) ¿Dónde van los detalles?**

El ppt responde esta pregunta de manera muy clara. Los detalles finos —como el nombre exacto de una columna, un formato visual o una decisión puntual de interfaz— no tienen por qué quedar todos dentro de la historia.

Esos detalles pueden aparecer en:

* documentación interna del equipo;  
* pruebas de aceptación automatizadas;  
* conversaciones específicas de refinamiento.

La idea importante es que **la historia no debe cargar todo el peso del detalle**. La historia expresa intención; los criterios acotan; y los detalles finos se completan durante conversación y validación.

## **19\) Pruebas de aceptación**

El ppt diferencia correctamente entre historia, criterios y pruebas. Las **pruebas de aceptación**:

* expresan detalles concretos que surgen de la conversación;  
* complementan la user story;  
* ayudan a verificar si lo esperado efectivamente ocurre.

La distinción importante es:

* **User story** \= intención y valor;  
* **criterios de aceptación** \= límites y condiciones;  
* **pruebas de aceptación** \= casos concretos que verifican esas condiciones.

Esto ayuda mucho a no confundir el nivel de abstracción de cada artefacto.

## **20\) INVEST: cómo reconocer una buena historia**

El ppt presenta el modelo **INVEST** de Bill Wake. Una buena historia debería ser:

* **Independent**: implementable en un orden razonable sin depender totalmente de otras;  
* **Negotiable**: negociable en su contenido, no rígida como contrato cerrado;  
* **Valuable**: valiosa para el usuario o el negocio;  
* **Estimatable**: entendible lo suficiente como para poder estimarse;  
* **Small**: lo bastante pequeña como para entrar en una iteración;  
* **Testable**: verificable mediante pruebas o criterios claros.

INVEST funciona como un filtro de calidad para las historias. Ayuda a detectar cuándo una historia todavía es demasiado grande, ambigua, dependiente o poco clara.

**Las user stories no necesitan cumplir completamente con INVEST desde el momento en que aparecen en el backlog**, porque muchas veces comienzan como ideas más amplias, **temas** o **épicas**, y se refinan progresivamente a medida que ganan prioridad. Sin embargo, cuando una historia se acerca al momento de ser incluida en una **iteración** o **sprint**, debería cumplir **INVEST** en un grado suficiente como para poder **priorizarse**, **estimarse**, **implementarse** y **validarse** razonablemente. En ese sentido, **INVEST funciona como un criterio de calidad especialmente importante en las historias cercanas a implementación** y se relaciona de manera directa con la **Definition of Ready**, ya que ayuda a decidir cuándo una historia está lo bastante clara, pequeña, valiosa y testeable como para entrar efectivamente al trabajo del equipo.

### **Definition of Ready (DoR)**

La **Definition of Ready** es un conjunto de criterios acordados por el equipo para decidir cuándo una historia está **suficientemente preparada** como para entrar en una iteración o sprint.

Aunque no forma parte formal del núcleo de Scrum 2020, en la práctica sirve para verificar que una historia:

* tiene valor claro;  
* se entiende razonablemente;  
* tiene criterios de aceptación;  
* puede estimarse;  
* es lo bastante pequeña;  
* no tiene dependencias críticas invisibles.

La DoR se relaciona mucho con **INVEST**, porque si una historia no es suficientemente independiente, estimable, pequeña o testeable, normalmente todavía no está lista para entrar.

### **Definition of Done (DoD)**

La **Definition of Done** es el conjunto de criterios acordados por el equipo para decidir cuándo una historia está **realmente terminada**.

En términos generales, la DoD ayuda a responder si una historia:

* fue implementada;  
* fue probada;  
* cumple sus criterios de aceptación;  
* y está en condiciones de presentarse como incremento real.

Mientras la DoR habla de cuándo una historia está **lista para empezar**, la DoD habla de cuándo está **lista para mostrarse o aceptarse**.

## **21\) Spikes**

El ppt define los **spikes** como un tipo especial de historia usado para reducir **riesgo** e **incertidumbre**. Los clasifica en:

* **técnicos**;  
* **funcionales**.

### **Spikes técnicos**

Sirven para investigar enfoques técnicos, performance, tecnologías, decisiones de compra o implementación.

### **Spikes funcionales**

Sirven para explorar cómo el usuario interactuará con el sistema, muchas veces mediante prototipos o experimentos.

La idea importante es que el spike no existe para entregar funcionalidad final, sino para producir **aprendizaje** que permita tomar mejores decisiones.

## **21.1) Lineamientos para spikes**

El ppt y la bibliografía complementaria dejan claro que los **spikes** deben entenderse como historias especiales orientadas a **reducir incertidumbre** y **administrar riesgo**, no como una forma habitual de trabajar. Por eso, sus lineamientos principales son que sean **estimables**, **demostrables** y **aceptables**. Esto significa que, igual que otras historias, deben poder ponerse en el backlog, estimarse y dimensionarse para entrar en una iteración. Sin embargo, su resultado no suele ser código funcionando, sino **información útil para decidir**, un **prototipo**, un **storyboard**, una **prueba de concepto** o alguna solución parcial que permita comprender mejor el problema y dimensionar correctamente las historias que estaban ocultas detrás de la incertidumbre inicial.

Además, el resultado de un spike debe ser **demostrable** para el equipo. Esto le da visibilidad al trabajo de investigación, facilita que las decisiones técnicas o funcionales se compartan y fortalece la responsabilidad colectiva sobre el camino elegido. Del mismo modo, el spike debe ser **aceptable**, es decir, tiene que tener criterios que permitan al Product Owner o al equipo reconocer cuándo cumplió su propósito. En otras palabras, un spike no termina “cuando se investigó bastante”, sino cuando produjo la información suficiente para reducir la incertidumbre que justificó su existencia.

Otro lineamiento central es que el spike debe ser **la excepción y no la regla**. Toda user story contiene cierto nivel de incertidumbre y riesgo, y parte del trabajo normal del equipo consiste justamente en aprender a resolver esa incertidumbre dentro de cada iteración. Por eso, los spikes deberían reservarse para las **incógnitas más grandes o más críticas**, y utilizarse como **última opción**, especialmente cuando no alcanza con conversar, refinar o dividir la historia usando estrategias normales de *splitting*.

Finalmente, el material recomienda que, en general, el spike se implemente en una **iteración separada** de las historias resultantes. La razón es que planificar en la misma iteración tanto la investigación como las historias derivadas agrega demasiado riesgo, ya que todavía no se conoce con suficiente claridad qué se descubrirá. Solo si el spike es **pequeño**, **simple** y existe alta probabilidad de encontrar una solución rápidamente, puede aceptarse que el spike y la historia derivada convivan en la misma iteración. Aun así, la recomendación general es separarlos para reducir riesgo de planificación.

## **22\) Ideas que el ppt y la clase quieren dejar claras**

Las últimas diapositivas del ppt y el cierre de la clase remarcan una serie de ideas muy importantes:

* el análisis detallado debe diferirse hasta el momento más útil;  
* hasta entonces, conviene capturar requerimientos como historias;  
* las user stories no son requerimientos exhaustivos de software;  
* conviene avanzar de a un paso por vez, evitar la palabra “Y”;  
* hay que escribir desde la perspectiva del usuario;  
* no conviene forzar todo para que sea una historia;  
* el cambio es inevitable;  
* el usuario muchas veces descubre lo que quiere cuando ve funcionando lo que pidió;  
* los stakeholders no siempre son solo los visibles;  
* lo importante no es entregar un documento, sino una **solución con valor**.  
* la conversación es lo MÁS IMPORTANTE.

La gran conclusión de esta unidad es que los requerimientos ágiles no son una forma “más liviana” de hacer lo mismo que antes, sino una forma distinta de pensar la construcción del producto: menos apoyada en congelar conocimiento temprano, y más apoyada en **conversación**, **priorización**, **validación** y **aprendizaje progresivo**.

## **Qué estudiar sí o sí para el parcial**

Tenés que poder explicar bien:

* qué significa “ágil” y por qué no equivale a improvisación;  
* cuáles son los **4 valores** y los **12 principios** del Manifiesto Ágil;  
* por qué BRUF genera desperdicio;  
* qué son los requerimientos ágiles;  
* cómo cambian frente al enfoque tradicional;  
* tipos de requerimientos;  
* qué es una user story;  
* partes de una user story: tarjeta, conversación, confirmación;  
* forma “como rol / quiero / para”;  
* qué no son las user stories;  
* qué es el backlog y cómo se prioriza;  
* qué significa cortar historias en vertical;  
* modelado de roles, personas y proxies;  
* criterios de aceptación;  
* pruebas de aceptación;  
* INVEST;  
* Definition of Ready;  
* Definition of Done;  
* qué es un spike y cuándo usarlo;  
* diferencia entre tema, épica y user story.

## **Lecturas recomendadas para complementar**

### **Imprescindibles**

**1\. PPT 02**  
Es el esqueleto completo del tema. Ordena los conceptos y muestra qué cuestiones resalta la cátedra.

**2\. Mike Cohn – *User Stories Applied***  
Conviene especialmente para:

* overview de user stories;  
* card/conversation/confirmation;  
* acceptance tests;  
* INVEST;  
* role modeling;  
* gathering stories;  
* planificación con stories.

**3\. Leffingwell y Behrens – *A User Story Primer***  
Muy útil como lectura breve para fijar:

* user stories como expresión de intención;  
* estructura estándar;  
* card / conversation / confirmation;  
* acceptance criteria;  
* INVEST;  
* splitting y spikes.

### **Muy útiles**

**4\. Brooks – *No Silver Bullet***  
Sirve para reforzar la idea de que la parte más difícil del software es decidir correctamente qué construir.

**5\. Manifiesto Ágil y sus 12 principios**  
Importantes para entender la base conceptual sobre la que se apoyan requerimientos ágiles, priorización, conversación y adaptación.

## **Posibles preguntas de parcial, con respuesta modelo**

### **1\. ¿Qué son los requerimientos ágiles?**

Son una forma de gestionar requerimientos basada en valor, priorización continua, detalle progresivo y adaptación al cambio. No buscan cerrar toda la especificación al inicio, sino descubrir y refinar lo necesario a medida que el producto evoluciona.

### **2\. ¿Por qué se critica el BRUF?**

Porque definir demasiado detalle demasiado temprano genera desperdicio, demora aprendizaje y fija supuestos antes de tener feedback real.

### **3\. ¿Qué es una user story?**

Es una expresión breve de intención que describe algo que el sistema debe hacer para un usuario o comprador. Su sentido completo surge de la tarjeta, la conversación y la confirmación.

### **4\. ¿Cuáles son las partes de una user story?**

Tarjeta, conversación y confirmación.

### **5\. ¿Qué forma suele tener una historia?**

Como `<rol>`, yo quiero/puedo `<actividad>`, de forma tal que `<valor>`.

### **6\. ¿Qué son los criterios de aceptación?**

Son condiciones que delimitan la historia, ayudan a compartir entendimiento, derivar pruebas y saber cuándo la historia tiene suficiente funcionalidad para entregar valor.

### **7\. ¿Qué diferencia hay entre criterios y pruebas de aceptación?**

Los criterios expresan condiciones generales de satisfacción; las pruebas son los casos concretos que verifican si esas condiciones se cumplen.

### **8\. ¿Qué significa INVEST?**

Que una buena historia debe ser independiente, negociable, valiosa, estimable, pequeña y testeable.

### **9\. ¿Qué significa que una historia sea una porción vertical?**

Que atraviesa las distintas capas del sistema y entrega funcionalidad usable de punta a punta, en lugar de cortar solo una capa técnica.

### **10\. ¿Qué es un spike?**

Es un ítem especial del backlog usado para reducir incertidumbre o riesgo técnico/funcional antes de comprometer una implementación.

### **11\. ¿Qué es la Definition of Ready?**

Es un conjunto de criterios que permite decidir si una historia está suficientemente preparada como para entrar en una iteración.

### **12\. ¿Qué es la Definition of Done?**

Es un conjunto de criterios que permite decidir si una historia está realmente terminada y en condiciones de presentarse o aceptarse.

## **Mini resumen final para memorizar**

Los **requerimientos ágiles** parten de la idea de que en software no conviene congelar todo el detalle desde el comienzo, porque el cambio, la incertidumbre y el aprendizaje son inevitables. Por eso se trabaja con **user stories**, expresiones breves de intención que se completan con **conversación** y **aceptación**. Las historias se priorizan por **valor** en el backlog, se refinan **just in time**, se implementan como **porciones verticales** y se validan con **criterios** y **pruebas de aceptación**. Para que sean útiles, conviene que cumplan **INVEST**. Cuando todavía hay demasiada incertidumbre, se utilizan **spikes** para investigar antes de comprometer una implementación. La **Definition of Ready** ayuda a saber cuándo una historia está lista para empezar, y la **Definition of Done** ayuda a saber cuándo está realmente terminada.

---

# **PPT 03: Estimaciones Ágiles**

## **1\) Idea central del tema**

La idea de fondo del ppt es esta:

**en Agile se estima, pero con pragmatismo, no con dogmatismo, y mucho menos confundiendo estimación con promesa.** El propio ppt abre con esa postura: no hay que ser dogmático y lo importante es ser pragmático. Después remata con una advertencia muy fuerte: **si las estimaciones se usan como compromisos, son peligrosas y perjudiciales** para la organización. También dice que lo más valioso de estimar es **el proceso de hacerlo**, porque ahí aparecen dudas, comparaciones, factibilidad y conversación de equipo.

McConnell refuerza exactamente esa línea, pero con más precisión conceptual: distingue entre **estimate**, **target** y **commitment**. Para él, una estimación es una predicción; un target es un objetivo deseado del negocio; y un compromiso es una promesa concreta de entrega. Mezclar esas tres cosas arruina la estimación y también arruina la planificación.

Mike Cohn también va en esa dirección: dice que para planificar bien hay que separar al menos tres preguntas distintas: **qué tan grande es esto**, **cuándo estaría** y **cuánto puedo entregar para cierta fecha**. O sea, primero entender tamaño, después hablar de duración y recién después de calendario y alcance.

---

## **2\) Qué lugar ocupa la estimación en Agile**

El ppt no presenta la estimación como un ritual burocrático ni como una ciencia exacta. La presenta como una herramienta útil para varias cosas:

* detectar temprano si algo parece o no factible,  
* proteger al equipo,  
* y abrir conversaciones valiosas sobre el trabajo.

Esa idea conecta perfecto con McConnell. En el capítulo 1 explica que una buena estimación no es “decir un número” sino **expresar una predicción con incertidumbre**, y que los estimados de punto único suelen ser engañosos porque ocultan la probabilidad real de cumplimiento. También aclara que estimar no es planificar: la estimación debería ser un proceso analítico y relativamente imparcial; la planificación, en cambio, es un proceso orientado a objetivos.

Cohn suma otra pieza importante: la planificación ágil existe para ayudar a decidir **qué construir y para cuándo**, pero no lo puede hacer bien si antes no separa **tamaño** de **duración**. Esa separación es uno de los pilares conceptuales de este tema.

Entonces, una frase muy buena para examen sería:

**en Agile se estima para entender, comparar y planificar mejor, no para simular exactitud ni para obligar al equipo a cumplir un número inventado.**

---

## **3\) Qué se estima en Agile**

El ppt dice que las **features/stories** se estiman usando una medida de **tamaño relativo** conocida como **story points**, y marca dos ideas esenciales:

* las medidas relativas no son absolutas,  
* y los story points **no son tiempo**.

Eso es central. En vez de preguntar directamente “¿cuántas horas son?”, el enfoque ágil pregunta algo más razonable:

* ¿qué tan grande es esta story comparada con otra?,  
* ¿qué tan compleja parece?,  
* ¿qué tanto riesgo o duda tiene?,  
* ¿qué peso relativo tiene dentro del backlog?

Cohn explica exactamente eso cuando introduce story points: los presenta como una forma de estimar **size** sin mezclarlo todavía con calendario. Incluso en la organización del libro deja explícito que primero trabaja **estimating size** y recién después **scheduling**.

---

## **4\) Por qué se usa estimación relativa**

El ppt defiende la **estimación relativa** con una idea muy simple pero potente:

* las personas estiman mal en términos absolutos,  
* pero somos bastante mejores comparando cosas,  
* comparar suele ser más rápido,  
* genera mejor dinámica grupal,  
* y usa mejor el tiempo de análisis de las stories.

El ejemplo visual de la diapositiva de los perros muestra eso perfecto: no hace falta medir con exactitud científica cuánto mide cada uno para saber cuál es más grande y cuál es más chico. Lo importante es la relación.

Cohn usa un ejemplo parecido cuando presenta story points: dice que, igual que cuando uno pide una gaseosa chica, mediana o grande sin saber los mililitros exactos, en software muchas veces alcanza con saber si algo es más chico, parecido o mucho más grande que otra cosa.

Entonces, el razonamiento completo sería:

**la estimación relativa se usa porque comparar tamaños es cognitivamente más confiable que adivinar tiempos exactos.**

---

## **5\) Qué significa “tamaño”**

El ppt define tamaño como una medida de la **cantidad de trabajo necesaria para producir una feature/story**, y agrega que el tamaño indica:

* cuán compleja es,  
* cuánto trabajo requiere,  
* y cuán grande es.

Pero ojo: más adelante el mismo material aclara que **tamaño no es esfuerzo**. Entonces conviene entender “tamaño” no como “horas reales”, sino como una valoración relativa que mezcla varias cosas:

* complejidad,  
* trabajo involucrado,  
* riesgo o duda,  
* y magnitud general de la story.

Cohn lo dice con más prolijidad: un story point representa el **overall size** de una historia, y ese tamaño es una mezcla de esfuerzo, complejidad, riesgo y otros factores. No hay una fórmula exacta; es un juicio relativo del equipo.

Las diapositivas de los “bubbles” lo muestran muy bien: cada historia tiene distinta combinación de **duda**, **complejidad** y **esfuerzo**, y de esa combinación sale el tamaño relativo. En el ejemplo, Story 1 y Story 2 terminan ambas como “M” o “5”, mientras Story 3 termina como “XL” o “13”.

---

## **6\) Tamaño vs esfuerzo vs tiempo**

Este es uno de los núcleos más importantes del tema.

El ppt dice explícitamente:

**Tamaño NO ES esfuerzo**. Además explica que las estimaciones basadas en tiempo son más propensas a error por diferencias en:

* habilidades,  
* conocimiento,  
* asunciones,  
* experiencia,  
* familiaridad con el dominio.

Entonces hay que separar tres cosas:

* **tamaño**: cuán grande/compleja/riesgosa es la story en términos relativos,  
* **esfuerzo**: cuánto trabajo real le cuesta al equipo hacerla,  
* **tiempo/duración**: cuántos días, semanas o iteraciones termina llevando.

No son equivalentes.

Cohn desarrolla exactamente esta separación en la Parte II de su libro. Primero habla de **estimating size**, recién después de **duration** y **schedule**. Incluso usa el ejemplo de mover una montaña de tierra: primero estimás tamaño, después convertís ese tamaño en duración.

McConnell también ayuda mucho acá porque separa **size**, **effort** y **schedule** como problemas de estimación distintos. En el índice se ve que dedica capítulos específicos a estimar tamaño, esfuerzo y cronograma, justamente porque no son lo mismo.

Una forma corta y correcta de decirlo en examen sería:

**primero estimamos tamaño relativo; después, con datos reales del equipo, derivamos duración.**

---

## **7\) Qué es un Story Point**

El ppt define el story point como una **unidad de medida específica del equipo** para complejidad, riesgo y esfuerzo; algo así como un “kilo” interno del sistema de medición del equipo. También dice que el story point da idea del “peso” de la story y que la complejidad tiende a crecer en forma exponencial.

Hay dos consecuencias importantes:

### **1\. Es específica del equipo**

Los story points **no son universales**. El “5” de un equipo no tiene por qué equivaler al “5” de otro. Sirven para comparar trabajo **dentro del mismo equipo y contexto**.

### **2\. No representan tiempo**

Un 8 no significa ocho horas ni ocho días. Significa que esa historia se considera más grande que una de 5 y menos grande que una de 13, dentro de la escala que usa ese equipo.

Cohn lo explica muy parecido: lo importante no es el valor absoluto del número, sino la relación entre historias. Una historia de 2 debería ser aproximadamente el doble de una de 1 y dos tercios de una de 3\. Lo que importa es la **proporción relativa**, no el número desnudo.

---

## **8\) Escalas posibles para estimar**

El ppt enumera varias formas de expresar tamaño:

* números del 1 al 10,  
* talles de remera: S, M, L, XL, XXL,  
* serie 2ⁿ,  
* Fibonacci: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, etc.

Y agrega una regla importante:

**una vez elegida la escala, no se cambia**, porque cambiarla sería como cambiar el metro patrón y perder comparabilidad.

Este ppt claramente simpatiza con **Fibonacci**, y tiene sentido. A medida que una historia crece, también crece la incertidumbre y la dificultad de distinguir tamaños con precisión fina. Fibonacci refleja bien esa lógica porque ensancha los saltos entre categorías.

Cohn también asocia story points con escalas relativas y dedica parte del libro a técnicas como story points e ideal days. Además, cuando explica las técnicas de estimación, muestra por qué no conviene obsesionarse con precisión falsa en tamaños grandes.

---

## **9\) Velocidad (Velocity)**

El ppt define la **velocidad** como una métrica del progreso de un equipo. Dice que se calcula sumando los story points de las user stories que el equipo **completa en la iteración**. Aclara además que:

* se cuentan solo las stories **completas**,  
* no las parcialmente completas,  
* y la velocidad ayuda a corregir errores de estimación.

Esto es muy importante: la velocidad no mide “horas gastadas”, ni “esfuerzo del sprint”, ni “cantidad de gente”, sino **puntos terminados**. O sea, capacidad empírica observada.

Cohn dice lo mismo cuando explica velocity: es la medida del ritmo del equipo, calculada a partir de los puntos de las historias terminadas. Esa velocidad observada permite proyectar futuras iteraciones y ajustar el plan sin necesidad de reestimar todo el backlog a cada rato.

---

## **10\) Para qué sirve la velocidad**

La velocidad sirve para varias cosas:

* ver cuánto puede entrar razonablemente en una iteración,  
* proyectar releases,  
* aprender la capacidad real del equipo,  
* y corregir errores de estimación inicial.

Cohn explica algo muy valioso sobre esto: una vez que tenés tamaño estimado y velocidad observada, la duración del proyecto deja de ser una intuición pura y pasa a ser una derivación razonada. Si el backlog suma cierta cantidad de puntos y el equipo viene sosteniendo cierta velocidad, podés proyectar cuántas iteraciones faltan.

Entonces, una frase muy buena para recordar es:

**los story points estiman tamaño; la velocidad conecta ese tamaño con la realidad del equipo.**

---

## **11\) Por qué la velocidad “corrige” errores**

El ppt dice que la velocidad corrige errores de estimación. Eso no significa que mágicamente arregle números mal puestos, sino que ayuda a que el plan converja hacia la realidad aunque la estimación inicial haya sido imperfecta.

Cohn lo explica muy bien con su lógica de story points: como el equipo aprende su velocidad real en las primeras iteraciones, aunque haya habido error en el tamaño absoluto percibido, el sistema se autocorrige en la proyección. Lo importante es que las proporciones entre historias sean razonables; después la velocidad absorbe parte del desvío.

Esto es una diferencia fuerte frente a enfoques más tradicionales, donde una mala estimación en horas puede contaminar mucho más toda la planificación.

---

## **12\) Planning Poker / Poker Estimation**

La segunda mitad del ppt propone como método principal **Planning Poker**. Lo presenta como una técnica popularizada por Mike Cohn que combina:

* opinión de experto,  
* analogía,  
* y desagregación.

También dice algo importante sobre quiénes participan: **los desarrolladores**. Y lo justifica con una idea muy sana:

**las personas más competentes para resolver una tarea deberían ser quienes la estimen.**

Eso es coherente con McConnell también. En sus capítulos sobre expert judgment individual y grupal, y más todavía al hablar de Wideband Delphi, deja claro que la estimación mejora cuando participan personas con conocimiento real del trabajo y cuando el juicio experto se estructura y se revisa.

---

## **13\) Qué lógica tiene Planning Poker**

Planning Poker no es solo “votar con cartas”. Tiene bastante sentido metodológico.

### **1\. Reduce sesgos de arrastre**

Al elegir cartas en simultáneo, se evita que el primero que habla condicione a los demás demasiado pronto.

### **2\. Obliga a explicitar diferencias**

Cuando no coinciden los valores, la técnica pide discutir especialmente las estimaciones más altas y más bajas. Ahí suelen aparecer:

* supuestos distintos,  
* riesgos técnicos no vistos por todos,  
* interpretaciones distintas de la historia,  
* dudas de negocio que el PO tiene que aclarar.

### **3\. Convierte la estimación en conversación de entendimiento**

Esto conecta de nuevo con lo que el ppt decía al principio: el mayor beneficio no es el número final sino el proceso de estimar.

Cohn dedica un capítulo entero a estas técnicas y ubica Planning Poker justamente como una forma colaborativa de estimación de tamaño.

---

## **14\) Pasos del Planning Poker**

El ppt describe bastante bien la mecánica.

### **Prerrequisitos**

* lista de features/stories a estimar,  
* cada estimador con su mazo de cartas.

### **Pasos**

1. Se elige una **base story** o historia canónica contra la que comparar.  
2. La story a estimar se lee al equipo.  
3. Los estimadores la discuten y le hacen al Product Owner todas las preguntas necesarias.  
4. Cada uno elige una carta y la pone boca abajo.  
5. Todas las cartas se revelan al mismo tiempo.  
6. Si todos coinciden, ese es el estimado.  
7. Si no coinciden, se discuten sobre todo los extremos y se vuelve a votar.  
8. Luego se repite con la siguiente story, comparándola contra la historia base.

La presencia de una **historia base** es importante porque le da estabilidad relativa a la escala del equipo.

---

## **15\) Fibonacci y por qué aparece tanto**

El ppt dedica una diapositiva a Fibonacci y recuerda la secuencia clásica. Eso no está puesto solo por cultura general, sino porque Fibonacci suele usarse en Planning Poker para expresar tamaños relativos crecientes con separación no lineal.

La razón conceptual es que, a mayor tamaño, también aumenta la incertidumbre. Entonces no tiene mucho sentido distinguir con demasiada precisión entre historias grandes. Es más sano pasar de 5 a 8, de 8 a 13, de 13 a 21, etc.

Cohn, al trabajar story points y técnicas de estimación, va en esta línea: una estimación relativa útil no necesita exactitud milimétrica, sino categorías suficientemente discriminantes para apoyar decisiones.

---

## **16\) Cómo “decodificar” los números**

La diapositiva 20 del ppt es muy útil para entender cómo leer los valores en la práctica:

* **0**: no hay idea clara del producto o funcionalidad en este punto.  
* **1/2 o 1**: funcionalidad muy pequeña, usualmente cosmética.  
* **2–3**: funcionalidad pequeña a mediana; ideal.  
* **5**: funcionalidad media; también deseable.  
* **8**: funcionalidad grande; todavía posible, pero conviene preguntarse si no se puede dividir.  
* **13**: ya hay que explicar seriamente por qué no se puede partir.  
* **20**: hay que preguntarse cuál es la razón de negocio para mantener algo así de grande y por qué no se divide.  
* **40**: no es razonable meter eso en un sprint.  
* **100**: señal de que algo está muy mal planteado.

La enseñanza de fondo es clarísima:

**cuando una story da muy grande, normalmente no solo indica más trabajo; también indica peor refinamiento, más incertidumbre y peor capacidad de planificación.**

Eso conecta directo con el ppt 02 y el modelo **INVEST**, sobre todo con la S de **Small** y la E de **Estimable**. Una historia demasiado grande o difusa deja de ser una buena historia.

---

## **17\) Qué aporta McConnell para complementar este tema**

Aunque el ppt está muy orientado a story points, velocity y poker, McConnell te aporta profundidad conceptual muy útil para parcial y para entender mejor el tema.

### **a) Estimate ≠ target ≠ commitment**

Ya lo vimos, pero es de las mejores ideas para llevarte de este tema. Una estimación no es un compromiso. Una fecha objetivo del negocio tampoco es automáticamente un estimado realista.

### **b) Las estimaciones son probabilísticas**

McConnell insiste en que una estimación de punto único es engañosa porque siempre tiene una probabilidad implícita. Un número solo, sin rango ni probabilidad, suele ser un target disfrazado de estimate.

### **c) Cone of Uncertainty**

En el índice y en el capítulo 4 aparece el **Cone of Uncertainty**: al comienzo del proyecto la variabilidad es mucho más grande, y recién se va achicando a medida que se aprende. Esto encaja perfecto con el enfoque ágil de inspeccionar y adaptar.

### **d) Error de estimación y política organizacional**

McConnell también dedica secciones enteras a incertidumbre, optimismo infundado, subjetividad, estimaciones “off-the-cuff”, precisión injustificada y política alrededor de los números. Eso sirve mucho para entender por qué estimar no es solo un problema técnico.

---

## **18\) Qué aporta Mike Cohn para complementar este tema**

Cohn es probablemente el complemento más directo del ppt.

### **a) Separar tamaño y duración**

Esto es casi la tesis central de la Parte II del libro. Primero se estima tamaño; después se transforma eso en duración.

### **b) Story points e ideal days**

Cohn no se limita a story points; también presenta **ideal days** como otra forma de estimar tamaño. Igual, la lógica es parecida: no mezclar demasiado pronto estimación de tamaño con el calendario real.

### **c) Velocity**

Desarrolla la idea de velocidad como medida del ritmo real del equipo y base para release planning.

### **d) Planning failures**

En sus primeros capítulos explica por qué fallan los enfoques tradicionales: planificar por actividades en vez de por features, multitasking, ignorar incertidumbre y convertir estimados en compromisos. Todo eso explica muy bien por qué Agile propone otra lógica.

---

## **19\) Qué quiere dejarte este ppt sí o sí**

Si lo tuviera que destilar en pocas ideas, serían estas:

1. **No usar estimaciones como compromisos rígidos.**  
2. **Estimar en relativo, no directamente en horas.**  
3. **Story points no son tiempo.**  
4. **Tamaño no es esfuerzo ni duración.**  
5. **La discusión grupal de estimación vale mucho más que el numerito solo.**  
6. **La velocidad se calcula con historias terminadas, no empezadas.**  
7. **Los números grandes son señales de alerta para dividir o repensar.**  
8. **Agile sigue siendo empírico: inspeccionar y adaptar es obligatorio.**

---

# **Qué estudiar sí o sí para el parcial**

Tenés que poder explicar bien, con tus palabras:

* por qué es peligroso usar estimaciones como compromiso,  
* diferencia entre **estimación**, **target** y **commitment**,  
* por qué se usa estimación relativa,  
* qué significa **tamaño**,  
* diferencia entre **tamaño**, **esfuerzo** y **tiempo**,  
* qué es un **story point**,  
* por qué no representa horas,  
* qué escalas se pueden usar,  
* por qué Fibonacci tiene sentido,  
* qué es la **velocidad**,  
* cómo se calcula,  
* por qué solo cuenta trabajo terminado,  
* qué es **Planning Poker**,  
* quiénes deben estimar,  
* cómo funciona el método,  
* y cómo interpretar valores grandes como 8, 13, 20, 40 o 100\.

---

# **Lecturas recomendadas para complementar**

## **Imprescindibles**

### **1\. PPT 03**

Es el resumen más directo, corto y orientado a lo que probablemente les importe en clase: story points, tamaño relativo, velocidad y planning poker.

### **2\. Mike Cohn – *Agile Estimating and Planning***

Es el mejor complemento para esta unidad. En la introducción ya deja claro que el libro trata de hacer ágiles a la estimación y a la planificación mismas, y en la Parte II separa tamaño de duración, trabajando story points, ideal days y técnicas de estimación como planning poker.

### **3\. Steve McConnell – *Software Estimation***

Muy bueno para fijar conceptos más profundos: qué es una estimación de verdad, por qué no hay que confundirla con un compromiso, de dónde sale el error de estimación, cómo presentar rangos, cómo pensar incertidumbre y por qué la política organizacional contamina tanto este tema.

---

## **Muy útil como conexión con lo anterior**

### **4\. Mike Cohn – relación con User Stories**

No hace falta leer todo ahora, pero tené presente que estimar bien depende de tener historias más o menos refinadas. Si la story es gigante, ambigua o mal escrita, el problema no es solo de estimación: es de backlog.

---

# **Posibles preguntas de parcial con respuesta modelo**

## **1\. ¿Qué es un story point?**

Es una unidad relativa de tamaño usada por un equipo para estimar historias o features considerando complejidad, trabajo involucrado, riesgo e incertidumbre. No representa tiempo directo.

## **2\. ¿Por qué en Agile se prefiere estimar en relativo?**

Porque las personas comparan mejor de lo que estiman en términos absolutos. La estimación relativa es más rápida, más útil para el equipo y suele generar mejor discusión que intentar adivinar horas exactas desde el inicio.

## **3\. ¿Tamaño es lo mismo que esfuerzo?**

No. El tamaño es una medida relativa de cuán grande, compleja o riesgosa es una historia. El esfuerzo y el tiempo dependen además de experiencia, habilidades, conocimiento del dominio y contexto del equipo.

## **4\. ¿Qué es la velocidad?**

Es la métrica del progreso del equipo, calculada como la suma de los story points de las historias completas en una iteración. No incluye trabajo parcialmente terminado.

## **5\. ¿Para qué sirve la velocidad?**

Sirve para observar la capacidad real del equipo, ajustar planes futuros, corregir errores de estimación inicial y proyectar la duración de releases o proyectos.

## **6\. ¿Qué es Planning Poker?**

Es una técnica colaborativa de estimación en la que los desarrolladores discuten una historia, eligen en simultáneo una carta con su estimación y, si hay diferencias, conversan especialmente los extremos hasta llegar a un valor razonable.

## **7\. ¿Quiénes deben estimar?**

Principalmente quienes van a realizar el trabajo, porque son quienes mejor pueden valorar complejidad, riesgo y tamaño relativo. El Product Owner aclara necesidades y contexto de negocio, pero no debería imponer el número técnico.

## **8\. ¿Qué significa que una historia sea 13 o 20 puntos?**

Es una señal de alerta. Probablemente sea una historia demasiado grande, incierta o mal partida. Antes de meterla en un sprint conviene preguntarse seriamente si no debe dividirse.

## **9\. ¿Qué diferencia hay entre estimación, target y commitment?**

La estimación es una predicción; el target es un objetivo de negocio; el compromiso es una promesa de entrega. Confundir estas tres cosas genera malas decisiones y presiones dañinas sobre el equipo.

## **10\. ¿Qué mensaje general deja este tema?**

Que estimar es útil cuando se hace con pragmatismo, en términos relativos, aceptando incertidumbre y usando la información real del equipo para adaptar el plan. Se vuelve dañino cuando se transforma en falsa precisión o en compromiso rígido.

---

# **Mini resumen final para memorizar**

En Agile, las estimaciones no se usan para fingir exactitud sino para entender mejor el trabajo, detectar riesgos y planificar de manera adaptativa. Por eso se estima en tamaño relativo mediante story points y no directamente en horas. El tamaño de una historia combina complejidad, trabajo e incertidumbre, pero no equivale a tiempo. La duración se proyecta recién cuando ese tamaño se combina con la velocidad observada del equipo. Una técnica típica para estimar es Planning Poker, donde el equipo compara historias usando una escala como Fibonacci y discute diferencias hasta llegar a un consenso razonable. Todo esto se apoya en una idea central: estimar no es comprometerse; es aprender lo suficiente como para poder decidir mejor.

---

# **PPT 04: Gestión de Productos**

## **1\) Idea central del tema**

Este ppt cambia el foco.

Hasta ahora veníamos viendo ingeniería, requisitos ágiles, user stories y estimación. Acá la materia empieza a mirar el software como **producto**, no solo como “algo para desarrollar”. El mensaje central es:

**el éxito no depende de construir muchas funcionalidades, sino de construir valor real para usuarios reales.**

Eso se ve clarísimo en varias diapositivas del deck nuevo. En la **página 3** aparece una idea fuerte: el mayor riesgo no es fallar técnicamente, sino “construir a la perfección algo que nadie quiere”. Y en la **página 4** se refuerza con el dato visual de que alrededor del **45% de las características de un sistema típico nunca se usan**. El mensaje es brutal: producir más no implica entregar más valor.

El deck viejo va por la misma línea. En la **página 4** muestra el famoso reparto de uso de funcionalidades, donde una gran porción queda en “never”, y después, en las definiciones de MVP, insiste en que lo importante es **aprender validando con comportamiento real**, no enamorarse de un backlog enorme.

Eric Ries lo plantea como problema de desperdicio: una startup fracasa cuando construye cosas que nadie quiere. Para él, el progreso verdadero no es cuántas features hiciste, sino cuánto **aprendizaje validado** generaste.

---

## **2\) Qué quiere enseñar “Gestión de Productos”**

La materia, en este ppt, te quiere sacar del enfoque puramente técnico.

No alcanza con:

* programar bien,  
* estimar bien,  
* cumplir tareas,  
* ni tener arquitectura prolija.

Todo eso importa, pero si el producto no resuelve una necesidad real o no logra adopción, no alcanza.

La **página 5** del ppt viejo y la **página 20** del ppt nuevo muestran esto como una “grieta” o “brecha” entre dos mundos:

* el mundo **focalizado en tareas / características / producto**,  
* y el mundo **focalizado en experiencias / gente / actividades / contexto**.

La evolución que plantea el material es esta:

1. primero el producto tiene que ser **funcional / útil**,  
2. después **confiable**,  
3. después **usable**,  
4. luego **conveniente**,  
5. después **placentero**,  
6. y finalmente **significativo**.

O sea: no se trata solo de “hacer features”, sino de ir construyendo una experiencia con valor creciente.

---

## **3\) Por qué no alcanza con construir mucho**

Una de las ideas más importantes del tema aparece en el dato del **45%**.

El deck nuevo, en las **páginas 3 y 4**, insiste en que cerca de la mitad de las funcionalidades desarrolladas en productos de software típicos no se usan nunca. El mensaje que acompaña ese dato dice que escribir código no es sinónimo de crear valor, y que el éxito no se mide por cantidad de funcionalidades entregadas sino por adopción real del cliente.

El deck viejo lo plantea con otra estética, pero igual contenido: en la **página 4** se ve el gráfico donde solo una porción muy chica se usa “always” y una gran porción queda en “never”.

Desde Lean Startup, esto se interpreta como **waste**: desperdicio. Ries dice que todo esfuerzo que no contribuye a descubrir qué quieren realmente los clientes es, en una startup, una forma de desperdicio.

Entonces, una frase de parcial muy buena sería:

**en gestión de productos, construir más funcionalidades no implica crear más valor; de hecho, puede aumentar el desperdicio si esas funcionalidades no son adoptadas por los usuarios.**

---

## **4\) Ciclo de vida del producto**

El deck viejo arranca preguntando por qué creamos productos y muestra el **ciclo de vida del producto** en la **página 3**:

* introducción,  
* crecimiento,  
* madurez,  
* declive.

El deck nuevo recupera eso en la **página 4** al lado del gráfico del 45%, mostrando la curva de ventas/beneficios a lo largo del tiempo.

Esto sirve para entender dos cosas:

1. un producto no es estático; evoluciona,  
2. la gestión de producto no termina cuando lanzás la primera versión.

Por eso más adelante el ppt mete conceptos como MVP, MMF, MMP, MMR y roadmap: porque un producto se construye y escala por etapas, no de una sola vez.

---

## **5\) Lean Startup como marco conceptual**

El deck nuevo, en la **página 6**, mete explícitamente el ciclo **Construir – Medir – Aprender** y lo presenta como antídoto frente a la “audacia del cero”: esa fantasía de esperar a que todo esté perfecto antes de lanzar. También dice que postergar el lanzamiento aumenta aislamiento y riesgo de fracaso.

Ries es todavía más claro. Define cinco principios, pero para esta unidad importan sobre todo tres:

* las startups existen en contextos de **incertidumbre extrema**,  
* el objetivo central no es producir cosas sino generar **aprendizaje validado**,  
* el circuito fundamental es **Crear – Medir – Aprender**.

En el libro también insiste con algo muy útil para parcial:

**un experimento no es una maqueta decorativa; es una forma de poner a prueba hipótesis de negocio con el menor esfuerzo posible.**

---

## **6\) La “audacia del cero”**

La **página 7** del deck nuevo habla del “dilema del lanzamiento” y contrapone dos cosas:

* la fantasía de tener **0 ingresos y 0 clientes**, que invita a imaginar éxito futuro,  
* contra el costo real del retraso: más desperdicio, menos feedback temprano y mayor riesgo de construir algo que nadie quiere.

Ries usa una idea muy parecida en Lean Startup: dice que muchas organizaciones prefieren seguir con “cero” porque los números chicos incomodan. Cero permite fantasear; números pequeños obligan a enfrentar realidad. Pero retrasar el contacto con el mercado te quita justamente lo que más necesitás: aprendizaje real.

Entonces, el mensaje es:

**el producto no debería esperar a estar perfecto; debería salir lo antes posible en una forma lo suficientemente útil como para poner a prueba hipótesis reales.**

---

## **7\) Qué es un MVP**

Acá aparece el concepto central del tema.

El deck viejo define MVP en la **página 19** con la formulación clásica de Eric Ries: una versión de un nuevo producto que permite recopilar la máxima cantidad de aprendizaje validado sobre clientes con el menor esfuerzo. También aclara que el aprendizaje vale más si observás lo que la gente hace con el producto que si solo le preguntás qué haría.

En la **página 20**, agrega tres rasgos prácticos del MVP:

* tiene suficiente valor para que la gente quiera usarlo o comprarlo inicialmente,  
* demuestra suficiente beneficio futuro para retener primeros usuarios,  
* y proporciona un ciclo de retroalimentación para guiar el desarrollo futuro.

El deck nuevo lo resume de manera más visual en la **página 7**: el MVP es un experimento diseñado para enfrentar la realidad lo antes posible. Requiere simplificación y evitar la sobreconstrucción.

Y AgileSparks, en el “dinosaurio lean/agile”, lo explica igual de bien: el MVP se construye para probar la hipótesis de valor única, incluyendo además algunas “table stakes” mínimas para que sea realmente viable como producto.

---

## **8\) Qué NO es un MVP**

Esto es re importante porque suele tomarse mal.

Un MVP **no es**:

* un producto de mala calidad,  
* una versión rota hecha “así nomás”,  
* un prototipo interno sin contacto real con usuarios,  
* ni la versión final pero recortada arbitrariamente.

La **página 22** del deck viejo enumera errores comunes:

* confundir MVP con MMF o MMP,  
* exagerar la parte “mínima” olvidando la “viable”,  
* y lanzar algo, llamarlo MVP, pero después no cambiarlo aunque el feedback lo contradiga.

Este punto conecta perfecto con Lean Startup: el MVP existe para **aprender**, así que si no cambia nada después del aprendizaje, perdiste el sentido del enfoque.

---

## **9\) MVP y propuesta de valor única (UVP)**

Tanto el deck nuevo como el viejo usan la lógica de la **Unique Value Proposition**.

La **página 12** del deck nuevo y las **páginas 6–10** del deck viejo muestran la idea del “dinosaurio”:

1. primero tenés una **hipótesis de valor único** o UVP,  
2. después construís un **MVP** para poner a prueba esa hipótesis,  
3. si la señal del mercado es confusa, seguís explorando o pivotás,  
4. si la señal se vuelve clara, podés avanzar a etapas posteriores de crecimiento.

Acá hay una idea clave:

**el MVP no existe solo para “salir rápido”, sino para validar si la propuesta de valor que imaginaste realmente tiene mercado.**

---

## **10\) Casos de validación temprana: Dropbox y Facebook**

El deck nuevo mete dos casos clásicos.

### **Dropbox**

En las **páginas 8 y 10** explica que el riesgo técnico de Dropbox era enorme por la complejidad de sincronización y sistemas distribuidos. En vez de construir toda la infraestructura primero, Drew Houston usó una **prueba de humo**: un video de 3 minutos mostrando cómo funcionaría el producto. El resultado fue que la lista de espera saltó de 5.000 a 75.000 personas casi de un día para el otro.

La enseñanza es clarísima:

**cuando el riesgo técnico de construir es muy alto, primero podés validar interés sin construir todo.**

### **Facebook**

En las **páginas 8 y 9**, el deck muestra el caso Facebook como validación de dos hipótesis:

* **hipótesis de valor**: si el producto le entrega valor al usuario,  
* **hipótesis de crecimiento**: cómo nuevos usuarios descubren el producto.

El material dice que en 2004 más del 50% de los usuarios registrados volvían al sitio todos los días, y que casi 3/4 del campus de Harvard lo usaba en un mes sin gastar en marketing. O sea: no validaron solo factibilidad técnica, validaron comportamiento humano.

Esto conecta directo con Lean Startup, donde Ries presenta precisamente la **hipótesis de valor** y la **hipótesis de crecimiento** como dos de las hipótesis más importantes a validar en un experimento temprano.

---

## **11\) Anatomía de un MVP efectivo**

La **página 11** del deck nuevo es excelente. Muestra dos pirámides:

* a la izquierda, cómo **no** hacerlo: producto fragmentado, con funcionalidad suelta pero sin coherencia,  
* a la derecha, cómo **sí** hacerlo: un producto cohesivo, aunque limitado.

El texto aclara que un MVP no habla solo de diseño técnico; debe enfocarse en la UVP y ofrecer lo mínimo indispensable para ser viable.

Esto es importantísimo:

**mínimo no significa incompleto de manera absurda; significa limitado, pero coherente.**

O sea, un MVP tiene que resolver algo real, aunque sea poco. No puede ser solo una pila de pedacitos inconexos.

---

## **12\) Qué pasa después del MVP: señal difusa o señal clara**

El deck viejo y el nuevo explican muy bien este momento.

Si lanzás el MVP y cada cliente potencial te dice:  
“está bueno, pero para usarlo necesito X”,  
y cada uno pide una X distinta, entonces todavía **no encontraste mercado**.

En cambio, si cada vez más respuestas apuntan a la **misma X**, ahí aparece una señal clara y conviene revisar la hipótesis cliente/problema/solución. Eso es el punto de partida del **pivot**.

La **página 13** del deck nuevo lo muestra visualmente:

* Fase A,  
* Fase B con señal dispersa,  
* Fase C con señal clara y pivot.

---

## **13\) Qué es un pivote**

Un pivote no es “tirar todo a la basura porque salió mal”.

En Lean Startup, pivotar es **cambiar de dirección con aprendizaje acumulado**. Ries lo contrapone a perseverar. No es improvisación total; es ajuste estratégico basado en evidencia.

El deck viejo lo explica simple en la **página 10**:  
estás ejecutando un pivote y construyendo **MVP2** centrado en la nueva hipótesis basada en el aprendizaje reciente generado por el MVP anterior.

Entonces:

**pivotar \= reformular hipótesis y producto en función de feedback real, no por capricho.**

---

## **14\) Matriz de priorización para decidir qué entra en el MVP**

La **página 14** del deck nuevo muestra una matriz muy útil para examen.

Cruza:

* urgente / no urgente  
* importante / no importante

Y propone cuatro cuadrantes:

1. **Hacer**: incluir en el MVP; son componentes críticos de la propuesta de valor única.  
2. **Planear**: cosas para beta o maduración posterior.  
3. **Delegar**: por ejemplo integraciones de terceros o APIs.  
4. **Eliminar**: remover del roadmap; puro desperdicio.

Esto es básicamente una herramienta de recorte orientada a foco. Sirve para no meter en el MVP todo lo que “suena copado”.

---

## **15\) MVF y MMF**

Una de las partes más ricas del tema es que no se queda solo en MVP.

### **MMF – Minimum Marketable Feature**

La **página 12** del deck viejo y la **página 15** del deck nuevo lo presentan como la pieza más pequeña de funcionalidad que puede liberarse aportando valor inmediato y crecimiento. Se usa cuando ya hay alta certeza comercial en un área.

### **MVF – Minimum Viable Feature**

La **página 14** del deck viejo y la **página 15** del deck nuevo lo muestran como una “feature pionera” o mini versión del MVP. Se usa cuando hay alto potencial pero también alta incertidumbre: querés aprender con una feature concreta antes de invertir más.

AgileSparks lo resume muy bien:

* **MMF** sirve cuando hay bastante certeza de valor,  
* **MVF** sirve cuando todavía estás explorando una zona incierta.

Una forma de memorizarlo:

* **MVP** valida producto/mercado en general,  
* **MVF** valida una feature incierta,  
* **MMF** entrega valor comercial claro en una zona ya entendida.

---

## **16\) MMP, MMR y cronología de lanzamiento**

El deck viejo, en las **páginas 17 y 18**, y el deck nuevo, en las **páginas 18 y 19**, muestran la secuencia entre varios “mínimos”:

* **MVP**: aprendizaje validado, aún no necesariamente un producto final,  
* **MMP**: Minimum Marketable Product, primer release digno para early adopters,  
* **MMR**: Minimum Marketable Release, incremento mínimo que aporta nuevo valor a usuarios,  
* y los MMF como bloques dentro de esos releases.

La **página 19** del deck nuevo es muy clara:

* Fase 1: MVP para aprendizaje,  
* Fase 2: MMP / MMR1 para lanzamiento,  
* Fase 3: MMR2 … MMRN para evolución.

Esto es importante porque mucha gente mete “MVP” para cualquier cosa. Y no es lo mismo:

* validar una hipótesis,  
* que lanzar un producto comercial mínimo,  
* que hacer releases incrementales de mercado.

---

## **17\) User Stories como corte técnico fino**

La **página 16** del deck nuevo y la **página 15** del deck viejo meten la idea del “corte geológico” o “dinosaurio carpaccio”.

La idea es esta:

aunque MVP, MVF o MMF sean “átomos” desde negocio, desde implementación todavía pueden ser grandes. Entonces se los corta en **rebanadas finas técnicas**, típicamente **user stories**, para reducir riesgo tecnológico y obtener feedback temprano de implementación.

Esto conecta perfecto con el PPT 02:

* los contenedores grandes son MVP / MMF / MVF,  
* y las unidades pequeñas operativas siguen siendo stories.

Muy buena conexión para parcial.

---

## **18\) MLP: Minimum Lovable Product**

Acá entra el agregado más nuevo del material.

El **MLP** no es el concepto clásico de Lean Startup. Es una evolución más reciente desde producto/UX que busca ir más allá de “viable” y apuntar a algo que los usuarios **amen desde el inicio**. Las fuentes que subiste lo definen como la versión más simple de un producto que no solo resuelve un problema, sino que además genera conexión emocional, delight o una experiencia agradable/diferencial.

El deck nuevo mete esta idea en la **página 20**, donde la “grieta de la experiencia” se cruza pasando de:

* productos / funcionalidades / tareas,  
* a gente / contexto / emoción / actividades.

### **Qué agrega el MLP frente al MVP**

Según las fuentes:

* MVP busca aprender con el menor esfuerzo,  
* MLP busca aprender **y además** lograr atención, interés, delight, apego o “amor” temprano del usuario.

GammaUX lo dice bien:  
el MLP es la versión que genera la máxima cantidad de amor por parte de los primeros usuarios con el mínimo esfuerzo.

LaunchNotes habla de tres componentes:

* funcionalidad,  
* usabilidad,  
* y delight.

Aha\! lo presenta como contrafigura del MVP clásico y dice que el objetivo no es que el usuario diga “bueno, funciona”, sino “esto está buenísimo”.

---

## **19\) Cómo tomar el MLP sin confundirte**

Acá conviene ser prolijo porque para examen puede haber trampa conceptual.

### **Lo canónico en esta unidad**

Lo más sólido y “base” del tema sigue siendo:

* Lean Startup,  
* aprendizaje validado,  
* MVP,  
* pivote,  
* hipótesis de valor y crecimiento.

### **Lo complementario / más moderno**

MLP aparece como una evolución o mirada de producto más orientada a:

* experiencia,  
* diseño,  
* diferenciación,  
* emoción,  
* retención y fidelidad temprana.

Entonces, yo lo estudiaría así:

**MVP** \= validar rápido con el menor esfuerzo.  
**MLP** \= además de validar, lograr que el usuario realmente disfrute o valore fuertemente la experiencia inicial.

No son exactamente enemigos; más bien son enfoques distintos según contexto.

---

## **20\) Cuándo tiene más sentido pensar en MVP y cuándo en MLP**

Con el material que subiste, se puede resumir así:

### **MVP tiene más sentido cuando:**

* hay mucha incertidumbre,  
* necesitás validar hipótesis urgente,  
* el mayor riesgo es construir algo que nadie quiere,  
* querés maximizar aprendizaje temprano y reducir desperdicio.

### **MLP tiene más sentido cuando:**

* el mercado está más competitivo,  
* la experiencia y diferenciación pesan mucho,  
* no alcanza con que el producto “zafe”,  
* querés captar y enamorar temprano a usuarios.

Userpilot incluso dice que un MLP puede ayudarte con reputación de marca, diferenciación y mejor feedback porque engancha mejor a los usuarios desde el arranque.

---

## **21\) Qué quiere dejarte este ppt sí o sí**

Si lo tuviera que destilar, las ideas madre son estas:

1. **El producto debe crear valor, no solo funcionalidades.**  
2. **Muchísimas features terminan sin usarse.**  
3. **Lean Startup propone Construir–Medir–Aprender para reducir desperdicio.**  
4. **El MVP es un experimento para validar hipótesis lo antes posible.**  
5. **El aprendizaje validado se basa en comportamiento real, no en opiniones sueltas.**  
6. **Si la señal de mercado es dispersa, todavía no hay encaje; si converge, puede venir un pivote.**  
7. **MVP, MVF, MMF, MMP y MMR no son sinónimos.**  
8. **Las user stories son el corte fino técnico para implementar esos contenedores de negocio.**  
9. **MLP agrega la idea de experiencia deseable o lovable, más allá de la mera viabilidad.**

---

# **Qué estudiar sí o sí para el parcial**

Tenés que poder explicar bien:

* por qué la gestión de producto no se mide por cantidad de funcionalidades,  
* qué significa el dato del 45% de funcionalidades no usadas,  
* diferencia entre foco en tareas y foco en experiencias,  
* ciclo de vida del producto,  
* qué es Lean Startup,  
* qué es aprendizaje validado,  
* qué es el ciclo Construir–Medir–Aprender,  
* qué es un MVP,  
* qué NO es un MVP,  
* para qué sirven las hipótesis de valor y crecimiento,  
* qué muestran los casos Dropbox y Facebook,  
* qué es un pivote,  
* cómo decidir qué entra en un MVP,  
* diferencia entre MVP, MVF, MMF, MMP y MMR,  
* qué rol cumplen las user stories dentro de ese esquema,  
* y qué agrega el concepto de MLP.

---

# **Lecturas recomendadas para complementar**

## **1\. PPT 04 – versión nueva**

Es la mejor para ver la narrativa completa y los diagramas visuales de valor, MVP, pivote, priorización, MMF/MVF y roadmap. Especialmente buenas las páginas 3, 7, 11, 14, 15, 18 y 19\.

## **2\. PPT 04 – versión vieja**

Es más textual y más didáctica para definiciones de MVP, MMF, MVF, MMP, MMR y errores comunes. Muy útil para estudiar conceptos con palabras más directas.

## **3\. Eric Ries – *El método Lean Startup***

Es la base conceptual más importante de esta unidad. Sobre todo:

* startup como institución en incertidumbre,  
* aprendizaje validado,  
* Crear–Medir–Aprender,  
* audacia del cero,  
* experimentos,  
* hipótesis de valor y crecimiento,  
* pivotar o perseverar.

## **4\. AgileSparks – “dinosaurio”**

Muy útil para ordenar mentalmente MVP, MVF y MMF sin mezclarlos. Es casi un puente entre el material de cátedra y el lenguaje Lean/Agile.

## **5\. Fuentes de MLP**

Las usaría como complemento moderno, no como base principal:

* GammaUX,  
* LaunchNotes,  
* Userpilot,  
* Aha\!

---

# **Posibles preguntas de parcial con respuesta modelo**

## **1\. ¿Qué problema intenta resolver la gestión de productos?**

Busca asegurar que el software cree valor real para usuarios y negocio, evitando desperdiciar esfuerzo en funcionalidades que no se adoptan o que nadie necesita.

## **2\. ¿Qué significa que el 45% de las features no se usan?**

Significa que una gran parte del esfuerzo de desarrollo puede transformarse en desperdicio si el producto se construye por intuición interna y no por validación real con usuarios.

## **3\. ¿Qué es un MVP?**

Es la versión mínima de un producto que permite obtener aprendizaje validado sobre clientes con el menor esfuerzo posible, enfrentando la realidad del mercado lo antes posible.

## **4\. ¿Por qué un MVP no es simplemente “hacer algo chiquito”?**

Porque también debe ser viable: tiene que resolver algo real, permitir uso real y generar feedback útil. Si es solo algo roto o incoherente, no valida nada serio.

## **5\. ¿Qué diferencia hay entre hipótesis de valor e hipótesis de crecimiento?**

La hipótesis de valor prueba si el producto realmente aporta valor al usuario. La de crecimiento prueba cómo nuevos usuarios descubren y adoptan el producto.

## **6\. ¿Qué enseña el caso Dropbox?**

Que cuando construir el producto completo es muy costoso o riesgoso, se puede validar interés antes mediante pruebas de humo o experimentos ligeros, como un video o landing.

## **7\. ¿Qué es un pivote?**

Es un cambio de dirección basado en aprendizaje validado, donde se reformula la hipótesis producto/cliente/problema sin perder lo aprendido hasta ese momento.

## **8\. ¿Qué es un MMF?**

Es la pieza más pequeña de funcionalidad que puede liberarse aportando valor comercial o de usuario en un área donde ya existe bastante certeza.

## **9\. ¿Qué es un MVF?**

Es una feature mínima viable usada para explorar una oportunidad con incertidumbre todavía alta; sirve para aprender sobre una funcionalidad concreta.

## **10\. ¿Qué relación tienen MVP, MMF y user stories?**

MVP y MMF son contenedores de negocio o producto. Para implementarlos técnicamente se los corta en user stories más chicas, que reducen riesgo de ejecución y permiten feedback temprano.

## **11\. ¿Qué diferencia hay entre MVP y MLP?**

El MVP se centra en validar aprendizaje con el mínimo esfuerzo. El MLP agrega la intención de generar una experiencia que el usuario realmente disfrute o ame desde temprano.

---

## **Mini resumen final para memorizar**

La gestión de productos de software parte de una idea simple: no alcanza con desarrollar bien, hay que construir algo que realmente cree valor. Por eso el enfoque Lean Startup propone reducir desperdicio mediante el ciclo Construir–Medir–Aprender y usar MVPs para validar hipótesis con usuarios reales lo antes posible. A partir de esa validación, el producto puede pivotar, encontrar encaje y luego crecer mediante piezas mínimas como MVFs, MMFs y releases comercializables. El agregado más moderno de MLP recuerda que, además de ser viable, un producto puede buscar ser querido o memorable desde el arranque. En todos los casos, la lógica de fondo es la misma: menos fe ciega, más validación; menos feature por feature, más propuesta de valor y experiencia real.

Si querés, seguimos con el **05** con exactamente el mismo formato.

---

# **PPT 05: Componentes de Proyecto de Desarrollo de Software**

## **1\) Idea central del tema**

La idea de fondo del ppt es esta: un **proyecto de software** no se sostiene solo con código y buena voluntad; necesita **objetivos claros**, **alcance**, **planificación**, **estimaciones**, **gestión de riesgos**, **métricas**, **monitoreo** y **control**. El material retoma ideas ya vistas en el ppt 00, como **proceso**, **ciclos de vida** y distinción entre enfoques **definidos** y **empíricos**, pero ahora las aterriza en la **administración concreta de proyectos**. Es decir, deja de hablar solo del desarrollo en abstracto y empieza a responder qué debe gestionarse para que un proyecto llegue a buen puerto.

Una muy buena síntesis del tema aparece en la diapositiva 22: administrar proyectos es lograr que el trabajo esté hecho **en tiempo**, **con el presupuesto acordado** y **satisfaciendo requerimientos**. En una formulación más formal, la administración de proyectos es la aplicación de **conocimientos**, **habilidades**, **herramientas** y **técnicas** a las actividades del proyecto para satisfacer sus requerimientos.

## **2\) El punto de partida: el proceso de software**

El ppt abre definiendo el **proceso de software** como un conjunto estructurado de actividades para desarrollar un sistema de software, y aclara tres cuestiones:

* esas actividades varían según la organización y el tipo de sistema;  
* el proceso incluye **personas**, **métodos**, **herramientas** y **productos asociados**;  
* y debe **modelarse explícitamente** si se quiere administrarlo.

Esto marca una idea básica del resto del tema: **no se puede administrar bien algo que no está mínimamente explicitado**. El proceso no es solo una secuencia de tareas, sino el marco dentro del cual interactúan personas con habilidades, herramientas y equipos, procedimientos y métodos, y el trabajo que transforma insumos en productos.

## **3\) Procesos definidos vs empíricos**

Este ppt recupera una distinción ya vista en el 00\.

### **Procesos definidos**

Están inspirados en las líneas de producción y suponen que puede repetirse el mismo proceso una y otra vez obteniendo resultados similares. La administración y el control provienen de la **predictibilidad** del proceso. El esquema del ppt los resume como **entradas identificadas**, **proceso definido** y **salidas esperadas**.

### **Procesos empíricos**

Asumen procesos complicados, con variables cambiantes, y aceptan que la repetición puede producir resultados diferentes. En estos casos, el control se realiza a través de **inspecciones frecuentes** y **adaptaciones**. El patrón que muestra el ppt es claro: **asumir**, **construir**, **retroalimentar**, **revisar** y **adaptar**.

La anécdota del pasto en la Universidad de California funciona como una metáfora precisa: primero se observa el comportamiento real y recién después se formaliza la solución. La lectura conceptual importante es que los proyectos de software no siempre pueden pensarse como líneas de producción; muchas veces requieren una lógica **empírica**, basada en **feedback** y **adaptación**.

## **4\) Ciclos de vida**

El ppt define los **ciclos de vida** como la serie de pasos a través de los cuales progresa un producto o un proyecto. Luego diferencia entre el **ciclo de vida del proyecto** y el **ciclo de vida del producto**: el proyecto va desde la idea y el plan de negocio hasta la entrega, mientras que el producto continúa en operación, actualización y retiro.

Después agrega una idea central: un **ciclo de vida de un proyecto de software** es una **representación de un proceso** desde una perspectiva particular. Los modelos especifican:

* las **fases del proceso**;  
* y el **orden** en que se llevan a cabo.

La clasificación básica del ppt distingue tres tipos:

* **secuencial**;  
* **iterativo**;  
* **recursivo**.

Además, el material recuerda que existen más modelos posibles y remite al capítulo 7 de *Rapid Development*. McConnell, efectivamente, incluye allí variantes como **waterfall**, **spiral**, **staged delivery**, **evolutionary prototyping**, **evolutionary delivery** y otras. Eso confirma que la clasificación del ppt es una base útil, pero no agota el universo real de ciclos de vida.

### **Ventajas y desventajas de los modelos de ciclo de vida**

El **modelo secuencial** tiene como principal ventaja la **claridad estructural**. Define fases bien diferenciadas, facilita la documentación, el control formal y la trazabilidad entre etapas. Resulta especialmente útil cuando el problema está bien entendido, los cambios esperados son bajos y se necesita mucha formalidad. Su principal desventaja es la **rigidez**: si los requerimientos cambian o si el entendimiento del problema madura tarde, el costo de corregir aumenta y el feedback del usuario llega demasiado tarde.

El **modelo iterativo** tiene como gran ventaja la posibilidad de **entregar valor en partes**, aprender con feedback y corregir rumbo más temprano. Favorece la adaptación al cambio, la revisión continua y la reducción del riesgo porque cada iteración permite inspeccionar producto y proceso. Su desventaja es que exige más disciplina de coordinación, priorización e integración; si se lo ejecuta mal, puede derivar en fragmentación, deuda técnica o pérdida de visión global.

El **modelo recursivo** reconoce que algunos problemas complejos no pueden resolverse mediante una sola pasada lineal, sino a través de sucesivos ciclos de comprensión, construcción y revisión. Su ventaja es que se adapta bien a contextos de alta incertidumbre o fuerte innovación. Su desventaja es que puede resultar más difícil de comunicar, estimar y gestionar en organizaciones acostumbradas a planes cerrados, y requiere madurez para no transformarse en una espiral sin cierre ni hitos claros.

La conclusión teórica importante es que **ningún ciclo de vida es el mejor en abstracto**. Cada uno resuelve mejor ciertos problemas y empeora otros. La elección correcta depende del proyecto, del producto, del nivel de cambio esperado y del contexto organizacional.

### **Criterios para elegir el ciclo de vida adecuado**

La elección del ciclo de vida debe hacerse en función de las **necesidades del proyecto** y de las **características del producto**. Un criterio central es el **grado de estabilidad de los requerimientos**. Si el problema está bien entendido, el alcance cambia poco y se necesita alta formalidad, un enfoque más secuencial puede resultar razonable. Si, en cambio, hay incertidumbre, descubrimiento progresivo o necesidad de feedback temprano, conviene un enfoque más iterativo o empírico.

También influye la **criticidad del producto**. En sistemas donde un error puede tener gran impacto económico, regulatorio o de seguridad, suele requerirse más formalidad, trazabilidad y control entre etapas. En productos digitales orientados a mercado, aprendizaje con usuarios y evolución rápida, suele ser más importante la capacidad de experimentar, inspeccionar y adaptar.

Otros criterios relevantes son:

* el **tamaño del proyecto**;  
* la **madurez del equipo**;  
* la **disponibilidad de usuarios o stakeholders** para dar feedback;  
* la **presión de tiempo**;  
* la **necesidad de releases parciales**;  
* y el **nivel de riesgo técnico**.

En síntesis, la elección del ciclo de vida no debe hacerse por costumbre o moda, sino en función de cuál permite gestionar mejor la combinación de **incertidumbre**, **coordinación**, **control** y **valor** en ese proyecto concreto.

## **5\) Proceso, proyecto, producto, personas y herramientas**

La página 15 resume una relación muy importante:

* las **personas** se incorporan al **proceso**;  
* el **proceso** se adapta al **proyecto**;  
* el **proyecto** obtiene como resultado un **producto**;  
* y las **herramientas** automatizan o soportan partes del proceso.

Esto sirve para no mezclar planos:

* **proceso** \= cómo se trabaja;  
* **proyecto** \= esfuerzo temporario y organizado;  
* **producto** \= resultado entregable y evolutivo;  
* **herramientas** \= soporte;  
* **personas** \= quienes ejecutan, coordinan y aprenden.

### **Vínculo proceso–proyecto–producto**

El vínculo entre **proceso**, **proyecto** y **producto** es uno de los ejes más importantes del tema. El **proceso** define cómo se trabaja: actividades, métodos, herramientas, roles y transformaciones. El **proyecto** es el esfuerzo temporal y organizado que utiliza ese proceso para alcanzar un objetivo. El **producto** es el resultado construido, que luego pasa a operación, mantenimiento, evolución y eventual retiro.

En términos simples:

* el **proceso organiza el trabajo**;  
* el **proyecto ejecuta ese trabajo**;  
* el **producto es el resultado**.

La gestión de software consiste justamente en alinear esos tres planos. Si el proceso no sirve al proyecto, aparece desorden. Si el proyecto no está orientado al producto correcto, aparece desperdicio. Si el producto no retroalimenta al proceso y al proyecto, se pierde aprendizaje para su evolución futura.

## **6\) Qué es un proyecto**

Aunque la diapositiva 16 es más disparadora que definicional, las páginas siguientes construyen la idea de **proyecto** a partir de sus características.

### **a) Orientación a objetivos**

Los proyectos están dirigidos a obtener resultados, expresados a través de **objetivos**. Esos objetivos guían el proyecto, no deben ser ambiguos y deben ser alcanzables.

### **b) Duración limitada**

Los proyectos son **temporarios**: cuando se alcanza el objetivo, el proyecto termina. Por eso una línea de producción no es un proyecto.

### **c) Tareas interrelacionadas**

Los proyectos tienen tareas interrelacionadas basadas en esfuerzo y recursos, y eso introduce una complejidad sistémica que exige coordinación.

### **d) Unicidad**

Todos los proyectos, por similares que sean, tienen características que los hacen **únicos**.

Entonces, una definición razonada sería: un proyecto es un **esfuerzo temporal**, **orientado a objetivos**, compuesto por **tareas interrelacionadas**, que utiliza recursos limitados para producir un **resultado único**.

## **7\) Qué es la administración de proyectos**

La página 22 es una de las más importantes del tema. Allí se dice que administrar proyectos es lograr el trabajo:

* **en tiempo**;  
* **con presupuesto acordado**;  
* y **satisfaciendo especificaciones o requerimientos**.

Luego agrega una formulación más formal: la **administración de proyectos** es la aplicación de conocimientos, habilidades, herramientas y técnicas a las actividades del proyecto para satisfacer sus requerimientos. Eso incluye:

* identificar requerimientos;  
* establecer objetivos claros y alcanzables;  
* adaptar especificaciones, planes y enfoque a los intereses de los stakeholders.

En consecuencia, administrar no es solo controlar fechas, sino articular **objetivos**, **restricciones**, **personas**, **expectativas** y **decisiones**.

## **8\) La triple restricción**

Este es uno de los núcleos más examinables del ppt. La página 23 presenta la **triple restricción**:

* **objetivos/alcance**;  
* **tiempo**;  
* **costos**.

Además, aclara que el equilibrio entre estos tres factores afecta directamente la **calidad** del proyecto. La página 24 lo representa en un diagrama que relaciona costo, alcance, fecha comprometida, restricción de presupuesto, performance requerida y calidad como resultado del equilibrio.

La idea importante es que, si cambia una restricción, normalmente se ve afectada alguna de las otras. Por ejemplo:

* si aumenta el **alcance** y no cambia la fecha, tiende a subir el costo o a bajar la calidad;  
* si se recorta el **presupuesto** sin recortar alcance, se pone en riesgo la fecha o la performance;  
* si se adelanta la **fecha**, probablemente haya que ajustar alcance, costo o ambos.

## **9\) El desarrollo de software como desarrollo incremental**

La página 26 dice algo totalmente alineado con los temas anteriores: cada nueva versión del producto software se desarrolla **incrementalmente** en una serie de pasos.

Esto conecta con:

* los **requerimientos ágiles** del ppt 02;  
* las **estimaciones ágiles** del ppt 03;  
* y la **gestión de producto** del ppt 04\.

Es decir, aunque este ppt hable de “proyecto”, no vuelve a una visión monolítica rígida. Mantiene la idea de **evolución incremental** del software.

## **10\) Rol del líder de proyecto**

La página 27 ubica al **líder de proyecto** en el centro de múltiples relaciones:

* cliente;  
* equipo de proyecto;  
* gerentes funcionales;  
* niveles altos de administración;  
* subcontratistas;  
* organizaciones regulatorias.

Esto muestra algo importante: el líder de proyecto no solo coordina tareas, sino que también gestiona **interfaces** entre actores con intereses distintos. Además, el propio ppt ya decía que es responsabilidad del líder balancear objetivos que muchas veces compiten entre sí.

## **11\) Equipo de proyecto**

La página 28 define al **equipo de proyecto** como un grupo de personas comprometidas en alcanzar un conjunto de objetivos de los cuales se sienten mutuamente responsables. También enumera sus características:

* diversos conocimientos y habilidades;  
* posibilidad de trabajar juntos efectivamente y desarrollar sinergia;  
* grupo usualmente pequeño;  
* sentido de responsabilidad como unidad.

Esto se complementa bien con Sommerville, quien remarca que los grupos de desarrollo deberían ser bastante pequeños y cohesivos, y que su efectividad depende de sus miembros, su organización y su comunicación interna.

## **12\) Planificación y plan de proyecto**

La página 21 trae una frase muy importante: **“Planning is everything. Plans are nothing.”** La idea no es despreciar el plan, sino señalar que el valor está en **planificar**, es decir, en pensar, alinear y revisar, más que en creer que el plan quedará congelado de manera perfecta.

La página 29 usa una metáfora clara: un plan es a un proyecto lo que una **hoja de ruta** a un viaje. La página 30 dice que el **plan de proyecto** documenta:

* qué se hace;  
* cuándo se hace;  
* cómo se hace;  
* quién lo va a hacer.

En consecuencia, el plan no es un adorno documental, sino el instrumento que vuelve visible y coordinable al proyecto.

## **13\) Qué implica la planificación de proyectos de software**

La página 31 lista de forma bastante completa qué incluye planificar un proyecto de software:

* definición del alcance;  
* definición de proceso y ciclo de vida;  
* estimación;  
* gestión de riesgos;  
* asignación de recursos;  
* programación;  
* definición de controles;  
* definición de métricas.

En realidad, esa diapositiva funciona casi como el mapa conceptual del resto del ppt.

## **14\) Alcance del producto vs alcance del proyecto**

La página 32 trae una distinción muy importante.

### **Alcance del producto**

Son todas las características que pueden incluirse en un **producto o servicio**.

### **Alcance del proyecto**

Es todo el trabajo, y solo el trabajo, que debe hacerse para entregar ese producto o servicio con las características y funciones especificadas.

La página 33 agrega cómo se mide cada uno:

* el cumplimiento del **alcance del proyecto** se mide contra el **voyecto**;  
* el cumplimiento del **alcance del producto** se mide contra la **especificación de requerimientos**.

Una forma útil de memorizarlo es:

* **producto** \= qué debe tener;  
* **proyecto** \= qué trabajo hay que hacer para lograrlo.

## **15\) Definir el ciclo de vida del proyecto**

La página 34 muestra un flujo típico:

* requerimientos;  
* diseño;  
* implementación;  
* prueba;  
* operación y mantenimiento.

También recuerda que puede desagregarse más, incluyendo análisis y otros workflows centrales. Lo importante no es memorizar una única secuencia cerrada, sino entender que definir el ciclo de vida implica decidir:

* qué fases habrá;  
* cómo se ordenan;  
* cómo se articulan entre sí.

Esto conecta con McConnell, que en *Rapid Development* dedica el capítulo 7 a elegir y comparar modelos de ciclo de vida, justamente porque esa decisión impacta en **velocidad**, **riesgo** y **coordinación**.

## **16\) Estimaciones de software**

La página 35 lista cinco cosas que se estiman en software:

* tamaño;  
* esfuerzo;  
* calendario;  
* costo;  
* recursos críticos.

Esto conecta directamente con el ppt 03, donde ya se vio que:

* **tamaño** no es tiempo;  
* **esfuerzo** no es lo mismo que duración;  
* y el **calendario** se razona a partir de estimaciones y capacidad real.

También conecta con McConnell:

* en *Rapid Development*, los capítulos 8 y 9 tratan **estimación** y **scheduling**;  
* y en *Software Estimation* se profundiza la diferencia entre **estimate**, **target** y **commitment**.

## **17\) Riesgo y gestión de riesgos**

La página 36 define **riesgo** de una manera muy útil para memorizar:

* problema esperando para suceder;  
* evento que podría comprometer el éxito del proyecto.

La página 37 muestra el flujo de **gestión de riesgos**:

* planificar;  
* identificar;  
* analizar;  
* seguimiento y control;  
* aprendizaje;  
* base de conocimiento de riesgos.

La idea clave es que los riesgos no se atienden una sola vez al inicio; se identifican y gestionan durante todas las fases del proyecto. McConnell también dedica un capítulo entero a **Risk Management** en *Rapid Development*, y Sommerville remite a bibliografía específica sobre gestión de riesgos.

## **18\) Métricas de software**

La página 39 divide las **métricas de software** en:

* métricas de proceso;  
* métricas de proyecto;  
* métricas de producto.

La página 40 resume las métricas básicas para un proyecto:

* tamaño del producto;  
* esfuerzo;  
* tiempo;  
* defectos.

La página 41 las distribuye por niveles.

### **A nivel desarrollador**

Aparecen métricas como:

* esfuerzo;  
* duración estimada y real de una tarea;  
* cobertura de unit tests;  
* defectos encontrados en unit tests;  
* defectos encontrados en revisión por pares.

### **A nivel equipo**

Aparecen:

* tamaño del producto;  
* duración entre hitos;  
* staffing;  
* tareas planificadas y completadas;  
* distribución del esfuerzo;  
* estado y volatilidad de requerimientos;  
* defectos en integración y testing;  
* peer reviews;  
* porcentaje de tests ejecutados.

### **A nivel organización**

Aparecen:

* tiempo calendario;  
* performance planificada y real de esfuerzo;  
* performance presupuestaria;  
* precisión de estimaciones;  
* defectos en release.

La idea importante es que no existe “la métrica” universal; depende del nivel de decisión que se quiere soportar.

## **19\) Mantener las métricas simples**

La página 42 tiene una idea muy sana: si se está a millas del destino, no tiene sentido medir en milímetros. También propone tres preguntas para evaluar una métrica:

* ¿da más información que la disponible actualmente?  
* ¿esa información tiene beneficio práctico?  
* ¿realmente dice lo que se quiere saber?

Este punto pone un límite importante a la obsesión por medir: **medir por medir no sirve**; la métrica debe ser útil para decidir. McConnell también dedica un capítulo específico a **Measurement** en *Rapid Development*, lo que confirma que medir importa, pero siempre con propósito.

## **20\) Monitoreo y control**

La página 44 marca el tema de **monitoreo y control**, y la página 47 lo resume de forma muy simple: consiste en **comparar lo planificado con lo real**.

Ese mecanismo parece obvio, pero es uno de los núcleos más prácticos de la gestión de proyectos:

* se planifica;  
* se observa la realidad;  
* se compara;  
* se detectan desvíos;  
* se corrige.

Sin este ciclo, el plan pierde utilidad y se vuelve decorativo.

## **21\) Cómo se atrasa un proyecto**

La página 45 pregunta “cómo se atrasa un proyecto” y la página 46 responde con la referencia clásica de Brooks: **de a un día por vez**.

Eso se complementa muy bien con *The Mythical Man-Month*. Brooks explica que los atrasos se vuelven especialmente graves cuando se detectan tarde, sobre todo en testing de sistema, y formula su ley más conocida: **“Adding manpower to a late software project makes it later.”** El razonamiento es que agregar gente tarde no solo suma manos: también agrega entrenamiento, redistribución de trabajo, comunicación extra y testeo adicional. Por eso el retraso no se corrige linealmente.

## **22\) Factores de éxito y causas de fracaso**

La página 48 resume tres factores clave para el éxito de un proyecto:

* monitoreo y feedback;  
* misión u objetivo claro;  
* comunicación.

Después, la página 49 enumera causas de fracaso muy concretas:

* fallas al definir el problema;  
* planificar con datos insuficientes;  
* que la planificación la haga un grupo desconectado;  
* falta de seguimiento del plan;  
* plan pobre en detalles;  
* mala planificación de recursos;  
* estimaciones basadas en supuestos sin datos históricos;  
* ausencia de un responsable claro.

El valor de este listado es que aterriza el tema: los proyectos no fracasan solo por complejidad técnica; muchísimas veces fracasan por **mala gestión básica**.

## **23\) Qué bibliografía complementa mejor este ppt**

### **1\. Sommerville**

Es muy útil para la parte de **gestión de proyectos**, **grupos**, **motivación**, **comunicación** y **riesgos**. El libro incluye un capítulo de gestión de proyectos y remite a bibliografía sobre Brooks, McConnell y riesgo.

### **2\. *Rapid Development* – McConnell**

Es probablemente el mejor complemento directo para este ppt. Para esta unidad convienen especialmente:

* **capítulo 5: Risk Management**  
* **capítulo 7: Lifecycle Planning**  
* **capítulo 8: Estimation**  
* **capítulo 9: Scheduling**  
* **capítulo 26: Measurement**  
* **capítulo 41: Top-10 Risks List**

### **3\. *The Mythical Man-Month* – Brooks**

Es muy útil para:

* entender cómo se atrasan realmente los proyectos;  
* por qué agregar gente tarde suele empeorar las cosas;  
* y por qué el **man-month** no es lineal.

## **Qué estudiar sí o sí para el parcial**

Tenés que poder explicar bien:

* qué es un **proceso de software**;  
* diferencia entre **proceso definido** y **empírico**;  
* qué es un **ciclo de vida** y cómo se relaciona con el proceso;  
* qué es un **proyecto** y cuáles son sus características;  
* qué es la **administración de proyectos**;  
* qué es la **triple restricción** y cómo impacta en la calidad;  
* qué documenta un **plan de proyecto**;  
* qué implica la **planificación** de un proyecto de software;  
* diferencia entre **alcance del producto** y **alcance del proyecto**;  
* qué se estima en software;  
* qué es un **riesgo** y cómo se gestiona;  
* tipos de **métricas** y métricas básicas;  
* qué significa **monitorear y controlar**;  
* por qué los proyectos se atrasan;  
* cuáles son los factores de éxito y las causas típicas de fracaso.

## **Posibles preguntas de parcial con respuesta modelo**

### **1\. ¿Qué es un proceso de software?**

Es un conjunto estructurado de actividades, métodos, prácticas y transformaciones que las personas usan para desarrollar o mantener software y sus productos asociados. Debe modelarse explícitamente si se quiere administrar.

### **2\. ¿Qué diferencia hay entre proceso definido y proceso empírico?**

El definido se basa en repetibilidad y predictibilidad. El empírico asume variabilidad y complejidad, por lo que se controla con inspección frecuente, retroalimentación y adaptación.

### **3\. ¿Qué es un proyecto?**

Es un esfuerzo temporal, orientado a objetivos, compuesto por tareas interrelacionadas y recursos limitados, que busca producir un resultado único.

### **4\. ¿Qué es la administración de proyectos?**

Es la aplicación de conocimientos, habilidades, herramientas y técnicas a las actividades del proyecto para satisfacer sus requerimientos, equilibrando tiempo, costo, alcance y calidad.

### **5\. ¿Qué es la triple restricción?**

Es la relación entre alcance, tiempo y costo. El equilibrio entre esas tres variables impacta directamente en la calidad del proyecto, y el líder debe balancearlas.

### **6\. ¿Qué diferencia hay entre alcance del producto y del proyecto?**

El alcance del producto son las características del producto o servicio. El alcance del proyecto es el trabajo necesario, y solo ese trabajo, para entregarlo.

### **7\. ¿Qué incluye la planificación de un proyecto de software?**

Incluye definir alcance, proceso y ciclo de vida, estimar, gestionar riesgos, asignar recursos, programar, definir controles y definir métricas.

### **8\. ¿Qué se estima en software?**

Tamaño, esfuerzo, calendario, costo y recursos críticos.

### **9\. ¿Qué es un riesgo en un proyecto?**

Es un problema esperando para suceder o un evento que podría comprometer el éxito del proyecto. La gestión de riesgos implica planificar, identificar, analizar, seguir y controlar riesgos durante todo el proyecto.

### **10\. ¿Qué significa monitoreo y control?**

Significa comparar lo planificado con lo real, detectar desvíos y actuar para corregirlos.

### **11\. ¿Cómo se atrasa un proyecto?**

De manera gradual, acumulando pequeños desvíos. Brooks lo resume diciendo que los proyectos se atrasan de a un día por vez, y advierte además que agregar gente tarde suele empeorar el atraso.

### **12\. ¿Cuáles son causas típicas de fracaso?**

Definir mal el problema, planificar con datos insuficientes, no seguir el plan, estimar sin datos históricos, planificar mal recursos o directamente no tener un responsable claro.

## **Mini resumen final para memorizar**

Este ppt muestra que un proyecto de software no puede gestionarse solo con intuición técnica. Hace falta **explicitar el proceso**, elegir o adaptar un **ciclo de vida**, definir **alcance**, estimar **tamaño**, **esfuerzo**, **tiempo** y **costo**, gestionar **riesgos**, asignar **recursos**, medir lo importante y monitorear desvíos comparando plan con realidad. El proyecto es **temporal**, **orientado a objetivos**, **único** y compuesto por **tareas interrelacionadas**. El líder debe balancear **alcance**, **tiempo** y **costo** sin perder de vista la **calidad**. Y, como recuerdan Brooks y la cátedra, los proyectos no suelen romperse de golpe: se atrasan y fracasan por acumulación de pequeños problemas de **definición**, **planificación**, **seguimiento** y **comunicación**.

---

---

# **PPT 06: Estimaciones de Software**

## **1\) Idea central del tema**

La idea de fondo del ppt es esta:

**estimar es inevitable, pero hay que entender bien qué es una estimación y qué no es.**  
Por definición, una estimación **no es precisa**, **no es un plan**, y **no es un compromiso**. Las estimaciones sirven como base para planificar, pero no deben confundirse con el plan ni con una promesa de entrega. Además, cuanto mayor sea la distancia entre lo estimado y lo planeado, mayor es el riesgo del proyecto. Todo eso aparece condensado en la **página 3** del ppt.

McConnell arranca exactamente por ahí. En el capítulo 1 distingue entre **estimate**, **target** y **commitment**. Para él, una estimación es una predicción; un target es un objetivo de negocio deseado; y un compromiso es una promesa concreta. Mezclar estas tres cosas destruye la utilidad de la estimación. También dice que la relación entre estimación y planificación es estrecha, pero que **estimar no es planear y planear no es estimar**.

Entonces, la frase madre del tema sería:

**una estimación útil no tiene que ser exacta; tiene que ser lo bastante buena como para permitir decisiones sensatas sobre el proyecto.**

---

## **2\) Qué quiere enseñar este ppt**

Este ppt quiere sacarte una mala idea muy común:

**creer que estimar es “tirar un número”.**

La cátedra quiere que entiendas que estimar implica:

* aceptar incertidumbre,  
* distinguir estimación de plan,  
* elegir una técnica razonable,  
* usar datos cuando existan,  
* estructurar el juicio experto,  
* evitar sesgos,  
* y no olvidarse actividades reales del proyecto.

McConnell lo dice sin vueltas en el “Welcome”: la estimación de software no es magia negra, pero tampoco es intuición pura. Hay investigación, técnicas, datos históricos y reglas prácticas que permiten mejorar muchísimo la calidad de las estimaciones. También aclara que el problema típico no es pasar de ±10% a ±5%, sino evitar errores del 100% o más, que son tristemente normales en muchas organizaciones.

---

## **3\) Estimación, planificación y compromiso**

La **página 3** del ppt resume cinco ideas clave:

* una estimación no es precisa por definición,  
* estimar no es planear,  
* planear no es estimar,  
* las estimaciones son base del plan, pero el plan no tiene que coincidir exactamente con lo estimado,  
* las estimaciones no son compromisos.

McConnell refuerza esto en el capítulo 1\. Explica que muchas veces los ejecutivos creen estar pidiendo una estimación cuando en realidad están pidiendo un **plan para alcanzar un target**. Ahí aparecen malos entendidos muy clásicos: el técnico vuelve con una predicción analítica y el negocio reacciona como si le hubieran negado un objetivo comercial. Para McConnell, una de las primeras responsabilidades del líder técnico es traducir esa confusión y separar correctamente:

* qué es la estimación,  
* qué es el target,  
* y qué es el compromiso.

Esto conecta muchísimo con el ppt 05\. Ahí veíamos que el plan documenta qué, cuándo, cómo y quién. Acá se completa la idea: **el plan usa estimaciones, pero no se reduce a ellas**.

---

## **4\) ¿Para qué estimamos?**

La **página 4** del ppt pregunta “¿Para qué estimamos?” y muestra una idea muy importante: muchas estimaciones de esfuerzo, costo o cronograma se definen **demasiado temprano**, cuando todavía no existe una base realista suficiente para confiar en ellas. El gráfico sugiere que la confiabilidad realista aparece más adelante, a medida que progresa el proyecto.

McConnell responde esta pregunta de forma mucho más explícita: el propósito principal de la estimación **no es adivinar perfectamente el futuro**, sino determinar si los objetivos del proyecto son lo bastante realistas como para poder controlarlo y conducirlo a buen puerto. Es decir, la estimación sirve para tomar decisiones:

* si el alcance entra o no entra,  
* si el target es razonable o no,  
* si hay que recortar, escalonar o reforzar,  
* y cuánto riesgo estás asumiendo.

En otras palabras:

**estimamos para poder decidir y gobernar el proyecto, no para decorar una planilla.**

---

## **5\) De dónde vienen los errores de estimación**

La **página 5** del ppt lanza la pregunta, y el resto del material la responde por distintos caminos. McConnell dedica el capítulo 4 entero a esto: “Where Does Estimation Error Come From?”. Ahí enumera las fuentes principales:

* incertidumbre propia del proyecto,  
* caos en el proceso,  
* requerimientos inestables,  
* actividades omitidas,  
* optimismo infundado,  
* subjetividad y sesgos,  
* estimaciones “off-the-cuff”,  
* precisión injustificada.

Esto es importantísimo porque cambia la conversación. El problema de estimación no suele venir de una sola fórmula “mal elegida”, sino de una mezcla de:

* información incompleta,  
* proceso desordenado,  
* presión política,  
* y mala práctica estimando.

El ppt toma varios de esos focos, especialmente:

* datos históricos,  
* juicio experto,  
* Wideband Delphi,  
* actividades omitidas,  
* uso de buffers.

---

## **6\) La incertidumbre es normal: el Cone of Uncertainty**

Aunque el ppt no lo nombra explícitamente, la **página 4** está muy alineada con el **Cone of Uncertainty** de McConnell. En el capítulo 4, McConnell explica que al comienzo del proyecto las estimaciones pueden estar erradas por factores enormes, porque todavía faltan muchísimas decisiones sobre:

* alcance,  
* diseño,  
* requisitos,  
* interfaz,  
* implementación.

En su tabla de error por fase, una estimación en la etapa de **Initial Concept** puede variar aproximadamente entre **0.25x y 4x**, mientras que a medida que el producto se define mejor y se completa diseño/interfaz, el rango se achica. También dice algo clave: el cono **no se estrecha solo**; se estrecha a medida que el proyecto toma decisiones que reducen variabilidad. Si el proyecto es caótico o cambia demasiado, el cono se ensancha otra vez.

Entonces, para examen:

**no hay que pedirle precisión quirúrgica a una estimación hecha cuando el proyecto todavía está en su parte más incierta.**

---

## **7\) Técnicas fundamentales de estimación: contar**

La **página 6** del ppt pone una idea muy simple, pero potentísima:  
**la técnica fundamental de estimación es contar.**

McConnell lo convierte en regla en el capítulo 7: **Count, Compute, Judge**. Primero contar, después convertir esos conteos en estimaciones mediante alguna relación o cálculo, y usar juicio solo como último recurso. Es una crítica directa a la costumbre de arrancar por intuición pura.

La idea es esta:

* primero identificás unidades observables o razonables de trabajo,  
* después las transformás en tamaño, esfuerzo o cronograma,  
* y recién al final metés juicio subjetivo donde no te quede otra.

Esto es muy importante porque ordena el proceso mental:  
**mejor medir o contar algo imperfecto que inventar todo desde cero.**

---

## **8\) Métodos utilizados**

La **página 7** enumera varios tipos de métodos:

* basados en la experiencia,  
* basados exclusivamente en los recursos,  
* basados exclusivamente en el mercado,  
* basados en los componentes del producto o del proceso de desarrollo,  
* algorítmicos.

El ppt no los desarrolla todos igual, pero sí pone foco fuerte en los **basados en experiencia**, que aparecen en la **página 8**:

* datos históricos,  
* juicio experto puro,  
* Delphi,  
* analogía.

McConnell, en la tabla de contenidos, desarrolla una estructura bastante alineada:

* datos históricos y calibración,  
* juicio experto individual,  
* descomposición y recomposición,  
* analogía,  
* juicio experto en grupos,  
* herramientas,  
* uso de múltiples enfoques.

Entonces, conceptualmente:

**no existe un único método mágico; conviene entender familias de métodos y combinarlos con criterio.**

---

## **9\) Datos históricos**

La **página 9** introduce los **datos históricos**, y la **página 10** dispara la pregunta “¿qué datos históricos necesito?”. Aunque el ppt no la responde en texto, McConnell sí lo hace con bastante detalle en el capítulo 8: recomienda recolectar, calibrar y usar datos sobre:

* tamaño,  
* esfuerzo,  
* tiempo calendario,  
* defectos,  
* y otras variables relevantes del contexto organizacional.

McConnell resalta varias ventajas de los datos históricos:

* mejoran precisión,  
* capturan influencias organizacionales reales,  
* reducen subjetividad,  
* reducen optimismo infundado,  
* y bajan la política alrededor de la estimación.

Además, explica que uno de los mayores errores es comparar proyectos solo con la memoria personal de “cuánto tardó la vez pasada”, porque la memoria suele recordar mal o recordar la estimación anterior en vez del resultado real.

O sea:

**sin datos históricos, la estimación depende mucho más del humor, la intuición y el sesgo.**

---

## **10\) Juicio experto puro**

La **página 11** define el juicio experto puro así:

* un experto estudia las especificaciones y hace su estimación,  
* se basa en sus conocimientos,  
* y si desaparece el experto, la empresa deja de estimar.

Ese último punto es buenísimo porque muestra el riesgo de este enfoque:  
**funciona mientras esté la persona correcta, pero no escala organizacionalmente.**

McConnell dedica el capítulo 9 al **Individual Expert Judgment**. No lo descarta, pero insiste en estructurarlo:

* elegir bien quién estima,  
* usar granularidad razonable,  
* usar rangos,  
* usar fórmulas simples,  
* usar checklists,  
* y comparar estimaciones con resultados reales para calibrarse.

Entonces, el juicio experto puede ser útil, pero **sin estructura se vuelve frágil y opaco**.

---

## **11\) Juicio de experto como práctica dominante**

La **página 12** del ppt dice algo muy importante:

* el juicio de experto es el enfoque más usado en la práctica,  
* alrededor del 75% de las organizaciones de software lo usan principalmente,  
* y deja abierta una pregunta muy sana: “¿experto en qué?”

McConnell coincide en espíritu. No niega que el juicio experto sea común; de hecho le dedica varios capítulos. Pero justamente porque es tan común, insiste en que hay que **disciplinarlo**, calibrarlo y apoyarlo con datos.

La pregunta “¿experto en qué?” es buenísima porque no alcanza con ser:

* buen programador,  
* o buen arquitecto,  
* o líder técnico.

No necesariamente eso te convierte en **buen estimador**. McConnell lo dice casi textual en el prólogo: ser experto desarrollando no vuelve automáticamente a alguien experto estimando.

---

## **12\) Cómo estructurar el juicio experto**

La **página 13** del ppt propone cuatro formas de estructurarlo:

* usar tareas con granularidad aceptable,  
* usar el método optimista/habitual/pesimista,  
* aplicar la fórmula **(o \+ 4h \+ p) / 6**,  
* usar checklist y criterio definido para asegurar cobertura.

Esta fórmula es la clásica de **PERT**, y McConnell la incluye en su listado de ecuaciones del libro. También dedica bastante espacio a:

* rangos,  
* fórmulas,  
* checklists,  
* y descomposición.

La advertencia del ppt al final del slide también es importante:  
esto es **un buen comienzo, pero un pésimo final**. O sea, no alcanza con poner una fórmula si todo lo demás está mal:

* si faltan actividades,  
* si el alcance está inestable,  
* si el proceso es caótico,  
* o si nadie compara después contra reales.

---

## **13\) Wideband Delphi**

La **página 14** introduce **Wideband Delphi**:

* un grupo informado trata de estimar esfuerzo y duración,  
* y las estimaciones grupales suelen ser mejores que las individuales.

La **página 15** describe el proceso:

1. se entregan especificaciones a un grupo de expertos,  
2. se reúnen para discutir producto y estimación,  
3. envían estimaciones individuales al coordinador,  
4. cada uno recibe feedback anónimo sobre la suya y las ajenas,  
5. se vuelven a reunir,  
6. revisan su estimación,  
7. el ciclo se repite hasta converger razonablemente.

La **página 16** lo ilustra visualmente. McConnell dedica el capítulo 13 a este método y hasta muestra formularios y evidencia de que, en muchos casos, Wideband Delphi reduce el error frente a estimaciones aisladas. También aclara que no siempre mejora todo, pero en una mayoría importante de casos sí lo hace.

Entonces:

**Wideband Delphi vale porque obliga a explicitar supuestos, contrastar miradas y moderar sesgos individuales.**

---

## **14\) Actividades omitidas: una de las fuentes más comunes de error**

La **página 17** del ppt es de las más importantes del tema. Dice que una de las fuentes de error más comunes es **omitir actividades necesarias**. Agrupa lo omitido en tres clases:

### **a) Requerimientos faltantes**

O sea, cosas que había que construir pero ni siquiera entraron al radar.

### **b) Actividades de desarrollo faltantes**

Por ejemplo:

* documentación técnica,  
* participación en revisiones,  
* creación de datos para testing,  
* mantenimiento de versiones previas.

### **c) Actividades generales**

Por ejemplo:

* días por enfermedad,  
* licencias,  
* cursos,  
* reuniones de compañía.

McConnell desarrolla esto de manera espectacular en el capítulo 4, sección **Omitted Activities**, con listas muy completas de actividades funcionales, no funcionales, de desarrollo y no desarrollo que suelen faltar en las estimaciones. Incluso cita estudios que muestran que muchas veces los desarrolladores estiman razonablemente bien lo que recuerdan, pero se olvidan entre **20% y 30%** del trabajo necesario.

Este punto hay que estudiarlo muy bien porque es re tomable en parcial.

---

## **15\) Buffers y optimismo**

La misma **página 17** menciona el uso de **buffers** y cierra con una frase muy buena atribuida a Chris Peters:  
nunca hay que temer que las estimaciones de desarrolladores sean demasiado pesimistas, porque suelen ser **demasiado optimistas**.

McConnell coincide totalmente. En el capítulo 4 habla de:

* optimism,  
* subjectivity,  
* y el clásico problema de las estimaciones excesivamente optimistas.  
  También en el capítulo 3 concluye que, si no podés ser perfectamente exacto, es menos dañino errar un poco por arriba que por abajo, porque la penalidad de subestimar suele ser peor que la de sobreestimar.

Entonces, la lógica del buffer no es “meter grasa porque sí”, sino:  
**reconocer explícitamente incertidumbre, overhead y riesgo real.**

---

## **16\) Off-the-cuff estimates**

Aunque el ppt no lo nombra así, este tema está muy conectado con lo que McConnell llama **off-the-cuff estimates**. Son esas estimaciones improvisadas, tiradas rápido “de memoria” o “de oído”. En el capítulo 4 muestra evidencia de que esas estimaciones son mucho peores que las revisadas o estructuradas. De hecho, plantea como regla práctica no dar estimaciones de este tipo, porque incluso dedicarle 15 minutos y revisar un poco ya mejora mucho la calidad del resultado.

Esto engancha perfecto con el ppt:  
si no estructurás el juicio, si no revisás actividades omitidas, si no tenés datos históricos, terminás en un off-the-cuff disfrazado.

---

## **17\) Precisión injustificada**

Otra idea muy importante de McConnell que completa muy bien el ppt es la de **unwarranted precision**.

Una estimación puede sonar muy profesional por venir con muchísimos decimales o muchísimo detalle, pero eso no la hace más confiable. McConnell distingue entre:

* **precisión**,  
* y **exactitud**.

Un número puede ser muy preciso y poco exacto. En software eso pasa cuando alguien dice algo como “esto tarda 395.7 días”. El problema no es solo el número; es el mensaje falso de certeza que transmite.

Esto se relaciona directamente con la **página 3** del ppt, que recordaba que una estimación no es precisa por definición.

---

## **18\) Estimaciones como probabilidades, no como verdades absolutas**

Este es otro complemento muy fuerte de McConnell.

En el capítulo 1 explica que toda estimación tiene una **probabilidad implícita**, aunque la gente la exprese como si fuera un número fijo. Critica las estimaciones de punto único porque ocultan incertidumbre real y hacen creer que la probabilidad de cumplimiento es 100%, lo cual es falso. Defiende usar rangos, escenarios o niveles de confianza mejor fundamentados.

Esto conversa muy bien con el ppt:

* si una estimación no es precisa,  
* si no es un compromiso,  
* y si el error cambia según etapa,  
  entonces **tiene más sentido pensarla como rango que como fecha clavada en piedra**.

---

## **19\) Lo que el ppt quiere que te quede claro sí o sí**

Si lo destilamos mucho, este tema quiere dejarte estas ideas:

1. **Estimar no es planear.**  
2. **Estimar no es comprometerse.**  
3. **Toda estimación tiene incertidumbre.**  
4. **Cuanto más temprano está el proyecto, menos confiable es la estimación.**  
5. **Los datos históricos son valiosísimos.**  
6. **El juicio experto sirve, pero hay que estructurarlo.**  
7. **Las estimaciones grupales, como Wideband Delphi, suelen mejorar resultados.**  
8. **Uno de los mayores errores es olvidar actividades necesarias.**  
9. **Los desarrolladores suelen ser optimistas, no pesimistas.**  
10. **Hay que usar buffers y rangos con criterio, no como maquillaje.**

---

# **Qué estudiar sí o sí para el parcial**

Tenés que poder explicar bien:

* qué es una estimación y qué no es,  
* diferencia entre estimación, plan y compromiso,  
* por qué una estimación no es precisa por definición,  
* para qué se estima,  
* por qué las estimaciones tempranas son poco confiables,  
* qué es el Cone of Uncertainty,  
* cuáles son las principales fuentes de error,  
* técnicas fundamentales de estimación,  
* qué significa “contar”,  
* qué son los métodos basados en experiencia,  
* para qué sirven los datos históricos,  
* qué riesgos tiene el juicio experto puro,  
* cómo se estructura el juicio experto,  
* fórmula optimista/habitual/pesimista,  
* qué es Wideband Delphi y cómo funciona,  
* por qué las actividades omitidas arruinan estimaciones,  
* por qué hay que contemplar buffers y overhead,  
* y por qué las estimaciones improvisadas o demasiado precisas son problemáticas.

---

# **Lecturas recomendadas para complementar**

## **1\. PPT 06**

Es el resumen más corto y directo del tema. Muy bueno para tener la foto general:

* estimación vs plan,  
* métodos,  
* juicio experto,  
* Wideband Delphi,  
* actividades omitidas.

## **2\. McConnell – *Software Estimation***

Es el complemento clave para esta unidad. Sobre todo te convienen:

* **Cap. 1:** What Is an Estimate?  
* **Cap. 4:** Where Does Estimation Error Come From?  
* **Cap. 7:** Count, Compute, Judge  
* **Cap. 8:** Calibration and Historical Data  
* **Cap. 9:** Individual Expert Judgment  
* **Cap. 13:** Expert Judgment in Groups  
* **Cap. 22:** Estimate Presentation Styles  
* **Cap. 23:** Politics, Negotiation, and Problem Solving

## **3\. Relación con los ppt anteriores**

Este tema se entiende mejor si lo conectás con:

* **PPT 03** para tamaño relativo, story points y velocidad,  
* **PPT 05** para proyecto, plan, alcance, riesgo y métricas.

---

# **Posibles preguntas de parcial con respuesta modelo**

## **1\. ¿Qué es una estimación de software?**

Es una predicción aproximada sobre esfuerzo, costo, tiempo u otros parámetros del proyecto. No es precisa por definición, no es un plan y no es un compromiso.

## **2\. ¿Qué diferencia hay entre estimar y planear?**

La estimación es un proceso analítico orientado a aproximar la realidad. La planificación usa esas estimaciones para decidir qué hacer, cómo, cuándo y con quién. Los planes se apoyan en las estimaciones, pero no son lo mismo.

## **3\. ¿Qué diferencia hay entre estimación, target y compromiso?**

La estimación es una predicción; el target es un objetivo deseado del negocio; y el compromiso es una promesa de entrega. Confundirlos genera malos planes y malas decisiones.

## **4\. ¿Por qué las estimaciones tempranas son poco confiables?**

Porque el proyecto todavía contiene mucha incertidumbre sobre alcance, diseño, requisitos, personal, riesgo y ejecución. El Cone of Uncertainty muestra que esa variabilidad recién se reduce cuando el proyecto toma decisiones que eliminan incertidumbre.

## **5\. ¿Qué es el Cone of Uncertainty?**

Es un modelo que muestra que las estimaciones tienen mucha variabilidad al inicio del proyecto y se vuelven más confiables a medida que avanza el trabajo y se reduce la incertidumbre. No se estrecha solo: hay que forzarlo reduciendo variabilidad real del proyecto.

## **6\. ¿Qué métodos basados en experiencia menciona el ppt?**

Datos históricos, juicio experto puro, Delphi y analogía.

## **7\. ¿Por qué son importantes los datos históricos?**

Porque permiten calibrar estimaciones con experiencia real de la organización, reducen subjetividad, optimismo y política, y mejoran la precisión frente a estimaciones basadas solo en memoria o intuición.

## **8\. ¿Qué riesgo tiene el juicio experto puro?**

Que depende demasiado del conocimiento individual de una persona. Si esa persona desaparece, la organización pierde la capacidad de estimar de la misma forma. Además, sin estructura puede introducir mucho sesgo.

## **9\. ¿Qué es Wideband Delphi?**

Es una técnica grupal de estimación donde varios expertos estiman en rondas sucesivas, reciben feedback anónimo y vuelven a revisar sus números hasta lograr una convergencia razonable. En general mejora frente a estimaciones individuales aisladas.

## **10\. ¿Cuál es una de las fuentes más comunes de error?**

Omitir actividades necesarias. Eso incluye requerimientos faltantes, tareas de desarrollo no consideradas y actividades generales como reuniones, enfermedad, licencias o capacitación.

## **11\. ¿Por qué los buffers tienen sentido?**

Porque ayudan a absorber incertidumbre, overhead, actividades omitidas y optimismo natural. No son maquillaje si se usan para representar riesgo real y variabilidad del proyecto.

## **12\. ¿Qué problema tienen las estimaciones improvisadas?**

Las estimaciones off-the-cuff suelen ser mucho menos confiables porque se basan en intuición rápida, memoria incompleta y poca revisión. Incluso dedicar unos minutos a revisar datos mejora mucho su calidad.

---

## **Mini resumen final para memorizar**

Este ppt enseña que estimar software no es tirar un número ni prometer una fecha. Una estimación es una aproximación incierta que sirve para tomar decisiones y planificar mejor, pero no equivale a un compromiso. Su calidad depende de entender bien la incertidumbre del proyecto, usar métodos razonables, apoyarse en datos históricos cuando existan, estructurar el juicio experto y no olvidarse actividades reales del trabajo. Wideband Delphi mejora el juicio individual al hacerlo grupal y iterativo. Uno de los errores más comunes es omitir trabajo; otro, subestimar por optimismo o improvisación. La gran idea de fondo es esta: cuanto más explícita y disciplinada sea la estimación, más útil será para gobernar el proyecto.

---

# **PPT 07: Scrum 2020, planificación de release y sprint, métricas Scrum**

## **1\) Idea central del tema**

La idea de fondo del ppt es esta:

**Scrum no es solo una lista de reuniones; es una forma empírica de trabajar en contextos complejos, donde planificar no significa adivinar todo desde el principio sino inspeccionar, adaptar y generar valor de manera iterativa.** El ppt abre justamente con **Cultura Ágil**, después pasa a **proceso empírico**, y en la **página 3** deja los tres pilares del empirismo: **transparencia, inspección y adaptación**.

La **Scrum Guide 2020** dice casi lo mismo, pero más formal: Scrum es un **marco de trabajo liviano** que ayuda a personas, equipos y organizaciones a generar valor mediante soluciones adaptativas para problemas complejos, y se apoya en **empirismo** y **Lean**. También explica que los eventos de Scrum existen para hacer posibles justamente esos tres pilares.

Entonces, la gran idea para parcial sería:

**Scrum organiza el trabajo complejo mediante ciclos cortos, objetivos claros, artefactos transparentes y eventos que permiten inspeccionar resultados y adaptarse rápidamente.**

---

## **2\) Ágil y Scrum no son lo mismo**

El ppt arranca con **Manifiesto Ágil** y después recién entra en **Scrum**. Eso ya te marca una distinción clave:

* **Ágil** es la filosofía o mentalidad general,  
* **Scrum** es uno de los marcos concretos para llevar parte de esa filosofía a la práctica.

En la **página 5** del ppt aparecen los **4 valores ágiles**:

* individuos e interacciones sobre procesos y herramientas,  
* software funcionando sobre documentación extensiva,  
* colaboración con el cliente sobre negociación contractual,  
* responder al cambio sobre seguir un plan.  
  Y en la **página 6** aparecen los **12 principios del Manifiesto Ágil**.

Mike Cohn, en la introducción y en los primeros capítulos de *Agile Estimating and Planning*, insiste mucho en esta idea: lo ágil no es solo “hacer iteraciones”, sino también tener una forma ágil de estimar y planificar. O sea, el proceso de planning también tiene que ser adaptable, revisable y enfocado en valor.

---

## **3\) Scrum 2020: definición y sentido**

En la **página 9** del ppt aparece la definición central:  
**Scrum es un marco de trabajo liviano que ayuda a las personas, equipos y organizaciones a generar valor a través de soluciones adaptativas para problemas complejos.**

La **Scrum Guide 2020** usa prácticamente la misma formulación y la desarrolla así:

1. el Product Owner ordena el trabajo en un Product Backlog,  
2. el Scrum Team convierte parte de ese trabajo en un Increment durante un Sprint,  
3. el equipo y los interesados inspeccionan resultados y se adaptan,  
4. y repiten el ciclo.

Eso es importante porque baja Scrum a un circuito bastante claro:  
**backlog → sprint → incremento → revisión → adaptación → siguiente sprint.**

---

## **4\) Scrum está basado en control empírico**

El ppt lo dice explícito en la **página 2**:  
**Ágil está basado en un proceso de control empírico.** Y en la **página 3** muestra los tres pilares:

* transparencia,  
* inspección,  
* adaptación.

La **Scrum Guide 2020** define cada uno:

### **Transparencia**

Lo importante del proceso y del trabajo tiene que ser visible para quienes lo hacen y para quienes reciben el resultado. Sin transparencia, la inspección se vuelve engañosa.

### **Inspección**

Hay que revisar frecuentemente artefactos y progreso hacia objetivos para detectar desvíos o problemas. Los eventos de Scrum existen justamente para eso.

### **Adaptación**

Cuando el proceso se desvía o el resultado no es aceptable, hay que ajustar rápido. Cuanto antes, mejor.

Esta parte conecta perfecto con el PPT 00 y el 05, donde ya veíamos que en software muchas veces no alcanza con procesos definidos rígidos y que el control real aparece por feedback e iteración.

---

## **5\) Valores de Scrum**

Aunque el ppt no los desarrolla demasiado en texto, el esquema visual del framework muestra también los **valores de Scrum**, y la **Scrum Guide 2020** los enumera formalmente:

* compromiso,  
* foco,  
* franqueza,  
* respeto,  
* coraje.

Estos valores no son un adorno moral. Sirven para que los pilares empíricos funcionen de verdad.  
Por ejemplo:

* sin franqueza no hay transparencia real,  
* sin coraje nadie expone problemas,  
* sin foco el sprint se dispersa,  
* sin respeto no hay autogestión sana,  
* sin compromiso el objetivo del sprint se vacía.

---

## **6\) El Scrum Team y sus responsabilidades**

En la **página 12** del ppt, cuando resume el framework, separa tres grandes cosas:

* responsabilidades,  
* reuniones,  
* artefactos.  
  Dentro de responsabilidades aparecen:  
* **Scrum Master**,  
* **Product Owner**,  
* **Developers**.

La **Scrum Guide 2020** define al **Scrum Team** como una unidad pequeña, multifuncional y autogestionada, generalmente de **10 personas o menos**, sin subequipos ni jerarquías internas.

### **Product Owner**

Es responsable de maximizar el valor del producto y de la gestión efectiva del Product Backlog:

* objetivo del producto,  
* claridad de los items,  
* orden,  
* transparencia del backlog.  
  Es una persona, no un comité.

### **Developers**

Son quienes crean el Increment utilizable en cada Sprint. Entre sus responsabilidades están:

* crear el Sprint Backlog,  
* incorporar calidad siguiendo la Definition of Done,  
* adaptar el plan día a día,  
* responsabilizarse mutuamente como profesionales.

### **Scrum Master**

Es responsable de establecer Scrum correctamente y de mejorar la efectividad del equipo:

* ayuda a la autogestión,  
* facilita eventos,  
* elimina impedimentos,  
* ayuda al Product Owner,  
* y también trabaja con la organización.

---

## **7\) Eventos de Scrum**

El ppt, en la **página 12**, enumera:

* Sprint Planning,  
* Daily Scrum,  
* Sprint Review,  
* Sprint Retrospective,  
* y además refinamiento del Product Backlog como actividad continua.

La **Scrum Guide 2020** formaliza cinco eventos:

* Sprint,  
* Sprint Planning,  
* Daily Scrum,  
* Sprint Review,  
* Sprint Retrospective.  
  El refinamiento del backlog no figura como evento formal sino como actividad continua.

Esto es un detalle importante para parcial:  
**el Sprint es el evento contenedor**, y adentro de él viven los demás eventos.

---

## **8\) El Sprint como núcleo del framework**

La **Scrum Guide 2020** dice que los Sprints son el corazón de Scrum: eventos de duración fija de **un mes o menos**, que se encadenan sin pausa, porque uno empieza inmediatamente después de terminar el anterior. Durante el Sprint:

* no se hacen cambios que pongan en peligro el Sprint Goal,  
* la calidad no disminuye,  
* el backlog se refina cuando hace falta,  
* y el alcance puede aclararse y renegociarse con el Product Owner según lo aprendido.

El ppt acompaña esto con la lógica de **timebox** y muestra al Sprint como marco del resto de las actividades.

La idea fuerte es:  
**el Sprint no es solo un período de tiempo; es la unidad básica de inspección y adaptación.**

---

## **9\) Timeboxes en Scrum**

La **página 14** del ppt resume los límites temporales clásicos:

* Sprint: **1 mes o menos**  
* Sprint Planning: **hasta 8 horas** para un sprint de 1 mes  
* Daily Scrum: **15 minutos**  
* Sprint Review: **hasta 4 horas**  
* Sprint Retrospective: **hasta 3 horas**  
* Refinamiento del Product Backlog: alrededor del **10% del tiempo del Sprint**

La **Scrum Guide 2020** coincide con los timeboxes de Sprint Planning, Daily Scrum, Review y Retrospective para sprints de un mes, y aclara que para sprints más cortos suelen durar menos.

Acá lo importante no es memorizar horas por sí mismas, sino entender el propósito del timebox:  
**poner foco, dar cadencia y evitar que las ceremonias se descontrolen.**

---

## **10\) Artefactos y compromisos**

La **página 13** del ppt muestra algo muy importante:  
cada artefacto tiene su compromiso asociado:

* **Product Backlog → Objetivo del Producto**  
* **Sprint Backlog → Objetivo del Sprint**  
* **Increment → Definition of Done**

La **Scrum Guide 2020** lo formaliza igual:

* para el Product Backlog, el compromiso es el **Product Goal**,  
* para el Sprint Backlog, el **Sprint Goal**,  
* para el Increment, la **Definition of Done**.

Esta versión 2020 de Scrum es importante porque hace mucho más explícita la idea de que los artefactos no son listas sueltas, sino instrumentos con foco y criterio de evaluación.

---

## **11\) Product Backlog**

La **Scrum Guide 2020** define el **Product Backlog** como una lista emergente y ordenada de lo necesario para mejorar el producto, y aclara que es la **única fuente del trabajo** del Scrum Team. También explica que el refinamiento consiste en dividir y precisar items, agregando descripción, orden y tamaño.

El ppt, en varias páginas, lo usa como punto de partida de la planificación:

* en la planificación de release,  
* en la planificación del sprint,  
* en el refinamiento continuo.

Esto conecta muy bien con lo que ya vimos en requisitos ágiles y user stories:  
**el backlog no está congelado; evoluciona.**

---

## **12\) Sprint Backlog**

La **Scrum Guide 2020** dice que el **Sprint Backlog** se compone de:

* el Sprint Goal,  
* el conjunto de PBIs seleccionados,  
* y el plan para entregar el Increment.  
  Además, remarca que es un plan hecho **por y para los Developers**, visible y actualizado en tiempo real a medida que se aprende más.

El ppt lo muestra en la planificación del sprint como la transformación desde el Product Backlog hacia un conjunto de items y tareas concretas para esa iteración.

---

## **13\) Increment y Definition of Done**

La **Scrum Guide 2020** define el **Increment** como un peldaño concreto hacia el Product Goal. Puede haber múltiples increments dentro de un sprint, pero ninguno cuenta como tal si no cumple la **Definition of Done**. También aclara algo muy importante: la Sprint Review **no debe verse como una puerta de liberación**; el valor puede liberarse antes si está realmente listo.

El ppt acompaña esto en la **página 13** y sobre todo en la **página 17**, donde muestra un ejemplo de **Definition of Done** muy concreta:

* diseño revisado,  
* código completo,  
* refactorizado,  
* con formato estándar,  
* comentado,  
* en repositorio,  
* inspeccionado,  
* documentación actualizada,  
* probado,  
* unit test,  
* integración,  
* sistema,  
* aceptación,  
* cero defectos conocidos,  
* y hasta en servidores de producción.

La idea conceptual es esta:  
**Done no es “casi terminado”; es un criterio compartido de calidad real.**

---

## **14\) DoR y DoD: ojo con esto en parcial**

En la **página 15** el ppt pone **DoR** y **DoD** juntos.  
En la **página 16** define **Definition of Ready** con condiciones como:

* valor de negocio claro,  
* comprensión suficiente por el equipo,  
* dependencias identificadas,  
* tamaño apto para un sprint,  
* criterios de aceptación claros y testeables,  
* criterios de performance claros,  
* etc.

En la **página 17** define **Definition of Done**.

Acá hay un matiz importante:

* **DoD sí es compromiso formal de Scrum 2020**, porque aparece en la Guía.  
* **DoR no aparece como elemento oficial del framework en la Scrum Guide 2020**; es una práctica complementaria muy usada para mejorar preparación del backlog y del sprint.

Eso puede ser una linda pregunta de parcial:  
**DoR puede usarse, pero no forma parte del núcleo formal de Scrum 2020 del mismo modo que DoD.**

---

## **15\) Sprint Planning**

La **Scrum Guide 2020** dice que la **Sprint Planning** inicia el Sprint y responde tres preguntas de fondo:

1. **¿Por qué es valioso este Sprint?**  
   De ahí sale el **Sprint Goal**.  
2. **¿Qué se puede hacer en este Sprint?**  
   Los Developers seleccionan PBIs en conversación con el Product Owner.  
3. **¿Cómo se realizará el trabajo elegido?**  
   Los Developers descomponen en trabajo más pequeño y arman el plan.

El ppt, en la **página 40**, lo resume visualmente:

* desde el Product Backlog se decide **qué hacer**,  
* y luego se baja a tareas, o sea, **cómo hacerlo**,  
* y remarca que la Sprint Planning es la primera actividad de cada Sprint.

Kenneth Rubin en *Essential Scrum* también pone el foco en esto y dedica un capítulo entero a Sprint Planning, incluyendo capacidad y selección de PBIs.

---

## **16\) Daily Scrum**

La **página 41** del ppt la muestra como planificación diaria, cada 24 horas, dentro de la ejecución del sprint.

La **Scrum Guide 2020** dice que el propósito de la Daily Scrum es:

* inspeccionar el progreso hacia el Sprint Goal,  
* y adaptar el Sprint Backlog si hace falta.  
  Es un evento de **15 minutos** para los Developers. No es la única conversación del día, pero sí el punto fijo diario de coordinación.

Idea importante:  
**no es un reporte al Scrum Master; es coordinación del equipo sobre su propio trabajo.**

---

## **17\) Sprint Review**

La **Scrum Guide 2020** dice que la Sprint Review sirve para inspeccionar el resultado del sprint y decidir futuras adaptaciones. Participan el Scrum Team y stakeholders, se revisa lo hecho, lo que cambió en el entorno y qué hacer después. Es una **sesión de trabajo**, no una demo vacía.

El ppt la incluye dentro del circuito general del framework y la enlaza con backlog, incremento y adaptación.

---

## **18\) Sprint Retrospective**

La **Scrum Guide 2020** define la retrospectiva como el espacio para planificar mejoras en calidad y efectividad. El equipo inspecciona:

* personas,  
* interacciones,  
* procesos,  
* herramientas,  
* y su Definition of Done.  
  Luego decide mejoras concretas, idealmente implementables cuanto antes.

Este punto es central porque muestra que Scrum no solo adapta producto, sino también **forma de trabajo**.

---

## **19\) Refinamiento del Product Backlog**

El ppt lo menciona como actividad continua y le asigna aproximadamente **10% del tiempo del sprint**.

La **Scrum Guide 2020** no fija ese porcentaje, pero sí define el refinamiento como la actividad continua de dividir y precisar PBIs agregando detalle, orden y tamaño.

Entonces:

* el **10%** es una guía práctica del material de clase,  
* no una regla rígida universal del framework.

---

## **20\) Capacidad del equipo en un Sprint**

La **página 18** del ppt es muy importante. Muestra que la capacidad total del sprint no equivale a “todo el tiempo calendario del equipo”, sino que se compone descontando:

* tiempo fuera del personal,  
* otros compromisos externos,  
* otras actividades Scrum,  
* y además considera buffer del sprint.

La **página 19** baja eso a un ejemplo concreto, calculando horas disponibles por persona y totalizando una franja de **140–197 horas** de esfuerzo disponible.

Rubin, en *Essential Scrum*, también trata la **capacidad** como parte de Sprint Planning y distingue que no basta con mirar cantidad de personas: hay que mirar disponibilidad real.

Acá el mensaje es clarísimo:  
**si planificás un sprint como si todo el mundo estuviera 100% disponible para PBIs, te mentís solo.**

---

## **21\) Ambiente de trabajo y herramientas visuales**

La **página 20** del ppt habla de un ambiente:

* abierto,  
* con pizarrones,  
* sin silencio absoluto,  
* y con cierta autonomía del equipo sobre horarios.

Después, en las **páginas 21 a 24**, aparecen herramientas como:

* taskboard,  
* ejemplo de tarjeta de tarea,  
* y la idea de **buena vs mala granularidad**.

Esto importa porque Scrum no vive solo en el discurso; necesita visibilidad real del trabajo. Un taskboard ayuda a la transparencia y a la inspección cotidiana.

---

## **22\) Buena y mala granularidad**

La **página 24** del ppt contrapone buena y mala granularidad. El sentido de fondo es:

* si los items son demasiado grandes, no se pueden gestionar ni inspeccionar bien,  
* si están razonablemente partidos, se puede ver progreso, bloquear menos cosas y coordinar mejor.

Esto conecta perfecto con Mike Cohn y con Rubin:

* los PBIs cercanos deberían ser suficientemente pequeños como para entrar en un sprint,  
* y las tareas suelen bajarse a tamaño bastante chico durante el Sprint Planning.

---

## **23\) Múltiples niveles de planificación**

La **página 28** del ppt muestra una jerarquía muy clara:

* estrategia,  
* portfolio,  
* producto,  
* release,  
* iteración,  
* día.

La **página 29** agrega una tabla excelente con:

* horizonte,  
* quién participa,  
* foco,  
* entregable.  
  Ahí dice, por ejemplo:  
* **Portfolio**: 1 año o más  
* **Producto**: varios meses o más  
* **Release**: 3 o menos a 9 meses  
* **Iteración**: 1 semana a 1 mes  
* **Día**: diario.

Mike Cohn plantea algo muy parecido con la “planning onion”, donde distingue justamente portfolio, product, release, iteration y day. Rubin también dedica capítulos a **multilevel planning**.

Esto es importante porque baja una idea fuerte:  
**Scrum no elimina la planificación; la distribuye en distintos horizontes.**

---

## **24\) Ojo: release planning no es un evento formal de Scrum 2020**

Acá hay otro punto fino de parcial.

El ppt dedica varias páginas a:

* planificación de portfolio,  
* producto,  
* release,  
* sprint.

Mike Cohn y Rubin también tratan **release planning** como algo muy importante en la práctica ágil.

Pero la **Scrum Guide 2020** no define “Release Planning” como **evento formal de Scrum**. Los eventos formales siguen siendo cinco. Entonces, release planning es:

* una práctica útil,  
* coherente con Scrum,  
* muy usada,  
* pero no un evento formal del núcleo mínimo del framework.

Esto puede ser muy preguntable.

---

## **25\) Planificación de release**

Aunque el ppt no desarrolla mucho texto en esas páginas, sí deja varias ideas visuales:

* hay relación entre releases y sprints,  
* puede haber distintas cadencias,  
* y la release planning trabaja a un nivel de granularidad mayor que el sprint.

Mike Cohn explica que la release planning responde básicamente:

* qué conjunto de funcionalidades queremos,  
* con qué recursos,  
* y en qué horizonte tentativo.  
  Además, la liga con story points y velocidad: sumás tamaño estimado, dividís por velocidad esperada y obtenés cantidad de iteraciones aproximadas, que luego mapeás al calendario.

Rubin agrega que release planning también puede variar según restricción dominante:

* fecha fija,  
* alcance fijo,  
* o combinaciones tensionadas.

---

## **26\) Granularidad según nivel de planificación**

La **página 36** del ppt es muy buena porque dice:

* meses,  
* semanas,  
* días,  
* horas,  
  y lo traduce a:  
* más grande que un release,  
* más grande que un sprint,  
* listo para un sprint,  
* tareas.

Eso sirve para no mezclar niveles:

* **portfolio/producto**: visión más grande,  
* **release**: bloques grandes de entrega,  
* **sprint**: PBIs listos para entrar,  
* **daily/taskboard**: tareas concretas.

---

## **27\) Cadencia de releases y sprints**

La **página 39** del ppt muestra tres posibilidades:

* release luego de múltiples sprints,  
* release luego de cada sprint,  
* release luego de cada feature.

Esto es buenísimo porque rompe una idea simplista:  
**Scrum no obliga a una única cadencia de liberación.**

Lo obligatorio es la cadencia del sprint y la existencia de incremento usable. Después, la liberación de valor al mercado o al usuario puede tener distintas estrategias según contexto. La propia Scrum Guide 2020 aclara que un increment puede entregarse antes del final del sprint y que la Sprint Review no es una puerta obligatoria para liberar valor.

---

## **28\) Métricas en ambientes ágiles**

La **página 42** abre esta sección, y la **página 43** mete una idea excelente:  
**“La medición es una salida, no una actividad.”**  
Y propone una filosofía minimalista:  
**medir lo necesario y nada más.**

En la **página 44**, el ppt además vincula la elección de métricas con dos principios ágiles:

* satisfacer al cliente mediante entregas tempranas y continuas,  
* y considerar al software funcionando como principal medida de progreso.

Esto te da una idea clave:  
**en ágil, las métricas tienen que ayudar a ver valor entregado y capacidad real de adaptación, no burocracia vacía.**

---

## **29\) Running Tested Features (RTF)**

La **página 45** presenta **Running Tested Features** como métrica. La idea es contar features que no solo existen, sino que están:

* corriendo,  
* integradas,  
* y probadas.

Conceptualmente, esta métrica es muy ágil porque evita inflar progreso con cosas “en proceso” o “medio hechas”. Va alineada con:

* software funcionando,  
* incremento usable,  
* Definition of Done.

---

## **30\) Capacidad como métrica de planificación**

La **página 46** del ppt pone la fórmula:  
**WH × DA \= Capacidad**  
donde:

* WH \= horas de trabajo disponibles por día,  
* DA \= días disponibles en la iteración.

Después, la **página 47** muestra un ejemplo de evolución de capacidad por sprint y la compara con story points completados.

Esto sirve para entender algo central:  
**la capacidad no es lo mismo que la velocidad.**  
La capacidad es disponibilidad potencial de trabajo. La velocidad es resultado histórico del trabajo efectivamente completado.

---

## **31\) Velocidad (Velocity)**

La **página 48** del ppt define velocidad como una medida del progreso del equipo, calculada como la suma de story points de las user stories completas en la iteración. También aclara:

* se cuentan solo las completas, no las parcialmente completas,  
* y la velocidad corrige errores de estimación.

Mike Cohn dice básicamente lo mismo:

* velocity es la tasa de progreso del equipo,  
* se obtiene sumando story points completados,  
* y permite transformar tamaño estimado en duración aproximada.  
  Además explica algo muy importante: cuando la velocidad observada difiere de la supuesta, el plan se corrige solo sin necesidad de reestimar todo.

Entonces:  
**velocity sirve para forecast del equipo, no para fantasear precisión absoluta.**

---

## **32\) Burndown y seguimiento de progreso**

La **página 25** muestra **Sprint Burndown Charts**, con trayectorias:

* a tiempo,  
* adelantado,  
* atrasado.

La **página 26** habla de gráficos de seguimiento del producto.  
Rubin también trata burndown y burnup como herramientas para visualizar avance de sprint o release.

Lo importante para entenderlos no es el dibujo en sí, sino la lógica:

* hacen visible tendencia,  
* permiten inspección,  
* ayudan a detectar desvíos,  
* pero no reemplazan el juicio ni el empirismo.

---

## **33\) Qué y cuándo estimar**

La **página 30** del ppt abre esta pregunta y después la responde indirectamente con la planificación multinivel.  
Rubin lo baja mejor en *Essential Scrum*:

* hay estimaciones en backlog/portfolio,  
* en product backlog,  
* y también a nivel tareas,  
  pero no todas sirven para lo mismo ni tienen el mismo nivel de detalle.

Mike Cohn también insiste en separar:

* estimación de tamaño,  
* estimación de duración,  
* y scheduling.  
  El tamaño relativo en story points no es directamente tiempo; el tiempo se deriva usando velocity.

---

## **34\) Scrum y planificación: no seguir un plan ciego**

Mike Cohn dice algo re importante:  
el objetivo no es tener un plan rígido perfecto, sino un proceso de planificación que permita **revisar y cambiar** el plan inteligentemente. Incluso dice que lo importante no es el plan en sí, sino la **actividad de planificar**.

Eso encaja perfecto con el último slide del ppt:  
**“Recordemos… ¿Dónde está la Agilidad?”**  
La agilidad está precisamente en:

* iterar,  
* inspeccionar,  
* adaptar,  
* entregar,  
* medir lo justo,  
* y replantear cuando la realidad cambia.

---

# **Qué estudiar sí o sí para el parcial**

Tenés que poder explicar bien:

* diferencia entre Ágil y Scrum,  
* qué es empirismo,  
* pilares de Scrum: transparencia, inspección y adaptación,  
* valores ágiles y valores de Scrum,  
* definición de Scrum 2020,  
* composición del Scrum Team,  
* responsabilidades de Product Owner, Developers y Scrum Master,  
* eventos de Scrum y propósito de cada uno,  
* timeboxes,  
* artefactos y compromisos,  
* qué son Product Goal, Sprint Goal y Definition of Done,  
* qué diferencia hay entre DoR y DoD,  
* qué es refinamiento del Product Backlog,  
* qué significa capacidad del equipo,  
* qué es velocidad,  
* cómo se calcula,  
* qué muestran burndown/burnup,  
* qué es RTF,  
* qué significa planificación multinivel,  
* diferencia entre planificación de producto, release, sprint y día,  
* y por qué release planning es útil pero no es un evento formal de Scrum 2020\.

---

# **Lecturas recomendadas para complementar**

## **1\. PPT 07**

Es el que mejor sintetiza:

* cultura ágil,  
* empirismo,  
* framework Scrum,  
* timeboxes,  
* DoR / DoD,  
* capacidad,  
* planning multinivel,  
* métricas.

## **2\. Scrum Guide 2020**

Es la base más importante para examen si preguntan por Scrum “oficial”:

* definición,  
* roles,  
* eventos,  
* artefactos,  
* compromisos,  
* valores.

## **3\. Agile Estimating and Planning – Mike Cohn**

Te sirve muchísimo para:

* planning multinivel,  
* release planning,  
* sprint planning,  
* story points,  
* velocity,  
* relación entre tamaño, velocidad y duración.

## **4\. Essential Scrum – Kenneth Rubin**

Muy bueno para:

* bajar Scrum a práctica real,  
* capacidad,  
* planning principles,  
* multilevel planning,  
* release planning,  
* sprinting y seguimiento.

---

# **Posibles preguntas de parcial con respuesta modelo**

## **1\. ¿En qué se basa Scrum?**

Scrum se basa en empirismo y Lean. Su lógica central es que el conocimiento proviene de la experiencia y de la toma de decisiones basada en lo observado. Por eso trabaja con transparencia, inspección y adaptación.

## **2\. ¿Qué es Scrum?**

Es un marco de trabajo liviano para generar valor mediante soluciones adaptativas frente a problemas complejos.

## **3\. ¿Cuáles son los roles o responsabilidades dentro del Scrum Team?**

Product Owner, Scrum Master y Developers. El Product Owner maximiza valor y gestiona backlog; los Developers construyen el incremento; el Scrum Master ayuda a que Scrum funcione correctamente y mejora la efectividad del equipo.

## **4\. ¿Cuáles son los artefactos y sus compromisos?**

Product Backlog con Product Goal, Sprint Backlog con Sprint Goal, e Increment con Definition of Done.

## **5\. ¿Qué diferencia hay entre DoR y DoD?**

La Definition of Ready es una práctica útil para saber si un item está suficientemente preparado para entrar a un sprint. La Definition of Done es el criterio formal de terminado del incremento y sí forma parte explícita de Scrum 2020\.

## **6\. ¿Para qué sirve la Sprint Planning?**

Para iniciar el sprint definiendo qué trabajo se hará, por qué ese sprint es valioso y cómo se realizará el trabajo. De ahí salen Sprint Goal y Sprint Backlog.

## **7\. ¿Cuál es el objetivo de la Daily Scrum?**

Inspeccionar el progreso hacia el Sprint Goal y adaptar el Sprint Backlog según haga falta. Es una reunión breve de coordinación del equipo, no un reporte jerárquico.

## **8\. ¿Qué es la velocidad?**

Es una métrica del progreso del equipo que se calcula sumando los story points de las historias terminadas en la iteración. Solo se cuenta trabajo completo.

## **9\. ¿Qué es la capacidad?**

Es la disponibilidad real de trabajo del equipo durante el sprint, considerando horas útiles, días disponibles, ausencias, otras actividades Scrum y compromisos externos.

## **10\. ¿Qué significa planificación multinivel?**

Que en ágil no se planifica una sola vez, sino en distintos horizontes: portfolio, producto, release, iteración y día. Cada nivel tiene distinto foco, distinto horizonte y distinto entregable.

## **11\. ¿Release Planning es un evento formal de Scrum?**

No. Es una práctica muy usada y muy útil en planificación ágil, pero no es uno de los eventos formales definidos por la Scrum Guide 2020\.

## **12\. ¿Qué métricas son coherentes con un enfoque ágil?**

Las que ayudan a ver software funcionando, progreso real y capacidad de entrega, como RTF, capacidad, velocidad y gráficos de seguimiento, evitando medir por medir.

---

## **Mini resumen final para memorizar**

Este ppt enseña que Scrum 2020 es un framework ágil basado en empirismo: transparencia, inspección y adaptación. Su estructura mínima la forman un Scrum Team con Product Owner, Scrum Master y Developers; eventos con cadencia fija como Sprint Planning, Daily Scrum, Sprint Review y Sprint Retrospective; y artefactos con compromisos claros como Product Goal, Sprint Goal y Definition of Done. La planificación en ágil no desaparece: se reparte en varios niveles, desde portfolio y producto hasta release, sprint y día. Para que eso funcione, el equipo necesita backlog refinado, capacidad realista, objetivos claros y métricas mínimas pero útiles, como velocidad, capacidad, burndown y RTF. La idea de fondo no es cumplir un ritual, sino construir valor de manera visible, adaptable y sostenida.

Si querés, seguimos con el **08** con el mismo formato.

