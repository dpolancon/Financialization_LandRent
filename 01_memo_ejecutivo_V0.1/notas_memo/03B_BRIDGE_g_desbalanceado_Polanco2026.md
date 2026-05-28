# Conceptualización del Crecimiento Desbalanceado: Un Enfoque de Elasticidad de Transformación y Conflicto Distributivo

**Autor:** Diego Polanco

**Marco de Referencia:** Capítulo 1 - Réplica Crítica y Clausura Macroeconómica (UMass Amherst, 2026)

**Propósito de esta Nota:** Servir como marco conceptual para auditar teorías de la renta del suelo (como Stiglitz-Hirano-Toda) y fundamentar por qué la dinámica macroeconómica y las decisiones de venta no requieren de microfundamentos neoclásicos de optimización intergeneracional (OLG), sino de restricciones de balance, dinámicas de acumulación desbalanceada y conflicto de clases.

## 1. La Reinterpretación del Coeficiente Producto-Capital: La Elasticidad de Transformación ($\theta$)

En la macroeconomía convencional y en el análisis tradicional de Anwar Shaikh (2016), la relación de largo plazo entre el producto y el capital se trata como una constante técnica o un mero artefacto algebraico de contabilidad.

Tu marco redefine este parámetro crítico. El coeficiente estimado de la relación en niveles de largo plazo se conceptualiza formalmente como la **elasticidad de transformación de la capacidad productiva respecto al stock de capital (**$\theta$**)**:

$$\theta \equiv \frac{\partial \ln Y^p}{\partial \ln K}$$

Este parámetro rige la velocidad y la eficiencia con la que la acumulación de capital físico ($K$) se traduce en la creación de capacidad productiva real ($Y^p$). En lugar de ser un indicador técnico estático, $\theta$ es un **parámetro institucional e históricamente contingente**, condicionado por el régimen de acumulación, la presión de balances y el conflicto distributivo.

## 2. La Clausura de Crecimiento Desbalanceado ($\theta \neq 1$)

La mayoría de los modelos postkeynesianos y neoclásicos imponen implícitamente una clausura de crecimiento balanceado asumiendo una transformación de capacidad unitaria ($\theta = 1$). Tu conceptualización rompe con esta limitación (el "filo de la navaja" harrodiano) al formalizar el **crecimiento desbalanceado como una condición sistémica general (**$\theta \neq 1$**)**.

### Dinámica de Acumulación sin Progreso Técnico

Partiendo de la identidad de acumulación y una clausura de ahorro-inversión estándar, se demuestra que la trayectoria dinámica de la tasa de acumulación neta de capital ($\hat{k} \equiv \dot{K}/K - \delta$) está gobernada por la siguiente **Ecuación Diferencial Ordinaria de Bernoulli de segundo orden**:

$$\frac{d\hat{k}}{dt} = (\theta - 1)\hat{k}(\hat{k} + \delta)$$

Donde $\delta$ representa la tasa de depreciación física del capital.

### Análisis de Fases y Regímenes Dinámicos

El comportamiento asintótico del sistema depende estrictamente del valor de la elasticidad de transformación ($\theta$):

