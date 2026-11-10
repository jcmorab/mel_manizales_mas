# Teoría de cambio de Manizales Más

Documento web interactivo de un solo archivo. **Versión 7.1** · noviembre de 2026.

`index.html` es autocontenido: CSS, JavaScript, logo, tipografía Poppins y el modelo
completo van embebidos. Se abre con doble clic o se publica en GitHub Pages
(Settings → Pages → rama `main`, carpeta `/ (root)`).

## Secciones

| Sección | Contenido |
|---|---|
| 01 Modelo | Qué es Manizales Más, hacia dónde va, sus tres frentes de trabajo y la base de sostenibilidad que los sostiene |
| 02 Teoría de cambio | La cadena de cada frente (empresas, talento y ecosistema), de la problemática al impacto, por frente o por programa, con la base de sostenibilidad debajo. Cada frente tiene su hipótesis con la evidencia que la sustenta y sus supuestos: lo que tiene que pasar para que funcione. Debajo, «Cómo lo medimos»: los 45 indicadores agrupados por etapa, filtrados por lo que se seleccione en la cadena |
| 03 Referencias | La evidencia de cada cadena, con el paso que sostiene cada estudio; marcos, fuentes de datos y programas |

## Cambios de la versión 7.1 (observaciones de la gerencia)

- **Impacto:** las empresas se miden por ventas, supervivencia a 24 meses y empleo formal con masa salarial;
  los jóvenes, por sus ingresos (por empleo o por negocio propio) a 12 y 24 meses.
- **Empresas:** nuevas actividades de entrenamiento con expertos (metodología de Babson College) y de
  aprendizaje entre pares; «conversión comercial» pasa a «propuestas comerciales que terminan en venta».
- **Talento:** la problemática es la falta de ingresos estables; se miden los empleos que generan los
  negocios de los jóvenes, formales e informales por separado.
- **Ecosistema:** organizado en las seis dimensiones del modelo adaptado a Manizales (mercados, política,
  finanzas, cultura, soporte, y trabajo y talento), con un indicador por dimensión y el índice como síntesis.
  Entrenamiento a mentores, Profesores de Alto Potencial y La ruta del emprendimiento pasan a este frente.
- **Sostenibilidad:** reemplaza a Transferencia como la base que sostiene los tres frentes, con cuatro
  componentes: transferencia a otros ecosistemas, proceso comercial, pago por resultados y comunidad.
  Queda marcada como propuesta para validar.

## Cambios de la versión 7.0

- **Impacto:** crecimiento económico de Manizales y Caldas (ventas reales y empleo formal de
  las empresas, empleo formal de los jóvenes, siempre frente a grupo de comparación), en lugar
  de mejora de ingresos. Cada ficha dice qué no cuenta.
- **Ecosistema:** el resultado es mejores condiciones del entorno para crecer (dominios de
  Babson, actores de MIT REAP), no acceso a financiación. Nuevo resultado de cultura de crecimiento.
- **Empresas:** fórmula de las 3C (clientes, capacidad, caja), apertura de mercados y canales,
  conversión comercial; emprendimiento temprano medido por validación, supervivencia y resiliencia.
- **Talento:** rutas separadas de empleabilidad (colocación, permanencia a 90 días, pertinencia)
  y emprendimiento (validación, ventas), más índice de agencia.
- **Mentoría y transferencia:** compromisos estratégicos cumplidos, retribución (give back),
  toolkits, territorios diagnosticados y madurez institucional.
- **Contribución multiactor** como supuesto explícito.
- **Evidencia:** cada cadena causal presenta los estudios que sustentan su diseño.
- Se reconstruyó la interfaz: navegación con enlaces, diseño adaptable a celular, accesibilidad
  (foco, etiquetas, contraste, movimiento reducido) e impresión de todas las secciones.

Las actividades se miden con un indicador común de agenda (`ACT_0`) y las finalizaciones de ruta con
uno solo (`PRD_0`). La problemática y los supuestos se presentan como enunciados, sin indicador propio.
En total hay 45 indicadores: 1 de actividades, 9 de productos, 31 de resultados y 4 de impacto.

Los códigos de indicadores se renumeraron; el libro técnico de Excel debe regenerarse con este modelo.

## Marco conceptual

- **Babson Entrepreneurship Ecosystem Project** (Isenberg): el ecosistema se construye
  alrededor de empresas existentes que escalan. Aporta el impacto de crecimiento, el foco en
  empresas de alto potencial, los seis dominios (políticas, financiación, cultura, apoyos,
  capital humano, mercados) y la regla "escala antes que cantidad".
- **MIT REAP** (Caldas, cohorte 8, 2021 a 2023): cinco tipos de actor, capacidad innovadora
  y emprendedora, ventaja comparativa y apuestas estratégicas regionales; distinción entre
  pymes y empresas de base innovadora.
- **MIT Venture Mentoring Service**: mentoría en equipo por hitos, medida como hitos
  estratégicos cumplidos.

## Editar el modelo

El modelo vive en el bloque `<script type="application/json" id="model">` de `index.html`.
Los programas declaran sus elementos; programas por indicador y conteos
se calculan solos, así que basta editar en un lugar.

## Principios

1. **Impacto solo con comparación.** Sin grupo de comparación es seguimiento.
2. **Ninguna cifra sola.** Las ventas se reportan con empleo formal, margen y caja.
3. **Contribución, no atribución.** Se nombran los aliados que cofinancian.
4. **Definiciones únicas.** Toda cifra pública usa la definición de su ficha.
5. **Sin datos personales.** El repositorio no aloja bases con identificadores.
