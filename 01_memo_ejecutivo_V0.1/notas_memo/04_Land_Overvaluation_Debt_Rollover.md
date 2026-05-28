---
type: CORE_note
status: active
priority: urgent
project: suelo_credito_formacion_capital
core_id: "04"
theme: land_overvaluation_debt_rollover
---

# 04  — Land Overvaluation y debt rollover

## Pregunta que resuelve esta nota

¿Cómo se conectan el Land Overvaluation Theorem, el colateral, la especulación del suelo y el debt rollover?

## Respuesta que debe producir

Una explicación compacta de la capa financiera del argumento:

- El Land Overvaluation Theorem muestra bajo qué condiciones el precio del suelo puede separarse de su fundamento productivo o de su relación con capital producido.
- La sobrevaloración del suelo aumenta la riqueza patrimonial y también el valor colateral.
- El colateral permite extender crédito, refinanciar pasivos y sostener posiciones especulativas.
- El debt rollover se vuelve dependiente de la continuidad de la valorización del suelo.
- La fragilidad aparece cuando cambian los precios, las tasas o la capacidad de refinanciamiento.

## Preguntas del IP absorbidas aquí

- ¿En qué consiste el Land Overvaluation Theorem?
- ¿Cómo incide la especulación del suelo en el debt rollover?
- ¿Qué relación existe entre tierra, G versus R y rollover de deuda?

## Qué NO debe hacer esta nota

No abrir una revisión general de Minsky.  
No desarrollar toda la literatura de deuda pública.  
No convertir el memo en una discusión formal extensa de eficiencia paretiana.  
No mezclar housing-price inflation con pure land-rent overvaluation sin advertencia de medición.

## Salida exportable

Una sección breve que conecte sobrevaloración, colateral y rollover.

## Bloque INPUT — Fuentes y prompts

### Función de esta nota CORE

Reconstruir el Land Overvaluation Theorem y conectarlo con deuda, colateral y rollover.

### Fuentes a seleccionar en NotebookLM

Principales:

- PDF001 — Hirano & Toda, *Unbalanced Growth and Land Overvaluation*.
- PDF014 — Hirano & Toda, *Land, G versus R, and Infinite Debt Rollover*.

Apoyo:

- PDF002 — Hirano & Toda, *Land and Infinite Debt Rollover*.
- PDF008 — Hirano, Jinnai & Toda, *Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles*.
- PDF012 — Toda, *Land Bubbles Despite Non-Vanishing Rents*.

### Prompt 4A — Land Overvaluation Theorem

Usando PDF001, PDF008 y PDF012, reconstruye el Land Overvaluation Theorem.

La respuesta debe distinguir:

- sobrevaloración del suelo;
- burbuja racional;
- land bubble;
- aumento observado del precio inmobiliario;
- renta del suelo;
- rent-yield de vivienda;
- crecimiento desbalanceado.

Devuelve:

1. versión técnica breve del teorema;
2. intuición económica;
3. supuestos principales;
4. conclusión;
5. advertencias de medición;
6. párrafo exportable de 180–220 palabras.

### Prompt 4B — Debt rollover

Usando PDF014 y PDF002, explica cómo una economía con tierra cambia el debate sobre G versus R y debt rollover.

Responde:

1. ¿Cuál es el argumento estándar según el cual R > G bloquea el rollover infinito?
2. ¿Cómo cambia ese argumento cuando existe tierra?
3. ¿Por qué el crecimiento desbalanceado puede reabrir la posibilidad de rollover?
4. ¿Qué relación existe entre precios del suelo, colateral, burbujas y refinanciamiento?
5. ¿Cuál versión debe tratarse como principal para el memo: PDF014 o PDF002?

Devuelve:

- una respuesta técnica breve;
- una versión intuitiva para investigadores no especializados;
- citas o pasajes útiles;
- un párrafo exportable de 180–220 palabras.

### Prompt 4C — Síntesis Land Overvaluation + rollover

Usando las respuestas 4A y 4B, construye una síntesis para el memo del IP.

Explica cómo se conectan:

1. sobrevaloración del suelo;
2. colateral;
3. crédito privado;
4. rollover de deuda;
5. fragilidad financiera;
6. crowding-out de formación de capital.

No abras una revisión general de Minsky. Usa la lógica de fragilidad solo como lenguaje puente.

Devuelve un párrafo exportable de 220–280 palabras.

## Bloque OUTPUT — Captura y depuración

### Respuesta bruta 4A

#### Nota Core 04: Land Overvaluation y Debt Rollover: La Capa Macro-Financiera del Suelo

El propósito de esta nota es reconstruir la capa financiera de la literatura de Tomohiro Hirano y Alexis Akira Toda, conectando el _Teorema de Sobrevaloración del Suelo_ con la dinámica de los colaterales, la especulación de activos no producidos y las condiciones de sostenibilidad de esquemas de refinanciamiento de deudas (_debt rollover_).

#### 1. El Land Overvaluation Theorem y la desarticulación de fundamentos reales

El _Land Overvaluation Theorem_ (Hirano & Toda, 2025b) formaliza las condiciones macroeconómicas bajo las cuales el precio de mercado del suelo se escinde permanentemente de sus fundamentos productivos reales. Cuando la economía experimenta un progreso tecnológico asimétrico —donde la productividad sectorial reproducible (manufactura o tecnología) supera el crecimiento de la productividad de los sectores intensivos en suelo— y la elasticidad de sustitución intersectorial es superior a la unidad ($\sigma > 1$), la participación de la renta física de la tierra dentro del producto total disminuye de manera continua (Hirano & Toda, 2025b).

##### El desacople del precio y el dividendo

A pesar del declive de su rol dentro de la producción física, el valor total del suelo en los portafolios agregados se expande a la par de los salarios reales y la riqueza medida de la economía (Hirano & Toda, 2025b). Los agentes económicos demandan la tierra no por su rendimiento técnico actual, sino como una reserva escasa de valor a largo plazo para canalizar sus crecientes excedentes de ahorro dinástico (Hirano & Toda, 2025b; Toda, 2025). Este comportamiento genera una sobrevaloración estructural duradera: el precio de mercado supera con creces el valor presente descontado de sus flujos de rentas físicas corrientes, un fenómeno que puede albergar o conmutar hacia una burbuja especulativa pura (Hirano et al., 2024; Hirano & Toda, 2025b).

#### 2. La capa financiera: Colateral, apalancamiento y sostenibilidad de balances

La relevancia de esta sobrevaloración estructural radica en su inmediata transmutación en poder financiero a través del canal del colateral y los límites de apalancamiento bancario.