1. **Régimen de Sobreacumulación (**$\theta < 1$**):**
    
    - **Dinámica:** La acumulación de capital crece a un ritmo superior al de la creación de capacidad productiva.
        
    - **Estabilidad:** El atractor de estancamiento ($\hat{k}^*_1 = 0$) es **localmente estable** ($f'(0) < 0$).
        
    - **Resultado:** La acumulación neta experimenta una desaceleración endógena y sistemática hacia el estancamiento, lo que refleja la tendencia al subconsumo o sobreacumulación clásica sin necesidad de shocks exógenos.
        
2. **Régimen de Capacidad Excedente (**$\theta > 1$**):**
    
    - **Dinámica:** La capacidad productiva se expande más rápido que el stock de capital acumulado.
        
    - **Estabilidad:** El equilibrio de estancamiento es inestable ($f'(0) > 0$).
        
    - **Resultado:** La acumulación se acelera de manera explosiva sin límites por el lado de la oferta.
        
3. **Crecimiento Balanceado (**$\theta = 1$**):**
    
    - El caso restrictivo tradicional donde el capital y la capacidad se expanden de forma estrictamente proporcional.
        

## 3. Estabilización por Tendencia vs. Mecanismos Reales (La Crítica a Shaikh)

Para evitar que el sistema con sobreacumulación ($\theta < 1$) colapse hacia el estancamiento absoluto, la especificación uniecuacional clásica (Shaikh, 2016) introduce de manera ad-hoc un término de tendencia determinista ($b$) que representa el progreso técnico autónomo ($\hat{y}^p = \theta \hat{k} + b$).

Al incorporar este término, la dinámica de aceleración se transforma en una **EDO cuadrática**:

$$\frac{d\hat{k}}{dt} = (\hat{k} + \delta)[(\theta - 1)\hat{k} + b]$$

Esta modificación altera la estructura de equilibrio del sistema, reemplazando el colapso por un **atractor interior estable**:

$$\hat{k}^* = \frac{b}{1 - \theta}$$

### El Problema de la Doble Especificación Errónea

Tu análisis demuestra que este cierre estabilizado por tendencia es un **artificio puramente algebraico**. Al imponer un parámetro temporal constante ($b$) y una elasticidad fija ($\theta$) sobre una serie histórica de largo plazo, el modelo uniecuacional incurre en una doble especificación errónea (Basu, 2020):

- Fuerza a un término determinista ($b$) a absorber variaciones institucionales e históricas de gran relevancia.
    
- Omite las variables de conflicto distributivo, haciendo que la elasticidad estimada $\hat{\theta}$ actúe como un promedio matemático plano que invisibiliza los cambios de régimen macroeconómico.
    

## 4. El Cierre Sistémico: Conflicto Distributivo y la Tasa de Explotación ($e_t$)

La tesis fundamental de tu marco empírico (Stage S2) es que la relación producto-capital **no puede aislarse como una ley de producción técnica y neutral**. Cuando la relación se analiza dentro de un sistema multiecuacional (VECM), el vector bivariado elemental $X_t = (\ln Y_t, \ln K_t)'$ **se fractura por completo**, mostrando inestabilidad y ausencia de cointegración reproducible.

La estabilidad sistémica (co-integración de rango uno) se recupera **exclusivamente** cuando el modelo se expande a un sistema trivariado condicionado por la **tasa de explotación logarítmica (**$e_t$**)**:

$$X_t = \left(\ln Y_t, \ln K_t, e_t\right)' \quad \text{donde} \quad e_t = \ln \left(\frac{\pi_t}{1 - \pi_t}\right)$$

Donde $\pi_t$ representa la participación de los beneficios en el valor agregado corporativo.

### Consecuencias Teóricas del Cierre Trivariado

- **La distribución es una precondición matemática:** La tasa de explotación no es un resultado derivado o de "segundo orden" del crecimiento, sino el ancla estructural que estabiliza el espacio de cointegración del sistema de acumulación.
    
- **Sensibilidad a Shocks Históricos:** El sistema solo se estabiliza bajo la influencia del vector de variables dummy de control histórico ($h_2: 1956, 1974, 1980$), correspondientes a la transición del Estado keynesiano hacia el neoliberalismo financiero (el choque de Volcker).
    

## 5. El Contra-modelo frente a la Teoría del Suelo de Stiglitz-Hirano-Toda (S-H-T)

Este marco de crecimiento desbalanceado ofrece la arquitectura perfecta para desmontar el modelo neoclásico-financiero de S-H-T y responder críticamente a las interrogantes de tu IP:

### El Desmantelamiento de OLG

- **La trampa neoclásica:** S-H-T requieren de un modelo de Generaciones Traslapadas (OLG) porque bajo un agente optimizador infinito, este planificaría intertemporalmente a perpetuidad, desestimando la venta de un activo que se valoriza sistemáticamente por encima de la tasa de interés.
    
- **Tu alternativa de Clausura:** Bajo tu marco de crecimiento desbalanceado, los propietarios de suelo son conceptualizados como **agentes financiarizados insertos en una economía de excedente y fragilidad financiera**. Su comportamiento no está determinado por la optimización de la utilidad intergeneracional, sino por la **rigidez de sus estructuras de pasivos y restricciones de balance**.
    
- **El mecanismo de venta:** Las ventas de suelo se explican de forma endógena por requerimientos críticos de liquidez y fechas de vencimiento improrrogables de deudas (_debt rollover_). Si la acumulación sistémica se encuentra en un régimen de sobreacumulación ($\theta < 1$), las tensiones de balance se agudizan, forzando la liquidación de activos reales (como terrenos) para sostener la solvencia financiera de los balances de los propietarios. El conflicto distributivo regulado por $e_t$ determina en última instancia la disponibilidad de liquidez del sistema, prescindiendo por completo de la necesidad teórica de modelar agentes que mueren periódicamente.