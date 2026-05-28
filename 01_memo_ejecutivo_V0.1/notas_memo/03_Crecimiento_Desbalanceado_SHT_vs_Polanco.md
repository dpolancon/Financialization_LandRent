---
type: CORE_note
status: active
priority: urgent
project: suelo_credito_formacion_capital
core_id: "03"
theme: crecimiento_desbalanceado
---

# 03  — Crecimiento desbalanceado: SHT vs contribución propia

## Pregunta que resuelve esta nota

¿Qué significa crecimiento desbalanceado en Stiglitz–Hirano–Toda y cómo se relaciona con la contribución propia sobre desproporcionalidad entre demanda efectiva, acumulación y capacidades productivas?

## Respuesta que debe producir

Una comparación estricta, sin colapsar ambos enfoques:

- En SHT, el crecimiento desbalanceado ayuda a explicar cómo la valorización del suelo puede separarse de la acumulación de capital producido.
- En la contribución propia, el crecimiento desbalanceado remite a una desproporcionalidad entre acumulación de capital, formación de capacidades productivas, utilización y demanda efectiva.
- La conexión útil no es que ambas teorías sean idénticas, sino que la contribución propia permite traducir la sobrevaloración del suelo hacia una pregunta más general sobre desproporciones entre expansión patrimonial, inversión y capacidades productivas.

## Preguntas del IP absorbidas aquí

- ¿Por qué SHT señalan que el crecimiento desbalanceado es condición necesaria?
- ¿Qué entienden ellos por crecimiento desbalanceado?
- ¿Cómo se relaciona eso con mi contribución sobre crecimiento desbalanceado?

## Qué NO debe hacer esta nota

No usar la broma interna “el gran Diego Polanco”.  
No presentar el capítulo de tesis como teoría de precios del suelo.  
No decir que SHT y la contribución propia usan el mismo concepto.  
No abrir una discusión completa sobre capacidad instalada fuera del brief.

## Salida exportable

Una tabla SHT / contribución propia y un párrafo de 180–250 palabras para el memo.

## Bloque INPUT — Fuentes y prompts

### Función de esta nota CORE

Aclarar la noción de crecimiento desbalanceado en SHT y traducirla críticamente hacia la contribución propia sobre demanda efectiva y capacidades productivas.

### Fuentes a seleccionar en NotebookLM

Principales SHT:

- PDF001 — Hirano & Toda, *Unbalanced Growth and Land Overvaluation*.
- PDF008 — Hirano, Jinnai & Toda, *Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles*.
- PDF012 — Toda, *Land Bubbles Despite Non-Vanishing Rents*.

Fuente propia:

- `CriticalReplication_CU_Shaikh_DiegoPolanco.pdf`.

### Prompt 3A — Crecimiento desbalanceado en SHT

Usando solo PDF001, PDF008 y PDF012, explica qué entienden estos autores por crecimiento desbalanceado y por qué esa condición es necesaria para el Land Overvaluation Theorem.

Distingue:

- crecimiento desbalanceado;
- burbuja;
- especulación;
- sobrevaloración;
- leverage;
- rent-yield observado;
- renta pura del suelo.

Devuelve:

1. definición operativa de crecimiento desbalanceado en SHT;
2. por qué es condición necesaria para la sobrevaloración del suelo;
3. qué papel juegan productividad diferencial, elasticidad de sustitución y leverage;
4. qué advertencia introduce PDF012 sobre rent-yields;
5. párrafo exportable de 180–220 palabras.

### Prompt 3B — Comparación con contribución propia

Usando ahora PDF001, PDF008, PDF012 y `CriticalReplication_CU_Shaikh_DiegoPolanco.pdf`, compara el uso de “crecimiento desbalanceado” en Stiglitz–Hirano–Toda con la contribución propia desarrollada en el capítulo de tesis.

La comparación debe ser estricta:

- No digas que ambos conceptos son idénticos.
- No digas que el capítulo de tesis es una teoría de precios del suelo.
- Explica que en el capítulo el crecimiento desbalanceado se formula como desproporcionalidad entre acumulación de capital y formación de capacidades productivas, mediada por la elasticidad de transformación.
- Explica cómo esa idea puede ayudar a traducir el problema SHT hacia una economía política de demanda efectiva y capacidades productivas.

Devuelve una tabla con columnas:

1. dimensión;
2. SHT;
3. contribución propia;
4. conexión útil para el brief;
5. advertencia.

Luego entrega un párrafo exportable de 180–220 palabras para el IP.

## Bloque OUTPUT — Captura y depuración

### Pregunta enviada 3-Contexto

#### Nota Core 03: Crecimiento desbalanceado: SHT vs. Enfoque propio de desproporcionalidad

El propósito de esta nota es sintonizar y clarificar la divergencia teórica en torno al concepto de _crecimiento desbalanceado_, delimitando estrictamente el mecanismo de oferta sectorial de la literatura neoclásica frente a la propuesta de clausura macroeconómica de este proyecto basada en las desproporciones de la acumulación real.

#### 1. El crecimiento desbalanceado en la literatura Stiglitz-Hirano-Toda (SHT)

En la vertiente neoclásica de esta literatura, el crecimiento desbalanceado se define desde el lado de la oferta como una asimetría estructural en las tasas de progreso tecnológico o en la productividad sectorial (Hirano & Toda, 2025b; Hirano et al., 2024). Específicamente, describe escenarios donde la productividad laboral en los sectores reproducibles (como la manufactura) avanza de manera exponencialmente más rápida que la productividad del suelo dentro de los sectores no reproducibles (Hirano & Toda, 2025b). Para este enfoque, el crecimiento desbalanceado constituye una condición necesaria para la emergencia de burbujas racionales y la sobrevaloración del suelo debido a dos factores:

##### Ruptura de la eficiencia convencional

