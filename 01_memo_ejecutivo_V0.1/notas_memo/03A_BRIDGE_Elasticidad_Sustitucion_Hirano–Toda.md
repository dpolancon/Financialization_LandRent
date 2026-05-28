---
type: bridge_note
status: active
priority: urgent
project: suelo_credito_formacion_capital
bridge_for:
  - 03_CORE_Crecimiento_Desbalanceado_SHT_vs_Polanco
  - 04_CORE_Land_Overvaluation_Debt_Rollover
theme: elasticidad_de_sustitucion
created: 2026-05-25
---

#  Elasticidad de sustitución en la literatura Hirano–Toda

## Pregunta que resuelve esta nota

¿Qué significa la elasticidad de sustitución en esta literatura y por qué aparece como condición central para Land Overvaluation, land bubbles y debt rollover?

## Respuesta corta

En esta literatura, la elasticidad de sustitución mide qué tan fácilmente la producción puede reemplazar tierra por factores no-tierra —trabajo, capital, estructuras, tecnología o construcción vertical— cuando cambia la escasez relativa de la tierra.

No es una elasticidad de demanda por suelo.  
No es una elasticidad precio de la vivienda.  
No es la elasticidad de transformación `θ` de la contribución propia.  
Es una propiedad tecnológica de la función de producción.

Su importancia es directa: cuando `σ > 1`, la economía puede seguir expandiendo producción usando factores reproducibles aun cuando la tierra sea fija. Eso permite que la tierra pierda peso productivo relativo, pero conserve o aumente su precio como reserva de valor. Ahí aparece el núcleo del Land Overvaluation Theorem.

---

## Definición operativa

La elasticidad de sustitución indica cuánto cambia la proporción entre dos insumos cuando cambia su precio relativo.

En el caso de esta literatura, los insumos relevantes son:

- tierra / factores no-tierra;
- tierra / trabajo;
- tierra / capital;
- suelo fijo / construcción o espacio construido.

Una formulación estándar es:

```text
σ = cambio porcentual en la razón de insumos
    dividido por
    cambio porcentual en la razón de precios de factores
```

En Hirano–Jinnai–Toda, la elasticidad relevante entre capital y tierra se define como:

```
σ(K, X) = - ∂ log(K/X) / ∂ log(F_K/F_X)
```

donde `K` es capital, `X` es tierra, y `F_K/F_X` es la razón de productos marginales o precios relativos de factores. Los autores subrayan que esta es la elasticidad que importa para generar land price bubbles en su modelo, no cualquier elasticidad de sustitución genérica.

---

## Intuición económica

Si `σ` es baja, la tierra es difícil de reemplazar. Aunque haya más capital, tecnología o trabajo, la producción sigue necesitando tierra en proporciones rígidas. En ese caso, las rentas de la tierra tienden a moverse más de cerca con el crecimiento de la economía.

Si `σ > 1`, la tierra puede ser sustituida con relativa facilidad por factores reproducibles. Por ejemplo:

- construir edificios más altos sobre la misma superficie;
- usar más capital o tecnología para reducir el peso directo del suelo;
- desplazar producción hacia sectores menos intensivos en tierra;
- expandir actividades modernas intensivas en trabajo calificado, capital o conocimiento.

Por eso, en Hirano–Toda, `σ > 1` permite una paradoja: la tierra pierde centralidad como factor productivo, pero su precio puede seguir aumentando como activo patrimonial o reserva de valor.

---

## Rol en el Land Overvaluation Theorem

En `Unbalanced Growth and Land Overvaluation`, Hirano y Toda establecen que la sobrevaloración del suelo emerge necesariamente cuando se cumplen dos condiciones:

1. la elasticidad de sustitución entre tierra y factores no-tierra excede 1;
2. el progreso tecnológico es más rápido en los sectores o factores no intensivos en tierra.

Los autores dan una intuición muy clara: cuando `σ > 1`, el crecimiento de las rentas del suelo queda reprimido o crece más lento, porque la producción puede sustituir tierra por factores no-tierra. Pero el precio del suelo sigue siendo empujado por ingresos crecientes y por su papel como reserva de valor. El resultado es que el precio del suelo crece más rápido que sus rentas y el price-rent ratio tiende a subir.

En el caso exponencial, si la productividad de los factores no-tierra crece más rápido que la productividad de la tierra, la condición del teorema se cumple cuando `σ > 1`. Los autores resumen esto como crecimiento desbalanceado: productividad laboral o no-tierra creciendo más rápido que productividad de la tierra.

---

## Por qué `σ > 1` no es un detalle técnico menor

La condición `σ > 1` permite separar dos movimientos:

1. el movimiento productivo de la tierra;
2. el movimiento patrimonial del precio del suelo.

Con `σ > 1`, la tierra puede perder peso en la producción porque se vuelve sustituible en términos técnicos. Pero no pierde necesariamente su función como store of value. Por eso la economía puede transitar desde una estructura agraria o land-intensive hacia una economía moderna, mientras el suelo sigue concentrando riqueza patrimonial.