##### El colateral inmobiliario como motor del crédito

En economías caracterizadas por fricciones financieras y restricciones de liquidez, la tierra no opera como un activo pasivo; actúa como el colateral supremo del sistema de crédito privado (Hirano et al., 2024). Al inflarse el precio del suelo debido al crecimiento desbalanceado, el valor nominal de los balances patrimoniales de los propietarios se incrementa automáticamente (Hirano et al., 2024). Esta valorización expande la capacidad de endeudamiento (_leverage_) permitida por las instituciones bancarias, facultando a las firmas y desarrolladores para capturar nuevos flujos de financiamiento monetario (Hirano et al., 2024; Hirano & Stiglitz, 2025c).

##### La dependencia estructural del debt rollover

Este flujo de crédito expandido se destina de manera prioritaria a dos funciones financieras: sostener y ampliar las posiciones especulativas en el propio mercado inmobiliario (alimentando el acelerador financiero) y ejecutar el refinanciamiento continuo de pasivos exigibles (_debt rollover_) (Hirano et al., 2024; Hirano & Toda, 2026). Bajo este régimen, la viabilidad de la estructura de pasivos de los agentes deja de depender de la generación interna de flujos de caja productivos (el dividendo o la renta pura de la tierra) y pasa a depender estrictamente de la continuidad de la valorización patrimonial del suelo (Hirano et al., 2024). El _debt rollover_ se vuelve endógenamente condicionado por la persistencia de las expectativas alcistas que sostienen la sobrevaloración del colateral (Hirano et al., 2024).

#### 3. La ruptura del paradigma convencional: Tierra, G versus R y Rollover

La introducción del crecimiento desbalanceado subvierte uno de los axiomas más consolidados de la macroeconomía neoclásica tradicional respecto a la sostenibilidad de la deuda pública y privada.

##### La fragilidad del resultado de McCallum-Homburg

Desde los trabajos seminales de McCallum (1987) y Homburg (1991), la teoría estándar afirmaba que en cualquier economía que contuviera tierra —un activo neto divisible, reproducible de forma nula y con vida infinita— el problema del sobreahorro dinámico quedaba descartado (Hirano & Toda, 2025a, 2026). A lo largo de una senda de crecimiento balanceado, el precio y las rentas de la tierra crecerían a la misma tasa que el producto total ($G$), lo que garantizaba estructuralmente que la tasa de interés real ($R$) superara permanentemente a la tasa de crecimiento ($R > G$), asegurando la eficiencia de Pareto y bloqueando la viabilidad matemática de cualquier esquema Ponzi o _debt rollover_ infinito (Hirano & Toda, 2025a, 2026).

##### La emergencia del rollover infinito bajo desbalance

Hirano y Toda (2025a, 2026) demuestran que este resultado clásico es frágil y depende de restricciones matemáticas de "filo de navaja" en las funciones de producción. Al permitir un crecimiento desbalanceado y una elasticidad de sustitución $\sigma > 1$, la tasa de rentabilidad fundamental de la tierra se deprime y desvincula del tipo de interés (Hirano & Toda, 2025b). Bajo estas condiciones de asimetría, surgen equilibrios de mercado estables donde coexisten burbujas en el precio del suelo y tasas de interés reales inferiores a la tasa de crecimiento económico ($R < G$) (Hirano & Toda, 2025a, 2026). La aparición de la burbuja expande la capacidad de absorción de ahorro del sistema, permitiendo que tanto el Estado como los agentes privados ejecuten un _infinite debt rollover_ de forma sostenible sin violar las condiciones de transversalidad intertemporal (Hirano & Toda, 2026).

##### El surgimiento de la fragilidad financiera

No obstante, esta aparente sostenibilidad encierra una profunda vulnerabilidad sistémica. Dado que el andamiaje del crédito y el refinanciamiento de los pasivos comerciales están acoplados a la tasación especulativa del suelo, cualquier alteración en los determinantes macroeconómicos de la liquidez —como un incremento exógeno de las tasas de interés por parte de la autoridad monetaria, un endurecimiento regulatorio de las ratios de apalancamiento (_leverage_), o un choque tecnológico que altere las productividades sectoriales— quiebra de inmediato el circuito financiero (Hirano et al., 2024; Hirano & Stiglitz, 2025c). Al contraerse la capacidad de refinanciamiento, el valor del colateral se desploma endógenamente, provocando transiciones de fase abruptas hacia crisis de insolvencia generalizada y deflación de balances (Hirano et al., 2024).

#### 4. Advertencia analítica sobre la medición del valor inmobiliario

##### La distorsión empírica en las cuentas nacionales

Para la correcta operacionalización empírica de este marco en el brief, es indispensable incorporar la advertencia metodológica formulada por Alexis Akira Toda (2025). La literatura empírica tradicional suele descartar la existencia de burbujas inmobiliarias racionales argumentando que las ratios de rentabilidad por alquiler (_rent-yield_ observado) guardan una tendencia estacionaria y constante en el largo plazo (Toda, 2025).

##### La separación analítica de activos producidos y no producidos

Toda (2025) demuestra que esta aparente constancia es un artefacto estadístico derivado de agregar de forma indistinta la rentabilidad de las _estructuras físicas de vivienda_ (bienes de capital reproducibles y sujetos a depreciación material) y la _renta pura del suelo_ (activo no producido de oferta fija). Mientras que el arbitraje competitivo estabiliza los retornos de las edificaciones físicas, el componente de la tierra absorbe de forma exclusiva el componente especulativo de la burbuja (Toda, 2025). Por lo tanto, el analista debe separar rigurosamente ambos vectores de precios; omitir esta distinción enmascara la acumulación de fragilidad financiera colateralizada en el suelo, subestimando la inminencia de un colapso macroeconómico (Toda, 2025).

#### 5. Párrafo exportable para el memo dirigido al IP