Los análisis tradicionales asumen sendas de crecimiento balanceado o funciones de producción agregadas rígidas (como la Cobb-Douglas con elasticidad de sustitución $\sigma = 1$), lo cual garantiza matemáticamente que la tasa de interés ($R$) sea estrictamente superior a la tasa de crecimiento económico ($G$), imposibilitando la existencia de esquemas Ponzi o burbujas (Toda, 2025).

##### El Teorema de Sobrevaloración del Suelo

Al remover esta restricción y permitir un crecimiento desbalanceado junto a una elasticidad de sustitución intersectorial mayor a la unidad ($\sigma > 1$), el precio de la tierra comienza a crecer de forma sistemática por encima de sus fundamentos —es decir, el flujo capitalizado de sus rentas actuales— (Hirano & Toda, 2025b). Bajo estas condiciones, el suelo, en tanto activo no producido de oferta fija, se transforma en una reserva pura de valor que succiona los ahorros agregados de la economía (Hirano et al., 2024).

#### 2. El crecimiento desbalanceado en la contribución propia del proyecto

En el marco macroeconómico desarrollado por este proyecto, el crecimiento desbalanceado adquiere un significado ontológico radicalmente distinto. Lejos de reducirse a un diferencial técnico en los coeficientes exógenos de progreso tecnológico, el concepto remite a una desproporcionalidad macroeconómica intrínseca al régimen de acumulación que vincula la demanda efectiva, la distribución del excedente y la solvencia financiera de las firmas (Polanco, 2026).

##### La Elasticidad de Transformación ($\theta$)

El núcleo de este enfoque descansa sobre cómo la acumulación de capital físico ($K$) se traduce efectivamente en la creación de capacidad productiva real ($Y^p$), un proceso regulado por la elasticidad de transformación $\theta \equiv \partial \ln Y^p / \partial \ln K$ (Polanco, 2026). Cuando el régimen experimenta desproporciones estructurales ($\theta < 1$), el ritmo de expansión de la capacidad instalada física se desalinea de las necesidades de reproducción corporativa, agudizando las tensiones sobre los balances.

##### El nexo de Demanda Efectiva y Excedente

El desbalance macroeconómico se expresa como una brecha persistente entre la capacidad productiva física creada, su tasa efectiva de utilización y la escala de la demanda efectiva requerida para realizar monetariamente la masa de excedente social (Polanco, 2026). En lugar de postular equilibrios neoclásicos mediados por vectores de precios óptimos, el sistema queda clausurado y regulado por la dinámica del conflicto distributivo, determinando la vulnerabilidad o estabilidad de la reproducción patrimonial (Polanco, 2026).

#### 3. Articulación y traducción crítica (La conexión metodológica)

La vinculación analítica clave para el brief consiste en no forzar una identidad conceptual entre ambas teorías, sino utilizar el enfoque propio de desproporcionalidad como una matriz analítica superior capaz de traducir y absorber las regularidades identificadas por SHT.

La literatura de SHT demuestra matemáticamente que el crecimiento sectorialmente asimétrico provoca que el valor patrimonial de la tierra se divorcie de la acumulación real de bienes de capital producido (Hirano & Toda, 2025b). El enfoque propio traduce esta sobrevaloración neoclásica hacia una problemática macroeconómica general de balances: ¿cómo la expansión de la riqueza financiera abstracta (burbujas inmobiliarias y rentas capturadas por propietarios financiarizados) profundiza las desproporciones sitemáticas frente a la formación de capacidades productivas reales ($\theta$) y su posterior validación en el mercado mediante la demanda efectiva? (Polanco, 2026). Bajo esta traducción crítica, la inflación del suelo deja de ser una distorsión aislada de precios relativos factoriales y pasa a ser entendida como una patología distributiva que extrae excedente real para alimentar balances financieros ilíquidos, deprimiendo la inversión productiva real.

#### 4. Tabla comparativa de enfoques

|**Dimensión Analítica**|**Enfoque Stiglitz-Hirano-Toda (SHT)(Hirano & Toda, 2025b; Hirano et al., 2024)**|**Contribución Propia del Proyecto(Polanco, 2026)**|
|---|---|---|
|**Definición Operativa**|Crecimiento asimétrico de la productividad entre factores y sectores exógenos.|Desproporcionalidad sistémica entre la acumulación de capital, la capacidad real y la demanda efectiva.|
|**Mecanismo de Desacople**|Regulado por una elasticidad de sustitución intersectorial mayor a la unidad ($\sigma > 1$).|Regulado por la elasticidad de transformación de la capacidad productiva ($\theta$).|
|**Rol del Suelo**|Activo no producido que opera como reserva de valor y genera burbujas racionales de carteras.|Activo real divisible cuya inflación patrimonial abstracta extrae excedente y drena liquidez.|
|**Determinación del Equilibrio**|Ajuste de portafolios neoclásicos bajo expectativas racionales cortoplacistas (equilibrios momentáneos).|Dinámica del excedente corporativo, conflicto distributivo y validación por demanda efectiva.|
|**Impacto Sistémico**|El suelo desplaza al capital real (_crowding-out_), mermando la tasa de crecimiento de largo plazo.|La acumulación patrimonial autonomizada asfixia la creación y utilización de capacidad instalada real.|

#### 5. Párrafo exportable para el memo dirigido al IP

El análisis del crecimiento desbalanceado constituye el eje articulador para comprender la desconexión macroeconómica entre la expansión de la riqueza financiera y el desarrollo de las capacidades productivas reales. En la literatura neoclásica de Stiglitz-Hirano-Toda, este fenómeno se formaliza desde la oferta como un crecimiento asimétrico de la productividad sectorial, operando como una condición necesaria para que el precio del suelo se desligue de sus fundamentos y aloje burbujas racionales duraderas bajo una elasticidad de sustitución superior a la unidad (Hirano & Toda, 2025b; Hirano et al., 2024). Por su parte, el reencuadre propio de este proyecto resitúa la problemática en la órbita de la economía política del excedente, conceptualizándola como una desproporcionalidad sistémica entre la tasa de acumulación de capital real, la formación de capacidad productiva física —gobernada por la elasticidad de transformación ($\theta$)— y su realización en el mercado mediante la demanda efectiva (Polanco, 2026). La vinculación analítica entre ambos enfoques no radica en una falsa identidad de conceptos, sino en la capacidad de nuestro marco de balances para traducir la sobrevaloración del suelo de SHT hacia una contradicción general del régimen de acumulación. De este modo, la inflación inmobiliaria se devela como un mecanismo distributivo donde la valorización patrimonial abstracta extrae y drena los flujos de liquidez, agravando las desproporciones entre la expansión de la riqueza financiera y la utilización efectiva de la capacidad instalada real (Polanco, 2026).

