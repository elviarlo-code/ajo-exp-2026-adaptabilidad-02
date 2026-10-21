# Ajo 2026 — Supervivencia y desempeño de seis cultivares

**Institución:** INIA — EEA Vista Florida, Picsi, Lambayeque, Perú. **Siembra:** 17 de abril de 2026.

## Diseño y objetivo

Diseño de bloques completos al azar (DBCA), seis cultivares y cuatro bloques: **24 unidades experimentales**. Evaluar supervivencia, formación de bulbos, productividad y características morfológicas ante las condiciones restrictivas de la campaña de siembra temprana 2026. Se mantiene el diseño original y no se descartan parcelas con mortalidad total.

**Tratamientos:** T1 INIA 105 Donajus; T2 Ajo Blanco INIA; T3 Ajo Chino; T4 Ajo Kiyan/Kyan (denominación por validar); T5 Ajo Santeño; T6 Ajo Cañetano.

**Localidad de ejecución única: Vista Florida.** No se instaló el ensayo de ajo en Íllimo.

## Organización

- `protocols/`: F-010, protocolos y flujo de medición.
- `data/raw/`: fichas Excel originales de 24 U.E., bulbos individuales, clima y suelo.
- `data/metadata/`: diccionario de variables y trazabilidad.
- `data/processed/`: CSV procesados, generados reproduciblemente.
- `scripts/`: código Python para limpieza, verificación y análisis.
- `results/`: tablas estadísticas.
- `figures/`: gráficos.
- `manuscript/`: borrador científico.
- `docs/`: registro de decisiones metodológicas.

## Geometría de la U.E.

Dos surcos nominales de 4 m: uno con una hilera y otro con dos hileras. Si se cosechan completos: 8 metros lineales de surco y 12 metros lineales de hilera. Registrar la longitud **realmente cosechada** para cada U.E.; no reemplazar metros de superficie por metros lineales sin conservar dimensiones.

## Reglas de medición y análisis

- Pesar todos los bulbos del lote por U.E. antes de clasificar y registrar cada bulbo por separado.
- Mantener separados aptitud física, calibre y condición comercial (umbrales por documentar).
- Mortalidad completa constatada implica supervivencia 0 y producción 0; un campo no medido permanece vacío.
- La U.E. es la unidad de inferencia estadística; los bulbos individuales son submuestras.
- Supervivencia: conteos binomiales por U.E. y control de bloque; productividad: peso de toda la U.E., incluido cero real.
- Comparación 2025–2026: exploratoria, porque cambiaron simultáneamente fecha, suelo y ambiente meteorológico.
- No sobrescribir datos crudos; generar cálculos derivados en Python y conservar versiones.

## Archivos de evaluación

Se prepararon tres libros XLSX para colocar en `data/raw/`:

1. `01_Evaluacion_UE_ajo_2026.xlsx` — censos, producción y geometría.
2. `02_Evaluacion_bulbos_ajo_2026.xlsx` — peso, diámetros, dientes y calidad por bulbo.
3. `03_Evaluacion_clima_suelo_ajo_2026.xlsx` — meteorología y análisis de suelo.

## Investigación relacionada

- [Ajo experimental 2025](https://github.com/elviarlo-code/ajo-exp-2025-adaptabilidad-01)
- [Hoja de ruta ajo 2030](https://github.com/elviarlo-code/ajo-tecnologia-2030)

**Responsable técnico:** Ing. Víctor Ramírez Lora. **Estado:** plantillas y protocolos; mediciones reales pendientes de incorporación.