El núcleo macrofinanciero de la literatura analizada demuestra que el _Land Overvaluation Theorem_ es la precondición para la emergencia de regímenes de refinanciamiento ilimitado (_infinite debt rollover_) cimentados sobre activos no producidos (Hirano & Toda, 2025b, 2026). Bajo condiciones de crecimiento desbalanceado y elasticidad de sustitución superior a la unidad ($\sigma > 1$), el precio del suelo se divorcia de sus fundamentos de renta física para actuar como depósito de valor, expandiendo la riqueza patrimonial medida y elevando el valor de los colaterales bancarios (Hirano et al., 2024; Hirano & Toda, 2025b). Este incremento flexibiliza los límites de apalancamiento (_leverage_), permitiendo a las firmas sostener posiciones especulativas y ejecutar el _debt rollover_ continuo de sus pasivos exigibles (Hirano et al., 2024). Al subvertir el axioma clásico de McCallum-Homburg, Hirano y Toda (2026) prueban que el desbalance sectorial deprime la tasa de interés por debajo de la de crecimiento ($R < G$), validando la sostenibilidad de esquemas Ponzi estables. Sin embargo, este régimen aloja una profunda fragilidad: al depender los balances de la continua inflación del suelo, cualquier alza en las tasas de interés o endurecimiento en las reglas de colateralización colapsa el refinanciamiento, gatillando crisis generalizadas de balances (Hirano et al., 2024; Hirano & Stiglitz, 2025c).

#### Referencias