#### Referencias

- Hirano, T., Jinnai, R., & Toda, A. A. (2024). _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_ (Documento de trabajo arXiv:2211.13100v7 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Toda, A. A. (2025b). _Unbalanced Growth and Land Overvaluation_ (CIGS Working Paper Series No. 25-011E). The Canon Institute for Global Studies. (Aceptado para publicación en _Proceedings of the National Academy of Sciences_).
    
- Polanco, D. (2026). _Critical Replication of Shaikh’s Capacity Utilization Measure_ (Documento de trabajo / obra en progreso). Departamento de Economía, Universidad de Massachusetts Amherst.
    
- Toda, A. A. (2025). Land bubbles despite non-vanishing rents. _Economics Letters_, _257_(112708), 1-4. [https://doi.org/10.1016/j.ecolet.2025.112708](https://www.google.com/search?q=https://doi.org/10.1016/j.ecolet.2025.112708)


### Respuesta bruta 3A

#### Nota Core 3A: Crecimiento desbalanceado en la literatura Stiglitz-Hirano-Toda (SHT)

##### Glosario de términos y distinciones conceptuales

- **Crecimiento desbalanceado:** Se refiere a una asimetría estructural en el progreso tecnológico desde el lado de la oferta, donde la productividad de los sectores no intensivos en suelo (como la manufactura o la economía del conocimiento) se expande a un ritmo significativamente mayor que la de los sectores rezagados o dependientes de la tierra.
    
- **Burbuja:** Componente del precio de mercado de un activo que excede de forma estricta su valor fundamental, definido formalmente como el valor presente descontado de sus flujos de dividendos o rentas físicas a lo largo de la trayectoria de equilibrio macroeconómico real.
    
- **Especulación:** Práctica financiera orientada a la adquisición y retención de activos no producidos motivada por la expectativa de ganancias de capital en el corto plazo, transformando al suelo en un vehículo de portafolio y reserva de ahorro dinástico en lugar de un insumo puramente productivo.
    
- **Sobrevaloración:** Fenómeno duradero en el cual el precio de mercado del suelo crece de forma sistemática por encima del valor presente capitalizado de sus rentas fundamentales corrientes, impulsado hacia arriba por el incremento de los ingresos agregados y los salarios de la población.
    
- **Leverage:** Ratio o límite máximo de apalancamiento financiero dictado por los contratos de crédito y las regulaciones institucionales que determina la cantidad de deuda que los agentes económicos pueden contraer utilizando sus activos colaterales.
    
- **Renta pura del suelo:** El rendimiento económico directo derivado exclusivamente de la escasez física y el uso del espacio geográfico no reproducible provisto por la naturaleza de forma fija, disociada de cualquier mejora física construida sobre ella.
    
- **Rent-yield observado:** El rendimiento por alquiler visible en las cuentas nacionales y los registros inmobiliarios, calculado como la ratio o proporción existente entre los alquileres totales generados por una propiedad residencial agregada y su precio total de mercado.
    

#### Definición operativa del crecimiento desbalanceado en la arquitectura SHT

En la modelización de Stiglitz-Hirano-Toda, el crecimiento desbalanceado se define operativamente como una divergencia persistente en las tasas de progreso tecnológico sectorial. Específicamente, describe un escenario donde la productividad laboral y del capital en el sector reproducible avanza exponencialmente, mientras que la productividad de la tierra en el sector intensivo en suelo permanece rezagada. Bajo esta asimetría, los salarios agregados y la riqueza medida de la economía se expanden con rapidez, mientras que las rentas físicas fundamentales de la tierra decaen en términos relativos dentro de la composición del producto total. Asimismo, dentro de los desarrollos de macro-finanzas con fricciones de crédito, el crecimiento desbalanceado puede surgir endógenamente como un régimen macroeconómico provocado por la laxitud crediticia.

#### Por qué el crecimiento desbalanceado es condición necesaria para la sobrevaloración del suelo

El crecimiento desbalanceado es una condición necesaria para validar el _Teorema de Sobrevaloración del Suelo_ debido a las restricciones de equilibrio estacionario de los modelos tradicionales. En una senda de crecimiento balanceado convencional (donde todos los sectores se expanden a la misma tasa o bajo funciones Cobb-Douglas con elasticidad unitaria), la tasa de interés real ($R$) supera estructuralmente a la tasa de crecimiento económico ($G$) ($R > G$), lo que garantiza la eficiencia de Pareto y bloquea la formación de burbujas o esquemas Ponzi.

El crecimiento desbalanceado quiebra esta inmutabilidad. Al expandirse los ingresos de los agentes más rápido que las rentas físicas generadas por la tierra, la demanda del suelo como vehículo de ahorro dinástico eleva su precio de mercado a la par de los salarios. Esto desvincula el precio del activo no producido respecto de la capitalización de sus flujos productivos corrientes, permitiendo una sobrevaloración estructural duradera en el largo plazo.

#### El papel de la productividad diferencial, la elasticidad de sustitución y el leverage

##### Productividad diferencial

La productividad diferencial actúa como la fuerza motriz inicial al generar la brecha permanente entre la evolución de las remuneraciones al trabajo y el rendimiento marginal del suelo. Mientras que la abundancia de bienes reproducibles deprime sus precios relativos, la escasez fija del suelo intensifica su atractivo como depósito alternativo de valor para absorber los excedentes de ahorro de los trabajadores jóvenes.

##### Elasticidad de sustitución intersectorial ($\sigma > 1$)

La condición de que la elasticidad de sustitución entre el suelo y los factores reproducibles sea estrictamente mayor que uno ($\sigma > 1$) es indispensable para que la sobrevaloración sea sostenible sin asfixiar la subsistencia física del sistema. Cuando $\sigma > 1$, la economía puede sustituir progresivamente el suelo physical mediante la adición de capital reproducible (por ejemplo, construyendo edificios de mayor altura sobre el suelo fijo). Esto provoca que la participación de las rentas fundamentales de la tierra en el Producto Interno Bruto tienda a disminuir en términos reales. Paradoxalmente, aunque su rol productivo directo decae, su valor de mercado se dispara porque los agentes demandan el activo como un depósito escaso para canalizar sus crecientes ingresos.

##### Leverage

El _leverage_ opera como el interruptor macro-financiero que gobierna las transiciones de fase dentro de la economía. Si los límites de apalancamiento se relajan y superan un umbral crítico, el mecanismo del acelerador financiero vincula positivamente la inversión productiva con el valor colateral de la tierra. Esta retroalimentación rompe la senda de crecimiento balanceado e induce una transición endógena hacia un régimen de crecimiento desbalanceado donde los precios inmobiliarios se autonomizan, alojando burbujas de activos que drenan la liquidez del sistema.

#### La advertencia de PDF012 sobre los rent-yields observados

##### La ilusión de stationarity inmobiliaria

Alexis Akira Toda (2025) introduce una advertencia metodológica fundamental para invalidar las críticas empíricas tradicionales dirigidas contra los modelos de burbujas racionales. La literatura escéptica suele afirmar que los mercados inmobiliarios no albergan burbujas debido a que la ratio alquiler-precio (_rent yield_ observado) se muestra altamente estacionaria y constante en los datos históricos, argumentando que una burbuja teórica requeriría que esta ratio colapsara de forma continua hacia cero.

##### La disociación entre estructura y suelo

Toda (2025) demuestra que este sesgo empírico surge de la omisión analítica de no distinguir entre la renta de la _estructura física de la vivienda_ y la _renta pura del suelo_. Mientras que la rentabilidad de las estructuras residenciales (bienes de capital producidos sujetos a depreciación y reproducción) permanece relativamente estable en el tiempo debido al arbitraje competitivo, la renta pura del suelo (activo no producido) sufre una mutación drástica en contextos de crecimiento económico. Por consiguiente, el rendimiento por alquiler observado a nivel agregado puede simular una perfecta estabilidad en las series de tiempo, enmascarando por completo la emergencia inevitable de una burbuja masiva alojada de forma exclusiva en el componente de la tierra.

#### Párrafo exportable para el memo dirigido al IP

El análisis riguroso de la literatura neoclásica de Stiglitz-Hirano-Toda revela que el crecimiento desbalanceado, definido como el avance asimétrico de la productividad en sectores no intensivos en suelo, constituye la condición necesaria subyacente para la validación del _Teorema de Sobrevaloración del Suelo_ (Hirano & Toda, 2025b; Hirano et al., 2024). Cuando este desbalance tecnológico se conjuga con una elasticidad de sustitución intersectorial mayor a la unidad ($\sigma > 1$), la participación de la tierra en la producción real decae, pero su precio de mercado se desvincula de sus fundamentos productivos reales (Hirano & Toda, 2025b). Este desacople permite que el valor de la tierra aumente a la par de los salarios agregados, impulsado por una persistente demanda de ahorro e intensificado cuando la relajación del _leverage_ crediticio activa el acelerador financiero (Hirano & Toda, 2025b; Hirano et al., 2024). Asimismo, es crítico incorporar la advertencia metodológica de Toda (2025), quien demuestra que la aparente estabilidad en las series de tiempo del _rent-yield_ observado enmascara la gestación de burbujas racionales, debido a la falta de distinción entre la rentabilidad reproducible de las estructuras físicas y la valorización especulativa de la renta pura del suelo. Este marco neoclásico proporciona la fundamentación matemática para justificar cómo los activos no producidos drenan la liquidez agregada del sistema económico (Hirano & Toda, 2025b; Toda, 2025).

#### Referencias

- Hirano, T., Jinnai, R., & Toda, A. A. (2024). _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_ (Documento de trabajo arXiv:2211.13100v7 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Toda, A. A. (2025b). _Unbalanced Growth and Land Overvaluation_ (CIGS Working Paper Series No. 25-011E). The Canon Institute for Global Studies. (Aceptado para publicación en _Proceedings of the National Academy of Sciences_).
    
- Toda, A. A. (2025). Land bubbles despite non-vanishing rents. _Economics Letters_, _257_(112708), 1-4. [https://doi.org/10.1016/j.ecolet.2025.112708](https://www.google.com/search?q=https://doi.org/10.1016/j.ecolet.2025.112708)

### Respuesta bruta 3B

#### Nota Core 3B: Comparación y traducción crítica del crecimiento desbalanceado

El objetivo de esta sección es establecer un deslinde epistemológico y metodológico estricto entre la modelización del crecimiento desbalanceado en la literatura neoclásica de Stiglitz-Hirano-Toda (SHT) y la contribución macroeconómica propia desarrollada en el capítulo de tesis (Polanco, 2026). Se enfatiza que ambos marcos operan bajo paradigmas fundacionales distintos, utilizando la divergencia de forma analítica para construir una matriz de traducción hacia la economía política heterodoxa.

#### 1. Matriz analítica de comparación interteórica

La siguiente tabla sistematiza las diferencias operacionales, los puntos de articulación conceptual y las advertencias metodológicas necesarias para el brief institucional.

##### Tabla comparativa de desproporciones macroeconómicas

|**Dimensión**|**Enfoque Stiglitz-Hirano-Toda (SHT)(Hirano & Toda, 2025b; Hirano et al., 2024)**|**Contribución Propia del Proyecto(Polanco, 2026)**|**Conexión Útil para el Brief**|**Advertencia Metodológica**|
|---|---|---|---|---|
|**Naturaleza del desbalance**|Asimetría exógena (o endógena vía apalancamiento) en las tasas de progreso tecnológico de la oferta sectorial.|Desproporcionalidad estructural macroeconómica entre la acumulación real de capital y el ritmo de generación de capacidad material.|Permite reconceptualizar la sobrevaloración del suelo como un síntoma agregado de contradicciones profundas en la base real de acumulación.|**No colapsar ambos conceptos.** SHT describe precios factoriales dinámicos; la contribución propia mapea la base física reproducible agregada.|
|**Mecanismo paramétrico**|Regulado estrictamente por la elasticidad de sustitución intersectorial superior a la unidad ($\sigma > 1$).|Formulado a partir de la **elasticidad de transformación de la capacidad productiva ($\theta$)** respecto al stock de capital ($K$).|Ofrece un instrumental heterodoxo para medir cuándo la inversión física deja de traducirse eficientemente en capacidad instalada real, forzando desvíos de riqueza.|**El capítulo de tesis no es una teoría de precios del suelo.** Es un análisis de la dinámica del stock de capital y su utilización, no de asignación inmobiliaria.|
|**Determinación y clausura**|Ajuste de carteras optimizadoras intertemporales bajo condiciones de arbitraje y expectativas racionales.|Clausura regulada por la **dinámica de la demanda efectiva**, la utilización efectiva de la capacidad física y el conflicto distributivo corporativo.|Proporciona el andamiaje macroeconómico para traducir el "desacople" neoclásico de SHT hacia una rigurosa economía política del excedente y su realización.|La estabilidad temporal de las ratios de rentabilidad en SHT responde a sustituciones neoclásicas; en el marco propio, responde a patrones institucionales de utilización.|

#### 2. Párrafo exportable para el memo dirigido al IP

La comparación metodológica entre la literatura neoclásica de Stiglitz-Hirano-Toda (SHT) y la contribución de este proyecto demuestra que el concepto de crecimiento desbalanceado puede actuar como un potente pivote de traducción macroeconómica, sin colapsar ontológicamente marcos teóricos divergentes. Mientras que en los modelos de SHT el crecimiento desbalanceado se reduce a una asimetría técnica de la oferta sectorial regulada por la elasticidad de sustitución ($\sigma > 1$) (Hirano & Toda, 2025b; Hirano et al., 2024), en nuestro capítulo de tesis este fenómeno se formula estrictamente como una desproporcionalidad macroeconómica entre la acumulación de capital y la formación de capacidades productivas reales, mediada por la elasticidad de transformación ($\theta$) (Polanco, 2026). Es crucial advertir que el capítulo de tesis no constituye una teoría de precios del suelo; su utilidad radica en que ofrece una clausura analítica basada en la economía política heterodoxa. Al introducir el parámetro $\theta$, logramos reencuadre el problema del desacople inmobiliario neoclásico hacia una discusión sistémica sobre los límites distributivos del excedente, la dinámica de utilización de la capacidad instalada física y los requerimientos de la demanda efectiva. De este modo, la sobrevaloración del suelo de SHT se reinterpreta como una consecuencia macroeconómica de la incapacidad del capital para expandir la base material reproducible de producción (Polanco, 2026).

#### Referencias

- Hirano, T., Jinnai, R., & Toda, A. A. (2024). _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_ (Documento de trabajo arXiv:2211.13100v7 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Toda, A. A. (2025b). _Unbalanced Growth and Land Overvaluation_ (CIGS Working Paper Series No. 25-011E). The Canon Institute for Global Studies. (Aceptado para publicación en _Proceedings of the National Academy of Sciences_).
    
- Polanco, D. (2026). _Critical Replication of Shaikh’s Capacity Utilization Measure_ (Documento de trabajo / obra en progreso). Departamento de Economía, Universidad de Massachusetts Amherst.
    
- Toda, A. A. (2025). Land bubbles despite non-vanishing rents. _Economics Letters_, _257_(112708), 1-4. [https://doi.org/10.1016/j.ecolet.2025.112708](https://www.google.com/search?q=https://doi.org/10.1016/j.ecolet.2025.112708)

## Citas o pasajes útiles

- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Abstract; Introduction, pp. 1–4.
    
    Pasaje: El paper plantea una “desconexión aparente” entre la caída de la importancia productiva del suelo y su persistencia como reserva de valor. El Land Overvaluation Theorem establece que, cuando la elasticidad de sustitución entre tierra y factores no-tierra excede 1 y el progreso tecnológico es más rápido en los sectores no intensivos en tierra, la sobrevaloración del suelo emerge necesariamente.
    
    Uso posible en el memo: Este es el punto de entrada más claro para el IP: SHT no definen crecimiento desbalanceado como demanda efectiva insuficiente, sino como crecimiento desigual de productividades/factores que permite separar valor del suelo y función productiva del suelo.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Section 4, pp. 9–10.
    
    Pasaje: Los autores definen explícitamente crecimiento desbalanceado, siguiendo a Baumol, como crecimiento desigual de productividad entre factores de producción o sectores. El mecanismo requiere que las productividades de distintos factores crezcan a tasas distintas y que la elasticidad de sustitución entre tierra y otros factores sea relevante para el resultado.
    
    Uso posible en el memo: Sirve para fijar la definición operativa de SHT y evitar que el brief use “crecimiento desbalanceado” en sentido demasiado amplio o heterodoxo desde el comienzo.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Section 4 / Theorem 1, pp. 4 y 13–14.
    
    Pasaje: El paper muestra que, si la elasticidad de sustitución entre tierra y trabajo/factores no-tierra es mayor que 1, y la productividad laboral crece más rápido que la productividad de la tierra, el precio del suelo puede crecer junto con salarios/ingresos mientras las rentas del suelo crecen más lentamente. Esto produce una tendencia ascendente del price-rent ratio y sobrevaloración del suelo.
    
    Uso posible en el memo: Este es el puente técnico para explicar por qué el crecimiento desbalanceado es condición necesaria del teorema: el precio se mueve por la demanda de tierra como reserva de valor, mientras la renta productiva del suelo queda rezagada.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Section 5.1, pp. 15–16.
    
    Pasaje: En el ejemplo de transición desde economía malthusiana/agro-intensiva hacia economía moderna, el paper muestra que una burbuja o sobrevaloración emerge si la productividad del sector moderno crece suficientemente más rápido que la del sector tradicional intensivo en tierra. En el caso exponencial, la condición se reduce a que la productividad del sector moderno crezca más rápido que la del sector tradicional: `G2 > G1`. Los autores añaden que, en economías multisectoriales reales, no hay razón para esperar tasas iguales de progreso tecnológico; el crecimiento desbalanceado es una característica natural del desarrollo.
    
    Uso posible en el memo: Muy útil para una explicación intuitiva: el desarrollo económico reduce la centralidad productiva de la tierra, pero no elimina su función como reserva de valor. Esa diferencia produce la desconexión.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Implications of Theorem 1, pp. 4–5.
    
    Pasaje: Los autores distinguen su resultado de una lectura de burbujas como fenómenos puramente de corto plazo. El teorema muestra sobrevaloración del suelo en la tendencia de largo plazo durante el desarrollo económico. Con riesgo agregado, pueden existir fluctuaciones recurrentes alrededor de esa tendencia, con expansiones y contracciones del grado de sobrevaloración.
    
    Uso posible en el memo: Sirve para separar “sobrevaloración” de “boom-bust de corto plazo”. El Land Overvaluation Theorem no es simplemente una teoría de crisis inmobiliarias; es una teoría de desconexión de largo plazo entre renta productiva del suelo y precio del suelo.
    
- Fuente: PDF008 — Hirano, Jinnai & Toda, _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_.
    
    Página/sección: Abstract; Introduction, pp. 1–4.
    
    Pasaje: El paper presenta un modelo macro-financiero donde existe una retroalimentación positiva entre inversión de capital y precio del suelo. Cuando el leverage se relaja más allá de un valor crítico, ocurre una transición de fase: la economía pasa de crecimiento balanceado, donde los precios del suelo reflejan fundamentos, a crecimiento desbalanceado, donde los precios del suelo crecen más rápido que las rentas y aparecen burbujas.
    
    Uso posible en el memo: Complementa PDF001: en PDF001 el desbalance viene principalmente de productividad diferencial y sustitución; en PDF008 el desbalance puede emerger endógenamente por apalancamiento y acelerador financiero.
    
- Fuente: PDF008 — Hirano, Jinnai & Toda, _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_.
    
    Página/sección: Theorem 1 / discussion, pp. 3–4 y pp. posteriores del resultado.
    
    Pasaje: Si el leverage está bajo el umbral crítico, capital agregado, precio del suelo y renta del suelo crecen a la misma tasa en el largo plazo y el precio refleja fundamentos. Si el leverage supera el umbral, el precio del suelo crece más rápido que la renta, el price-rent ratio diverge y aparece una land bubble. El precio del suelo pasa a estar determinado por demanda sostenida, no solo por valor presente de rentas.
    
    Uso posible en el memo: Ayuda a explicar por qué “leverage” no es un detalle secundario. En esta rama de la literatura, el apalancamiento puede cambiar el régimen de crecimiento y activar sobrevaloración/burbuja.
    
- Fuente: PDF012 — Toda, _Land Bubbles Despite Non-Vanishing Rents_.
    
    Página/sección: Abstract; Introduction, pp. 1–2.
    
    Pasaje: Toda responde a la objeción empírica según la cual las burbujas inmobiliarias no existirían porque el rent-yield observado parece estacionario. El punto central es que puede existir una burbuja del suelo incluso si el housing rent yield observado es constante, porque los datos agregados mezclan renta de la estructura habitacional y renta pura del suelo. La clave es separar la renta del componente construido de la renta del suelo.
    
    Uso posible en el memo: Esta es una advertencia metodológica crucial. No se puede rechazar la hipótesis de land bubble o land overvaluation usando directamente rent-yields de vivienda si esos datos mezclan estructura y suelo.
    
- Fuente: `CriticalReplication_CU_Shaikh_DiegoPolanco.pdf`.
    
    Página/sección: Abstract; Introduction, pp. 1–2.
    
    Pasaje: El capítulo reinterpreta el coeficiente de la relación output–capital como una elasticidad de transformación `θ` que vincula acumulación de capital con formación de capacidad productiva. La contribución desplaza el foco desde el residuo de utilización hacia el parámetro estructural que gobierna cómo el capital acumulado se transforma en capacidad.
    
    Uso posible en el memo: Sirve para explicar que tu contribución no es una teoría de precios del suelo, sino una teoría de la relación entre capital acumulado y capacidad productiva.
    
- Fuente: `Chapter1_CriticalReplication.pdf`.
    
    Página/sección: Section 3.2.2, “The Unbalanced Growth Closure”, pp. 16–17.
    
    Pasaje: El capítulo define la elasticidad de transformación como `θ ≡ ∂ ln Y^p / ∂ ln K`. La clausura de crecimiento desbalanceado es `ŷ^p = θ · k̂`. El crecimiento balanceado, `θ = 1`, aparece como caso especial de filo de navaja; el caso general es `θ ≠ 1`, y el signo de `(θ − 1)` determina si domina la sobreacumulación relativa al aparato de capacidad productiva o la formación excesiva de capacidad cuya contradicción emerge si la realización falla.
    
    Uso posible en el memo: Este es el punto textual más fuerte para contrastar SHT y la contribución propia. En SHT, el desbalance es sectorial/factorial; en tu capítulo, es una elasticidad de transformación entre capital y capacidad productiva.
    

## Evaluación crítica

### Lo que aclara

- La revisión confirma que SHT usan “crecimiento desbalanceado” en un sentido técnico específico: crecimiento desigual de productividades entre factores o sectores. No es, en primer término, una teoría de demanda efectiva ni de utilización.
- Queda corroborado que en PDF001 el crecimiento desbalanceado es condición central del Land Overvaluation Theorem. La clave es la combinación entre productividad más rápida en factores/sectores no intensivos en tierra y elasticidad de sustitución mayor que uno.
- También queda claro que la sobrevaloración no es simplemente una burbuja transitoria. En PDF001, la sobrevaloración puede emerger como tendencia de largo plazo durante el desarrollo económico, mientras las fluctuaciones de corto plazo ocurren alrededor de esa tendencia.
- PDF008 aclara el papel del leverage: el crecimiento desbalanceado no solo puede aparecer por productividad diferencial, sino también como resultado endógeno de una relajación financiera que activa un feedback entre capital investment y land prices.
- PDF012 disciplina la dimensión empírica: un rent-yield observado estable no basta para descartar una burbuja del suelo, porque el alquiler de vivienda observado mezcla renta de estructura y renta pura del suelo.
- La comparación con tu capítulo queda bien fundada si se formula de manera estricta: tu contribución no explica precios del suelo, sino la transformación entre acumulación de capital y formación de capacidad productiva bajo `θ ≠ 1`.
- La conexión útil para el brief es clara: SHT muestran una desproporción entre valor del suelo y renta/fundamento productivo; tu marco permite traducir esa preocupación hacia una pregunta más amplia sobre la desproporción entre valorización patrimonial, acumulación y capacidades productivas.

### Lo que queda ambiguo

- La respuesta bruta usa “Stiglitz-Hirano-Toda” como bloque único. Para esta nota, conviene ser más preciso: PDF001 es Hirano–Toda; PDF008 es Hirano–Jinnai–Toda; PDF012 es Toda. Stiglitz entra indirectamente por la serie de literatura, pero no en estos tres textos principales.
- La respuesta bruta afirma que SHT trabajan “desde el lado de la oferta” de modo algo demasiado cerrado. Es correcto para PDF001, pero PDF008 incorpora explícitamente leverage, financial accelerator y transición de fase macro-financiera. Por tanto, mejor decir “en PDF001 el desbalance es productivo-sectorial; en PDF008 se endogeneiza financieramente”.
- La frase “reserva pura de valor que succiona los ahorros agregados” es demasiado fuerte para esta nota. PDF001 muestra tierra como store of value y sobrevaloración, pero el mecanismo de drenaje de ahorro hacia activos no producidos está mejor desarrollado en la nota 01 sobre crédito/crowding-out. Aquí conviene decir “la tierra mantiene su función como reserva de valor aunque decline su rol productivo”.
- La respuesta bruta dice que el precio del suelo “se desvincula de sus fundamentos productivos reales”. Es aceptable como intuición, pero debe formularse con precisión: sobrevaloración significa que el precio excede el valor fundamental definido como valor presente de rentas del suelo.
- La respuesta bruta introduce “renta capturada por propietarios financiarizados”, “patología distributiva” y “balances financieros ilíquidos”. Esas fórmulas son potencialmente útiles para una crítica posterior, pero exceden el brief si aparecen en la sección estricta de crecimiento desbalanceado.
- La comparación con tu contribución debe evitar decir que tu marco “absorbe” la literatura SHT o es una “matriz superior”. Mejor decir que “traduce” o “reubica” el problema en otra arquitectura teórica.
- La afirmación “incapacidad del capital para expandir la base material reproducible de producción” puede ser excesiva. Tu capítulo permite hablar de transformación no proporcional entre capital y capacidad; no necesariamente de incapacidad absoluta.

### Riesgo de sobreinterpretación

- Riesgo 1: decir que ambos conceptos de crecimiento desbalanceado son equivalentes. No lo son. En SHT, el desbalance se define por crecimiento desigual de productividades sectoriales/factoriales; en tu capítulo, por elasticidad de transformación entre capital y capacidad productiva.
- Riesgo 2: decir que SHT ofrecen una teoría de demanda efectiva. No. La demanda efectiva pertenece a tu traducción crítica, no al mecanismo central de PDF001/PDF008.
- Riesgo 3: usar “burbuja”, “sobrevaloración” y “especulación” como sinónimos. PDF001 trabaja con overvaluation respecto del valor fundamental; PDF008 trabaja con asset/land bubbles; PDF012 advierte sobre medición de rent-yields. Hay que mantener las distinciones.
- Riesgo 4: exagerar el lugar del leverage en PDF001. El leverage es central para PDF008, no para el Land Overvaluation Theorem de PDF001. En PDF001, el núcleo es productividad diferencial + elasticidad de sustitución.
- Riesgo 5: sobredimensionar la crítica heterodoxa dentro del memo. El IP pidió aclarar la literatura y relacionarla con tu contribución. La crítica debe ser precisa, no totalizante.
- Riesgo 6: presentar el capítulo como si ya resolviera empíricamente la relación entre suelo, crédito y capacidad productiva. No: el capítulo provee la arquitectura conceptual de `θ` y la desproporcionalidad capital-capacidad, no una estimación de land overvaluation.
- Riesgo 7: usar “Polanco 2026” como si fuera una fuente externa publicada. En el memo interno puede usarse como “contribución propia / capítulo de tesis”, no como paper publicado.

### Qué debe verificarse contra la fuente original

- Verificación completada: PDF001 define land overvaluation como precio del suelo por encima de fundamentos definidos por el valor presente de rentas.
- Verificación completada: PDF001 identifica la combinación de crecimiento desbalanceado y elasticidad de sustitución mayor que uno como condición central para que la sobrevaloración emerja necesariamente.
- Verificación completada: PDF001 define crecimiento desbalanceado, siguiendo a Baumol, como crecimiento desigual de productividad entre factores o sectores.
- Verificación completada: PDF001 muestra que, en el ejemplo de dos sectores, la condición de sobrevaloración se reduce al caso en que la productividad del sector moderno crece más rápido que la del sector tradicional, `G2 > G1`.
- Verificación completada: PDF008 establece que una relajación del leverage más allá de un umbral crítico puede producir una transición de fase desde crecimiento balanceado con precios fundamentales hacia crecimiento desbalanceado con precios del suelo creciendo más rápido que rentas y con land bubbles.
- Verificación completada: PDF012 afirma que una burbuja del suelo puede existir aunque el housing rent-yield observado sea constante, porque se debe distinguir la renta de la estructura habitacional de la renta pura del suelo.
- Verificación completada: el capítulo propio define `θ` como elasticidad de transformación de la capacidad productiva respecto del capital y presenta `θ = 1` como caso balanceado de filo de navaja, con `θ ≠ 1` como caso general.
- Corrección necesaria: no usar “Stiglitz-Hirano-Toda” para todos los textos de esta nota. Usar “Hirano–Toda”, “Hirano–Jinnai–Toda” y “Toda” cuando corresponda; reservar SHT como etiqueta amplia del programa de investigación.
- Corrección necesaria: reemplazar “matriz analítica superior” por “traducción crítica desde otra arquitectura teórica”.
- Corrección necesaria: reemplazar “patología distributiva” por una formulación más sobria: “mecanismo de valorización patrimonial que puede separarse de la formación de capacidad productiva”.
- Corrección necesaria: reemplazar “incapacidad del capital para expandir la base material reproducible” por “relación no proporcional entre acumulación de capital y formación de capacidad productiva”.

## Tabla exportable SHT / contribución propia

| Dimensión                | SHT                                                                                                                                                          | Polanco (2026)                                                                                                                         | Conexión útil para el brief                                                                                                                              | Advertencia                                                                                      |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| Objeto                   | Precio del suelo, rentas del suelo y fundamentos definidos como valor presente de rentas.                                                                    | Relación entre acumulación de capital, capacidad productiva y utilización.                                                             | Ambos enfoques permiten estudiar desacoples entre valorización y base productiva.                                                                        | No convertir el capítulo en una teoría de precios del suelo.                                     |
| Desbalance central       | Crecimiento desigual de productividad entre factores o sectores; en PDF001, sectores no intensivos en tierra crecen más rápido que los intensivos en tierra. | Desproporcionalidad entre acumulación de capital y formación de capacidad productiva, con mediación de demanda efectiva y utilización. | El desbalance SHT puede traducirse como caso específico de una preocupación más amplia por desproporciones macroeconómicas.                              | No afirmar identidad conceptual entre ambos usos de “crecimiento desbalanceado”.                 |
| Variable crítica         | Elasticidad de sustitución entre tierra y factores no-tierra, productividad relativa, price-rent ratio; en PDF008, leverage.                                 | Elasticidad de transformación `θ = ∂ ln Y^p / ∂ ln K`.                                                                                 | SHT mira la divergencia entre precio y renta; el capítulo mira la transformación entre capital y capacidad.                                              | No reemplazar `σ` por `θ`; son objetos distintos.                                                |
| Mecanismo macro          | La tierra pierde peso como factor productivo, pero conserva valor como store of value; si precios crecen más rápido que rentas, emerge overvaluation.        | La capacidad productiva no se deriva mecánicamente del capital acumulado; `θ ≠ 1` rompe proporcionalidad balanceada.                   | Permite explicar por qué una economía puede expandir riqueza patrimonial sin equivalente expansión de capacidad productiva.                              | Evitar lenguaje de “succión de liquidez” salvo en la sección de crédito/crowding-out.            |
| Implicancia para el memo | El Land Overvaluation Theorem depende de crecimiento desbalanceado y elasticidad de sustitución mayor que uno.                                               | La contribución propia ayuda a reubicar la pregunta en términos de demanda efectiva, utilización y formación de capacidades.           | El vínculo con el IP debe ser: SHT explican sobrevaloración del suelo; la contribución propia permite leer sus consecuencias para acumulación/capacidad. | Mantener la crítica acotada y no abrir una revisión completa de economía política del excedente. |

## Párrafo exportable para el memo

En Hirano–Toda, el crecimiento desbalanceado designa el crecimiento desigual de la productividad entre factores o sectores. Su relevancia para el Land Overvaluation Theorem es precisa: si la productividad crece más rápido en sectores o factores no intensivos en tierra y la elasticidad de sustitución entre tierra y factores no-tierra supera la unidad, el precio del suelo puede crecer más rápido que sus rentas fundamentales. En ese caso, la tierra pierde importancia relativa como factor productivo, pero conserva —o refuerza— su papel como reserva de valor, generando sobrevaloración de largo plazo. Hirano–Jinnai–Toda agregan una vía macro-financiera: cuando el leverage supera un umbral crítico, el precio del suelo puede entrar en un régimen de crecimiento desbalanceado donde aumenta más rápido que las rentas. Esta noción no es idéntica a la contribución propia. En el capítulo de tesis, crecimiento desbalanceado refiere a la relación no proporcional entre acumulación de capital y formación de capacidad productiva, mediada por la elasticidad de transformación `θ`. La conexión útil es que SHT explican la separación entre valor patrimonial del suelo y rentas productivas, mientras que la contribución propia permite traducir esa separación hacia una pregunta más amplia sobre capacidad productiva, utilización y demanda efectiva.
### Estado

- [x] Input 3A enviado
- [x] Output 3A capturado
- [x] Input 3B enviado
- [x] Output 3B capturado
- [x] Tabla exportable redactada
- [x] Citas verificadas
- [x] Párrafo exportable redactado
- [ ] Integrado en `05_OUTPUT_Memo_Breve_IP`