Hirano y Toda justifican `σ > 1` por dos vías. Primero, empíricamente, citan estimaciones para bienes raíces residenciales y comerciales donde la elasticidad de sustitución entre tierra y factores no-tierra supera la unidad. Segundo, argumentan que `σ < 1` puede producir un comportamiento patológico de tasas de interés en el modelo.

---

## Relación con crecimiento desbalanceado

La elasticidad de sustitución no produce por sí sola la sobrevaloración del suelo. Necesita combinarse con crecimiento desbalanceado.

El mecanismo es:

```
Productividad no-tierra crece más rápido que productividad de tierra+ σ > 1→ la economía sustituye tierra por factores reproducibles→ las rentas del suelo crecen relativamente más lento→ ingresos/salarios/riqueza crecen más rápido→ el suelo sigue demandado como reserva de valor→ el precio del suelo crece más rápido que sus rentas→ aparece land overvaluation
```

En el ejemplo de transición desde economía malthusiana hacia economía moderna, los autores muestran que la sobrevaloración emerge si la productividad del sector moderno crece más rápido que la del sector tradicional intensivo en tierra. En el caso exponencial, la condición se reduce a `G₂ > G₁`.

---

## Rol en leverage y land bubbles

En `Leverage, Endogenous Unbalanced Growth, and Asset Price Bubbles`, la elasticidad de sustitución aparece en una arquitectura distinta.

Aquí el objeto no es solamente la sobrevaloración del suelo por crecimiento sectorial desbalanceado, sino una transición de fase entre dos regímenes:

- régimen fundamental / crecimiento balanceado;
- régimen burbujeante / crecimiento desbalanceado.

Los autores muestran que, cuando el leverage supera un umbral crítico, el sistema puede pasar a un régimen donde el precio del suelo crece más rápido que sus rentas. La elasticidad de sustitución entre capital y tierra es relevante para determinar la región donde emergen bubbles.

El paper advierte que hay que distinguir la elasticidad de la función de producción básica `f` de la elasticidad relevante en la función `F`, que incorpora el objeto de riqueza agregada. La elasticidad que importa para generar burbujas del suelo es la elasticidad entre `K` y `X` en `F`.

---

## Rol en debt rollover

En `Land, G versus R, and Infinite Debt Rollover`, Hirano y Toda usan una función CES donde `σ` es la elasticidad de sustitución entre trabajo y tierra. Ahí `σ > 1` es esencial para reabrir la posibilidad de infinite debt rollover en una economía con tierra.

Bajo crecimiento balanceado, la presencia de tierra tiende a imponer `R > G`, bloqueando el rollover. Pero con crecimiento desbalanceado y `σ > 1`, las rentas del suelo pueden crecer más lento que la economía, mientras el precio del suelo puede alojar una burbuja. En la proposición central, con `G > 1` y `σ > 1`, si la tasa `R` es menor que `G^(1/σ)`, todos los equilibrios son asintóticamente burbujeantes, Pareto eficientes, y el infinite debt rollover es posible.

---

## Qué NO significa elasticidad de sustitución aquí

### No es elasticidad de demanda por suelo

No mide cuánto compran los agentes cuando cambia el precio del suelo. Mide sustitución tecnológica entre factores de producción.

### No es elasticidad precio de vivienda

No debe confundirse con la sensibilidad del precio inmobiliario frente a crédito, tasas o ingreso.

### No es igual a `θ`

La elasticidad de sustitución `σ` pertenece a la función de producción y mide reemplazo entre factores.

La elasticidad de transformación `θ`, en la contribución propia, mide cómo la acumulación de capital se transforma en capacidad productiva.

Ambas son elasticidades, pero responden preguntas distintas:

|Elasticidad|Pregunta|Objeto|
|---|---|---|
|`σ`|¿Qué tan sustituible es la tierra por factores no-tierra?|Tecnología / producción|
|`θ`|¿Qué tan proporcionalmente se transforma el capital acumulado en capacidad productiva?|Acumulación / capacidad|
|`σ > 1`|La tierra puede perder peso productivo mientras su precio crece como activo.|Land overvaluation|
|`θ ≠ 1`|El capital no se transforma proporcionalmente en capacidad productiva.|Crecimiento desbalanceado propio|

---

## Fórmula verbal para el memo

En esta literatura, la elasticidad de sustitución cumple una función precisa: permite explicar cómo la tierra puede volverse relativamente menos importante en la producción sin dejar de aumentar como activo patrimonial. Cuando `σ > 1`, los factores reproducibles pueden sustituir a la tierra en la producción; por ejemplo, mediante construcción vertical, capital, tecnología o desplazamiento hacia sectores modernos menos intensivos en suelo. Si al mismo tiempo la productividad de esos factores no-tierra crece más rápido que la productividad de la tierra, las rentas del suelo crecen más lentamente que los ingresos agregados. Sin embargo, como la tierra sigue funcionando como reserva de valor, su precio puede crecer junto con la riqueza de la economía. Esa divergencia entre precio y renta es el núcleo del Land Overvaluation Theorem.