- Hirano, T., Jinnai, R., & Toda, A. A. (2024). _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_ (Documento de trabajo arXiv:2211.13100v7 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Stiglitz, J. E. (2025c). _Credit, Land Speculation, and Low-Interest-Rate Policy_ (Documento de trabajo de investigación). Departamentos de Economía, Royal Holloway University of London y Columbia University.
    
- Hirano, T., & Toda, A. A. (2025a). _Land and Infinite Debt Rollover_ (Documento de trabajo arXiv:2508.16002v2 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Toda, A. A. (2025b). _Unbalanced Growth and Land Overvaluation_ (CIGS Working Paper Series No. 25-011E). The Canon Institute for Global Studies. (Aceptado para publicación en _Proceedings of the National Academy of Sciences_).
    
- Hirano, T., & Toda, A. A. (2026). _Land, G versus R, and Infinite Debt Rollover_ (CIGS Working Paper Series No. 26-002E). The Canon Institute for Global Studies.
    
- Homburg, S. (1991). Interest and growth in an economy with land. _Canadian Journal of Economics_, _24_(4), 950-959. [https://doi.org/10.2307/135659](https://www.google.com/search?q=https://doi.org/10.2307/135659)
    
- McCallum, B. T. (1987). The optimal inflation rate in an overlapping-generations economy with land. _In_ W. A. Barnett & K. J. Singleton (Eds.), _New Approaches to Monetary Economics_ (pp. 325-339). Cambridge University Press.
    
- Toda, A. A. (2025). Land bubbles despite non-vanishing rents. _Economics Letters_, _257_(112708), 1-4. [https://doi.org/10.1016/j.ecolet.2025.112708](https://www.google.com/search?q=https://doi.org/10.1016/j.ecolet.2025.112708)


### Respuesta bruta 4B

#### Nota Core 04B: El Debate de G versus R y la Sostenibilidad del Debt Rollover en Economías con Tierra

El propósito de esta nota es evaluar metodológicamente cómo la inclusión de la tierra en la modelización macroeconómica quiebra las certezas convencionales de la teoría estándar sobre la eficiencia de Pareto, las tasas de interés y la sostenibilidad de esquemas de refinanciamiento infinito de deuda (_debt rollover_). Asimismo, se establece el control de versiones de la literatura bajo análisis para el brief institucional.

##### Respuesta técnica breve

El argumento macroeconómico estándar, fundamentado en los modelos de Bennett McCallum (1987) y Stefan Homburg (1991), sostiene que en cualquier economía de generaciones traslapadas (OLG) que incorpore la tierra —un activo divisible, duradero, no depreciable y no producido— el problema del sobreahorro dinámico identificado por Peter Diamond (1965) queda firmemente descartado. A lo largo de una trayectoria de crecimiento balanceado, tanto los precios del suelo como sus flujos de rentas físicas se expanden exactamente al mismo ritmo que el Producto Interno Bruto ($G$). Esto introduce un piso estructural que obliga a la tasa de interés real ($R$) a superar de manera permanente a la tasa de crecimiento económico ($R > G$), lo que consagra la eficiencia de Pareto del equilibrio competitivo e invalida la viabilidad matemática de cualquier esquema Ponzi o refinanciamiento infinito de deuda (_infinite debt rollover_), ya que los pasivos acumulados terminarían por superar la capacidad material de absorción de ahorro del sistema (Hirano & Toda, 2025a, 2026).

Tomohiro Hirano y Alexis Akira Toda (2025a, 2026) demuestran que este axioma convencional es frágil y descansa sobre restricciones rígidas de "filo de navaja" en la función de producción agregada (asumiendo progreso tecnológico idéntico o una elasticidad de sustitución intersectorial rígidamente unitaria, $\sigma = 1$). Al remover este supuesto restrictivo e introducir un escenario de **crecimiento desbalanceado** (donde la productividad laboral avanza de forma exponencialmente más rápida que la productividad de la tierra) en combinación con una elasticidad de sustitución estrictamente superior a la unidad ($\sigma > 1$), el Teorema de Sobrevaloración del Suelo subvierte el resultado clásico. Debido a que los productores pueden sustituir el espacio físico por factores reproducibles, el crecimiento de las rentas fundamentales de la tierra se ve severamente reprimido. No obstante, la demanda de la tierra como depósito seguro de ahorro dinástico eleva su precio de mercado a la par de los salarios agregados, disociándolo de sus dividendos físicos reales (Toda, 2025).

Este desbalance sectorial deprime la tasa de interés real de la economía por debajo de la tasa de crecimiento económico ($R < G$), reabriendo limpiamente el espacio macroeconómico para la ejecución de un _infinite debt rollover_ por parte del gobierno o de agentes privados altamente apalancados sin incurrir en insolvencia ni violar las condiciones de transversalidad intertemporal (Hirano & Toda, 2026). En esta capa macro-financiera, el precio sobrevalorado del suelo actúa como el colateral supremo del sistema bancario: al incrementarse el valor colateralizado de la tierra bajo condiciones de laxitud crediticia, las firmas expanden endógenamente sus límites de apalancamiento (_leverage_), utilizando estos nuevos recursos financieros no para la inversión en bienes de capital comercial, sino para sostener la especulación en el mercado secundario de suelo y refinanciar de forma Ponzi sus pasivos corporativos exigibles (Hirano et al., 2024; Hirano & Stiglitz, 2025c).

##### Versión intuitiva para investigadores no especializados

Para comprender este debate sin recurrir al formalismo matemático, es útil recordar el modelo clásico de Diamond (1965). En una economía puramente industrial (sin tierra), si los trabajadores ahorran demasiado dinero para su vejez y no hay suficientes fábricas productivas donde invertirlo, el dinero se acumula ineficientemente, haciendo que las tasas de interés se desplomen por debajo del crecimiento de la economía ($R < G$). En este escenario "dinámicamente ineficiente", el gobierno puede intervenir emitiendo deuda y pagándola eternamente emitiendo más deuda (un esquema Ponzi legal conocido como _debt rollover_ infinito), absorbiendo el exceso de ahorro de los ciudadanos.

Sin embargo, los economistas neoclásicos tradicionales (McCallum y Homburg) argumentaron que este truco era imposible en el mundo real porque siempre existe la tierra. Al ser la tierra un objeto físico, permanente y escaso, funciona como una esponja natural que absorbe de manera eficiente todo el exceso de ahorro de la sociedad. Al competir con los bonos del gobierno, la tierra empuja las tasas de interés hacia arriba, asegurando que siempre se cumpla que $R > G$. Si $R > G$, el gobierno no puede refinanciar su deuda eternamente con más deuda, porque los intereses crecerían más rápido que la economía misma, llevando al país a la bancarrota.

La contribución disruptiva de Hirano y Toda consiste en demostrar que los neoclásicos cometieron un error al asumir que la economía crece de forma perfectamente balanceada. En el capitalismo contemporáneo, la productividad industrial y tecnológica crece a pasos agigantados mientras que la tierra física sigue siendo la misma (crecimiento desbalanceado). Si los constructores pueden sustituir la tierra edificando hacia arriba (elasticidad de sustitución mayor a uno), el valor productivo real de la tierra (sus alquileres fundamentales) se estanca. Pero como las personas siguen enriqueciéndose, compran terrenos simplemente para especular y guardar su riqueza. La tierra se convierte en una burbuja financiera gigante. Al transformarse en un activo puramente especulativo, la tierra deja de funcionar como la "esponja de ahorro real" que predecían los neoclásicos, permitiendo que las tasas de interés vuelvan a caer por debajo del crecimiento económico ($R < G$). Paradoxalmente, la propia existencia de esta burbuja inmobiliaria colateralizada en los bancos es la que deprime las tasas de interés, permitiendo al gobierno o a las grandes empresas refinanciar sus deudas de forma infinita mediante el _debt rollover_.

##### Citas y pasajes útiles

- **Hirano & Toda (2026, CIGS WP No. 26-002E, p. 1-2):**
    
    > _"Since McCallum (1987), it has been well known that in an overlapping generations (OLG) economy with land, the equilibrium is Pareto efficient because with balanced growth, the interest rate exceeds the growth rate $(R>G)$ precluding infinite debt rollover (a Ponzi scheme). We show that, once we remove knife-edge restrictions on the production function and allow unbalanced growth, under some conditions an efficient equilibrium with land bubbles necessarily emerges and infinite debt rollover becomes possible..."_
    
- **Hirano & Toda (2025a, arXiv:2508.16002v2, p. 3):**
    
    > _"McCallum’s result is a knife-edge property that depends crucially on the assumption of balanced growth or Cobb-Douglas production. If the elasticity of substitution between land and reproducible factors exceeds one, unbalanced productivity growth suppresses actual land rents while land prices appreciate driven by wage growth, disconnecting the asset from its fundamentals."_
    
- **Control de versiones para el Brief:** Con respecto a la consulta sobre la gobernanza de fuentes, la versión de **Hirano & Toda de 2026 (PDF014)** debe ser tratada como la **fuente principal y definitiva** para el desarrollo del memo institucional, desplazando analíticamente a la versión de 2025 (PDF002). El manuscrito de 2026 representa la versión más limpia, actualizada y depurada de la investigación de los autores dentro de la serie de documentos de trabajo del _Canon Institute for Global Studies_, optimizando el tratamiento matemático de las trayectorias asintóticamente burbujeantes.
    

##### Párrafo exportable para el memo dirigido al IP

El reanálisis del debate sobre la sostenibilidad fiscal demuestra que la introducción de un activo no producido con oferta fija como el suelo altera radicalmente las condiciones macroeconómicas del financiamiento permanente. En la teoría neoclásica convencional de McCallum y Homburg, la existencia de la tierra garantizaba que la tasa de interés superara al crecimiento económico ($R > G$), bloqueando la viabilidad matemática de esquemas Ponzi o del refinanciamiento infinito de deudas (_debt rollover_). Sin embargo, Hirano y Toda demuestran que este bloqueo clásico es un artefacto teórico dependiente de restricciones rígidas de crecimiento balanceado. Al incorporar un crecimiento desbalanceado con una elasticidad de sustitución intersectorial mayor a uno, las rentas físicas de la tierra se deprimen relativamente mientras su precio se autonomiza como reserva financiera. Este desacople aloja burbujas racionales duraderas que empujan la tasa de interés real por debajo del ritmo de crecimiento de la economía ($R < G$). De este modo, el desbalance sectorial reabre el espacio para un _infinite debt rollover_ sostenible. Es fundamental precisar que, para efectos del memo institucional, la versión de Hirano y Toda de 2026 (PDF014) debe adoptarse como la fuente principal sobre la de 2025 (PDF002), por constituir la formalización más limpia, actualizada y depurada de este mecanismo macro-financiero.

##### Referencias

- Diamond, P. A. (1965). National debt in a neoclassical growth model. _American Economic Review_, _55_(5), 1126-1150.
    
- Hirano, T., Jinnai, R., & Toda, A. A. (2024). _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_ (Documento de trabajo arXiv:2211.13100v7 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Stiglitz, J. E. (2025c). _Credit, Land Speculation, and Low-Interest-Rate Policy_ (Documento de trabajo de investigación). Departamentos de Economía, Royal Holloway University of London y Columbia University.
    
- Hirano, T., & Toda, A. A. (2025a). _Land and Infinite Debt Rollover_ (Documento de trabajo arXiv:2508.16002v2 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Toda, A. A. (2026). _Land, G versus R, and Infinite Debt Rollover_ (CIGS Working Paper Series No. 26-002E). The Canon Institute for Global Studies.
    
- Homburg, S. (1991). Interest and growth in an economy with land. _Canadian Journal of Economics_, _24_(4), 950-959. [https://doi.org/10.2307/135659](https://www.google.com/search?q=https://doi.org/10.2307/135659)
    
- McCallum, B. T. (1987). The optimal inflation rate in an overlapping-generations economy with land. _In_ W. A. Barnett & K. J. Singleton (Eds.), _New Approaches to Monetary Economics_ (pp. 325-339). Cambridge University Press.
    
- Toda, A. A. (2025). Land bubbles despite non-vanishing rents. _Economics Letters_, _257_(112708), 1-4. [https://doi.org/10.1016/j.ecolet.2025.112708](https://www.google.com/search?q=https://doi.org/10.1016/j.ecolet.2025.112708)

### Respuesta bruta 4C

#### Nota Core 04C: Síntesis Macro-Financiera: Integración de Sobrevaloración, Colateral e Infinite Debt Rollover

El propósito de esta sección es unificar los determinantes financieros analizados en las notas 04A y 04B, proveyendo al Investigador Principal (IP) una visión integrada del circuito macroeconómico que vincula la inflación especulativa de activos no producidos con la sostenibilidad y posterior vulnerabilidad de los balances públicos y comerciales.

##### Mecanismo de integración: Del desbalance sectorial a la deflación de balances

El andamiaje macro-financiero construido por Tomohiro Hirano, Joseph Stiglitz y Alexis Akira Toda devela que la dinámica del crédito contemporáneo no puede disociarse de las regularidades de la base real de la producción. Cuando el sistema ingresa en un régimen de crecimiento desbalanceado, condicionado por productividades asimétricas y una elasticidad de sustitución intersectorial mayor a la unidad ($\sigma > 1$), las rentas físicas marginales de la tierra tienden a verse reprimidas. Paradójicamente, la escasez del suelo y el avance de las remuneraciones del factor reproducible impulsan el precio de mercado de la tierra a crecer a la par de los salarios reales, provocando una sobrevaloración estructural duradera que desvincula el precio del activo respecto a sus dividendos materiales capitalizados.

En presencia de fricciones de liquidez, esta sobrevaloración muta de inmediato en poder financiero líquido. El suelo inflado opera como el colateral premium dentro de la función de tasación del sistema de crédito privado. El incremento de la riqueza patrimonial medible relaja los límites máximos de apalancamiento (_leverage_) bancario de los emprendedores, expandiendo el volumen agregado de crédito privado. Debido a que los retornos especulativos de la tierra apalancada superan los rendimientos de la producción reproducible en el corto plazo, el sistema financiero experimenta una severa distorsión en su composición sectorial: el crédito privado se canaliza de forma desproporcionada hacia el sector de real estate/suelo, drenando los fondos de ahorro finitos de la sociedad y estrangulando el crédito comercial enfocado en bienes de capital manufacturero e industrial. Este racionamiento genera un efecto de _crowding-out_ general de equilibrio general sobre la inversión productiva real, deprimiendo la productividad de largo plazo.

Sin embargo, esta absorción y desvío de liquidez altera las condiciones macroeconómicas agregadas. La gestación de la burbuja inmobiliaria deprime la tasa de interés real de los depósitos seguros por debajo del ritmo de crecimiento general de la economía ($R < G$), subvirtiendo el axioma clásico de McCallum-Homburg. Al revertirse la ratio a un entorno persistente de $R < G$, se abre un espacio de validación macroeconómica que permite tanto al gobierno como a las corporaciones ejecutar esquemas estables de refinanciamiento infinito o _debt rollover_ de sus pasivos exigibles. La aparente sostenibilidad Ponzi de la deuda se vuelve así estructuralmente dependiente de la burbuja del colateral del suelo. La fragilidad financiera intrínseca emerge cuando la política monetaria o shocks de liquidez externa contraen las condiciones crediticias; al verse mermada la capacidad de refinanciamiento (_rollover_), la demanda especulativa colapsa endógenamente, provocando caídas drásticas en el valor del suelo, la evaporación de los colaterales bancarios y una transición de fase abrupta hacia crisis generalizadas de insolvencia y deflación estructural de balances.

##### Párrafo exportable para el memo dirigido al IP

La síntesis macro-financiera de este cluster teórico demuestra que el desbalance sectorial y la sobrevaloración del suelo constituyen las piedras angulares sobre las cuales se erige un régimen de acumulación dominado por la fragilidad financiera y el desplazamiento material. Bajo condiciones de crecimiento desbalanceado, el precio del suelo se divorcia de sus rentas físicas fundamentales para operar como una reserva pura de valor indexada al ingreso total, elevando de forma automática el valor nominal del colateral inmobiliario dentro del sistema bancario (Hirano & Toda, 2025b). Este inflamiento del colateral expande de manera endógena el crédito privado hacia el sector de real estate mediante mecanismos de apalancamiento, absorbiendo los fondos finitos del sistema y gatillando un severo _crowding-out_ de la inversión productiva destinada a bienes de capital real (Hirano et al., 2024; Hirano & Stiglitz, 2025c). Paralelamente, la gestación de esta burbuja inmobiliaria deprime los tipos de interés reales por debajo del ritmo de crecimiento económico ($R < G$), abriendo el espacio macroeconómico para que tanto las firmas como el gobierno sostengan esquemas estables de refinanciamiento infinito o _debt rollover_ (Hirano & Toda, 2026). No obstante, este andamiaje Ponzi encierra una vulnerabilidad intrínseca: al depender la continuidad de los refinanciamientos de la ininterrumpida inflación de un activo no producido, cualquier shock contractivo en la política monetaria o en los límites regulatorios de colateralización destruye la liquidez del circuito, provocando una caída drástica en el valor de los activos colaterales y desencadenando una crisis sistémica de insolvencia y deflación de balances.

##### Referencias

- Hirano, T., Jinnai, R., & Toda, A. A. (2024). _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_ (Documento de trabajo arXiv:2211.13100v7 [econ.TH]). Recuperado de los archivos de precitaciones de arXiv.
    
- Hirano, T., & Stiglitz, J. E. (2021). _Credit, Land Speculation, and Long-Run Economic Growth_ (Documento de trabajo NBER Working Paper No. 32479). National Bureau of Economic Research.
    
- Hirano, T., & Stiglitz, J. E. (2025c). _Credit, Land Speculation, and Low-Interest-Rate Policy_ (Documento de trabajo de investigación). Departamentos de Economía, Royal Holloway University of London y Columbia University.
    
- Hirano, T., & Toda, A. A. (2025b). _Unbalanced Growth and Land Overvaluation_ (CIGS Working Paper Series No. 25-011E). The Canon Institute for Global Studies. (Aceptado para publicación en _Proceedings of the National Academy of Sciences_).
    
- Hirano, T., & Toda, A. A. (2026). _Land, G versus R, and Infinite Debt Rollover_ (CIGS Working Paper Series No. 26-002E). The Canon Institute for Global Studies.
    
- Toda, A. A. (2025). Land bubbles despite non-vanishing rents. _Economics Letters_, _257_(112708), 1-4. [https://doi.org/10.1016/j.ecolet.2025.112708](https://www.google.com/search?q=https://doi.org/10.1016/j.ecolet.2025.112708)

## Citas o pasajes útiles

- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Abstract; Introduction, pp. 1–2.
    
    Pasaje: El paper parte de una desconexión histórica: la importancia del suelo como factor productivo disminuye, pero la tierra sigue siendo una reserva de valor prominente, especialmente vía real estate dentro de la riqueza de los hogares. El objeto del paper es identificar condiciones bajo las cuales el suelo queda sobrevalorado respecto de sus fundamentos, definidos como el valor presente de sus rentas.
    
    Uso posible en el memo: Sirve para presentar el Land Overvaluation Theorem sin confundirlo con una burbuja de corto plazo. La pregunta central es cómo un activo cuyo rol productivo cae puede mantener o aumentar su valor patrimonial.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Section 4.3, Theorem 1, pp. 13–14.
    
    Pasaje: El Teorema 1 establece que, bajo los supuestos del modelo, si la elasticidad de sustitución entre tierra y factores no-tierra supera la unidad y la productividad laboral crece más rápido que la productividad de la tierra, la tierra queda sobrevalorada en equilibrio. En el caso exponencial, la condición es que la productividad laboral crezca más rápido que la productividad del suelo.
    
    Uso posible en el memo: Esta es la cita central para explicar “en qué consiste” el Land Overvaluation Theorem. La versión breve: crecimiento desbalanceado + elasticidad de sustitución mayor que uno ⇒ precio del suelo por encima del valor fundamental.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Section 4.3, Theorem 1, pp. 13–14.
    
    Pasaje: Los autores enfatizan que, bajo las condiciones del teorema, no existen equilibrios donde el precio del suelo iguale su valor fundamental. Es decir, la sobrevaloración no es una posibilidad entre otras, sino el único equilibrio bajo esas condiciones.
    
    Uso posible en el memo: Permite explicar por qué el teorema tiene fuerza: no dice solo que el suelo “puede” estar sobrevalorado, sino que, bajo las condiciones especificadas, la sobrevaloración emerge necesariamente.
    
- Fuente: PDF001 — Hirano & Toda, _Unbalanced Growth and Land Overvaluation_.
    
    Página/sección: Section 4.3, implications of Theorem 1, pp. 13–14.
    
    Pasaje: El paper indica que el teorema clarifica el rol del crecimiento desbalanceado y de la elasticidad de sustitución para generar sobrevaloración del suelo. También contrasta su resultado con la visión convencional según la cual, en la tendencia de largo plazo, el precio del suelo debería reflejar su valor fundamental.
    
    Uso posible en el memo: Sirve para presentar la contribución del teorema como una teoría de tendencia de largo plazo, no como una simple explicación de booms inmobiliarios transitorios.
    
- Fuente: PDF008 — Hirano, Jinnai & Toda, _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_.
    
    Página/sección: Abstract; Introduction, pp. 1–4.
    
    Pasaje: El paper introduce un modelo macro-financiero con retroalimentación positiva entre inversión de capital y precio del suelo. Cuando el leverage se relaja más allá de un valor crítico, el sistema pasa de crecimiento balanceado —donde los precios del suelo reflejan fundamentos— a crecimiento desbalanceado, donde los precios del suelo crecen más rápido que las rentas y aparecen land bubbles.
    
    Uso posible en el memo: Es la fuente principal para conectar sobrevaloración/burbuja del suelo con apalancamiento financiero. No debe presentarse como el mismo resultado que PDF001, sino como una extensión macro-financiera complementaria.
    
- Fuente: PDF008 — Hirano, Jinnai & Toda, _Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles_.
    
    Página/sección: Introduction, pp. 3–4.
    
    Pasaje: El mecanismo del paper depende de un feedback positivo: cuando sube el precio del suelo, aumenta la riqueza agregada, se expanden las inversiones y esto eleva rentas futuras, riqueza futura y demanda por suelo. El leverage determina la intensidad de esta interacción y puede producir una transición de fase hacia una economía con burbuja del suelo.
    
    Uso posible en el memo: Sirve para explicar el canal financiero sin sobregirar la idea de colateral. El punto fuerte es que el leverage amplifica la interacción entre inversión, riqueza y precio del suelo.
    
- Fuente: PDF012 — Toda, _Land Bubbles Despite Non-Vanishing Rents_.
    
    Página/sección: Abstract; Introduction, pp. 1–2.
    
    Pasaje: Toda responde a la objeción de que las burbujas inmobiliarias racionales no existirían si el rent-yield observado es estacionario. El paper muestra que puede existir una burbuja del suelo aun cuando el housing rent-yield observado sea constante, porque este indicador mezcla renta de la estructura habitacional y renta pura del suelo.
    
    Uso posible en el memo: Advertencia metodológica. No se debe usar directamente el rent-yield de vivienda para descartar sobrevaloración del suelo si no se separa estructura construida y tierra pura.
    
- Fuente: PDF014 — Hirano & Toda, _Land, G versus R, and Infinite Debt Rollover_.
    
    Página/sección: Abstract; Introduction, pp. 1–2.
    
    Pasaje: El paper parte del resultado convencional asociado a McCallum: en una economía OLG con tierra, bajo crecimiento balanceado, la tasa de interés excede la tasa de crecimiento `R > G`, lo que precluye el infinite debt rollover. Hirano y Toda muestran que, al remover restricciones de filo de navaja y permitir crecimiento desbalanceado, bajo ciertas condiciones emerge un equilibrio eficiente con land bubbles y el infinite debt rollover se vuelve posible.
    
    Uso posible en el memo: Esta es la fuente central para explicar la relación entre tierra, `G` versus `R` y rollover. Para el brief, PDF014 debe ser la fuente principal sobre debt rollover.
    
- Fuente: PDF014 — Hirano & Toda, _Land, G versus R, and Infinite Debt Rollover_.
    
    Página/sección: Introduction, pp. 2–4.
    
    Pasaje: El paper afirma que el equilibrio con land bubbles puede ser Pareto eficiente y, aun así, permitir infinite debt rollover. Esto desafía la intuición convencional según la cual rollover infinito y Pareto ineficiencia son dos caras del mismo problema.
    
    Uso posible en el memo: Sirve para corregir una formulación posible del brief: no decir simplemente que rollover aparece porque la economía es ineficiente; en esta literatura, puede aparecer incluso con eficiencia paretiana si la burbuja del suelo es necesaria.
    
- Fuente: PDF014 — Hirano & Toda, _Land, G versus R, and Infinite Debt Rollover_.
    
    Página/sección: Introduction, pp. 3–4.
    
    Pasaje: Los autores sostienen que, en una economía con tierra, la dinámica compatible con infinite debt rollover requiere crecimiento desbalanceado, porque bajo crecimiento balanceado se obtiene `R > G`, lo que bloquea el rollover. Además, advierten que no se puede analizar coherentemente el rollover ignorando la presencia de tierra.
    
    Uso posible en el memo: Es la pieza que conecta directamente la preocupación del IP con el crecimiento desbalanceado: el desbalance no es un agregado decorativo, sino lo que reabre el espacio para rollover en una economía con tierra.
    
- Fuente: PDF014 — Hirano & Toda, _Land, G versus R, and Infinite Debt Rollover_.
    
    Página/sección: Proposition 3.3 / Discussion, pp. 13–14 y pp. 19–20.
    
    Pasaje: Cuando `G = 1` o `σ = 1`, salarios y rentas del suelo crecen a la misma tasa, se obtiene crecimiento balanceado, el precio del suelo refleja fundamentos, el equilibrio es Pareto eficiente y el infinite debt rollover es imposible. En la conclusión, los autores resumen que el rollover infinito en una economía con tierra implica dinámicas de crecimiento desbalanceado.
    
    Uso posible en el memo: Esta cita sirve para fijar la condición negativa: con tierra y crecimiento balanceado, el rollover queda bloqueado; para reabrirlo, el modelo necesita desbalance.
    
- Fuente: PDF014 — Hirano & Toda, _Land, G versus R, and Infinite Debt Rollover_.
    
    Página/sección: Corollary 2 discussion, pp. 8–9.
    
    Pasaje: En un equilibrio burbujeante, el componente burbuja del activo puede dividirse proporcionalmente; una parte puede ser interpretada como deuda pública. Si el equilibrio es asintóticamente burbujeante, la burbuja no se desvanece respecto de la economía y la autoridad fiscal puede sostener déficits indefinidamente mediante rollover de deuda.
    
    Uso posible en el memo: Esta es la formulación más precisa de “cómo” una land bubble se conecta con debt rollover en PDF014. Ojo: el argumento está formulado sobre deuda pública/Ponzi en un modelo OLG, no sobre rollover corporativo privado.
    
- Fuente: PDF014 — Hirano & Toda, _Land, G versus R, and Infinite Debt Rollover_.
    
    Página/sección: Section 4.1, pp. 16–18.
    
    Pasaje: Los autores comparan su resultado con McCallum y muestran que el resultado clásico depende de una restricción de filo de navaja, como Cobb-Douglas o crecimiento balanceado de productividades. En el caso CES, si la elasticidad de sustitución es mayor que uno, se vuelve necesaria para infinite debt rollover.
    
    Uso posible en el memo: Sirve para explicar por qué PDF014 revisa la conclusión McCallum–Homburg sin simplemente negarla: la conclusión clásica funciona en crecimiento balanceado, pero no agota el caso general.
    

### Evaluación crítica

#### Lo que aclara

- La revisión confirma que el Land Overvaluation Theorem no es idéntico a debt rollover. El primero explica cuándo el suelo queda sobrevalorado respecto del valor presente de sus rentas; el segundo analiza cuándo la presencia de tierra permite o bloquea rollover infinito de deuda.
- La conexión entre ambos pasa por el crecimiento desbalanceado. En PDF001, el desbalance permite que el precio del suelo se separe de sus fundamentos; en PDF014, el desbalance permite escapar del resultado balanceado `R > G` que bloquearía el rollover.
- PDF001 debe usarse para responder “¿en qué consiste el Land Overvaluation Theorem?”; PDF014 debe usarse para responder “¿cómo cambia el debate `G` versus `R` y el rollover cuando hay tierra?”.
- PDF008 aclara el canal macro-financiero del leverage: cuando el apalancamiento supera un umbral, puede haber una transición de fase desde precios fundamentales hacia land bubbles. Esto es útil para conectar el teorema con finanzas, pero no debe reemplazar a PDF014 en el tema rollover.
- PDF012 introduce una advertencia empírica importante: no basta observar rent-yields inmobiliarios agregados; hay que separar renta de la estructura y renta pura del suelo. Esto disciplina la forma en que el memo habla de “rentas del suelo” y “precios inmobiliarios”.
- Queda corroborado que PDF014 debe tratarse como fuente principal para el memo sobre debt rollover, porque es la versión 2026 enfocada explícitamente en `Land, G versus R, and Infinite Debt Rollover`. PDF002 puede quedar como antecedente o versión previa.
- La nota bruta acierta al conectar sobrevaloración del suelo, leverage y fragilidad, pero debe presentarlo como una **síntesis interpretativa del proyecto**, no como una única proposición formal contenida en un solo paper.

#### Lo que queda ambiguo

- La respuesta bruta afirma que el Land Overvaluation Theorem es “precondición” para infinite debt rollover. Eso es demasiado fuerte. PDF001 y PDF014 son resultados conectados por crecimiento desbalanceado y land bubbles, pero no se debe afirmar que el teorema de PDF001 sea una condición formal directa del rollover en PDF014.
- La respuesta bruta habla de “colateral bancario” y “balances corporativos” como si PDF014 trabajara ese mecanismo. PDF014 trata principalmente de infinite debt rollover/Ponzi en una economía OLG con tierra. El canal de colateral privado corresponde más bien a PDF008 y a la literatura Hirano–Stiglitz sobre crédito y land speculation.
- La respuesta bruta dice que la burbuja inmobiliaria “deprime los tipos de interés reales por debajo del crecimiento”. En PDF014, la relación es más precisa: bajo ciertas condiciones de bajos tipos, land bubbles emergen necesariamente y hacen posible el rollover; además, el crecimiento desbalanceado permite que `R < G` o que el rollover se vuelva posible pese a eficiencia paretiana. No conviene presentar la causalidad como lineal y unilateral.
- La respuesta bruta usa “Ponzi estable” y “validación macroeconómica” con un tono demasiado fuerte. Para el memo, mejor hablar de “infinite debt rollover” o “rollover indefinido” y explicar que los autores lo tratan como posibilidad de equilibrio bajo condiciones específicas.
- La nota mezcla deuda pública y deuda privada. PDF014 habla de deuda pública/infinite debt rollover en sentido formal; el IP pregunta por debt rollover en relación con especulación del suelo, lo que permite una traducción hacia balances privados, pero esa traducción debe marcarse como extensión crítica, no como resultado del paper.
- La respuesta bruta introduce “deflación estructural de balances” y “crisis sistémica de insolvencia”. Puede ser útil como lenguaje puente, pero los papers citados no desarrollan una teoría minskyana completa de deflación de balances. Hay que suavizar.
- La respuesta bruta dice que el valor productivo de la tierra “se estanca”. En PDF001/PDF014, el resultado depende de tasas relativas de productividad/rentas y elasticidad de sustitución; mejor hablar de rentas del suelo creciendo más lento que precios, no necesariamente de estancamiento absoluto.

#### Riesgo de sobreinterpretación

- Riesgo 1: colapsar Land Overvaluation, land bubble y housing-price inflation. El memo debe distinguir: overvaluation es precio por encima del valor fundamental; land bubble es una forma específica de componente burbuja; housing-price inflation observado mezcla suelo y estructuras.
- Riesgo 2: convertir PDF014 en una teoría de deuda corporativa. PDF014 se ubica en el debate de deuda pública, `G` versus `R` e infinite debt rollover. La lectura sobre propietarios financiarizados y rollover privado es una traducción del proyecto, no el objeto formal del paper.
- Riesgo 3: decir que toda sobrevaloración del suelo aumenta automáticamente colateral y genera crédito. Esa conexión es plausible y está apoyada por PDF008/PDF003, pero no es el resultado formal del Land Overvaluation Theorem.
- Riesgo 4: escribir que la burbuja “causa” `R < G` sin matices. En PDF014, el argumento es de equilibrio: bajo ciertas condiciones, land bubbles, Pareto efficiency y rollover pueden coexistir; el crecimiento desbalanceado es condición clave para escapar del bloqueo `R > G` bajo crecimiento balanceado.
- Riesgo 5: usar “sostenible” de modo normativo. En estos textos, “infinite debt rollover possible” es una posibilidad de equilibrio, no necesariamente una recomendación de política ni un régimen históricamente estable.
- Riesgo 6: atribuir a Hirano–Toda una crítica heterodoxa de financialización. Esa crítica puede ser desarrollada por el proyecto, pero debe presentarse como reencuadre propio.
- Riesgo 7: cargar demasiado la sección con Minsky. La nota puede usar “fragilidad financiera” como puente, pero no debe abrir una teoría completa de financial instability.

#### Qué debe verificarse contra la fuente original

- Verificación completada: PDF001 define land overvaluation respecto de fundamentos entendidos como valor presente de rentas del suelo.
- Verificación completada: PDF001 establece el Land Overvaluation Theorem bajo elasticidad de sustitución mayor que uno y crecimiento más rápido de productividad no-tierra/laboral frente a productividad de tierra.
- Verificación completada: PDF008 establece que una relajación del leverage más allá de un umbral crítico genera una transición de fase desde crecimiento balanceado con precios fundamentales hacia crecimiento desbalanceado con land bubbles.
- Verificación completada: PDF012 advierte que un housing rent-yield constante no descarta land bubbles, porque debe separarse la renta de la estructura de la renta pura del suelo.
- Verificación completada: PDF014 parte del resultado McCallum–Homburg según el cual, con tierra y crecimiento balanceado, `R > G` bloquea infinite debt rollover.
- Verificación completada: PDF014 sostiene que, al permitir crecimiento desbalanceado y remover restricciones de filo de navaja, pueden emerger land bubbles y el infinite debt rollover se vuelve posible.
- Verificación completada: PDF014 afirma que la dinámica con infinite debt rollover en una economía con tierra requiere crecimiento desbalanceado, porque bajo crecimiento balanceado se obtiene `R > G` y el rollover queda bloqueado.
- Verificación completada: PDF014 formula que una burbuja del activo puede dividirse proporcionalmente, una parte puede interpretarse como deuda pública, y si la burbuja no desaparece respecto de la economía, la autoridad fiscal puede sostener déficits por rollover indefinido.
- Corrección necesaria: no escribir que “Land Overvaluation Theorem es la precondición para infinite debt rollover”. Reemplazar por: “ambos resultados comparten la condición de crecimiento desbalanceado y la posibilidad de que el suelo funcione como reserva de valor/burbuja”.
- Corrección necesaria: no escribir que PDF014 prueba directamente un mecanismo de colateral bancario privado. Reemplazar por: “PDF014 formaliza debt rollover en una economía con tierra; el canal colateral/privado debe conectarse vía PDF008 y la literatura de crédito de Hirano–Stiglitz”.
- Corrección necesaria: no escribir que el rollover es “sostenible sin fragilidad”. Reemplazar por: “posible como equilibrio bajo condiciones específicas; su lectura como fragilidad financiera es una interpretación crítica del proyecto”.
- Corrección necesaria: no usar “burbuja inmobiliaria” sin distinguir tierra y estructura. Incorporar la advertencia de PDF012.

### Párrafo exportable para el memo

El Land Overvaluation Theorem y el resultado sobre debt rollover pertenecen a dos piezas distintas pero conectadas de la literatura Hirano–Toda. El primero muestra que, bajo crecimiento desbalanceado y elasticidad de sustitución mayor que uno entre tierra y factores no-tierra, el precio del suelo puede quedar por encima de su valor fundamental, definido como el valor presente de sus rentas. El segundo muestra que la presencia de tierra cambia el debate sobre `G` versus `R`: bajo crecimiento balanceado, la tierra tiende a imponer `R > G`, bloqueando el infinite debt rollover; pero al permitir crecimiento desbalanceado, pueden emerger land bubbles y el rollover infinito vuelve a ser posible incluso en equilibrios pareto-eficientes. La conexión macro-financiera es que el suelo sobrevalorado o burbujeante opera como reserva de valor y puede sostener estructuras de refinanciamiento mientras su precio continúe validado. Sin embargo, para el proyecto conviene separar el resultado formal de su traducción crítica: PDF014 trata principalmente de rollover público/Ponzi en una economía OLG con tierra, mientras que el canal de colateral, leverage y fragilidad de balances privados debe articularse con PDF008 y con la literatura de crédito de Hirano–Stiglitz. La advertencia empírica de Toda es decisiva: no se debe inferir ausencia de burbuja desde rent-yields inmobiliarios agregados sin separar renta de estructuras y renta pura del suelo.
### Estado

- [x] Input 4A enviado
- [x] Output 4A capturado
- [x] Input 4B enviado
- [x] Output 4B capturado
- [x] Input 4C enviado
- [x] Output 4C capturado
- [x] Citas verificadas
- [x] Párrafo exportable redactado
- [ ] Integrado en `05_OUTPUT_Memo_Breve_IP`
