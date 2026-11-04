# Teoría de cambio de Manizales Más

Documento web interactivo de un solo archivo. **Versión 7.0** · noviembre de 2026.

`index.html` es autocontenido: CSS, JavaScript, logo, tipografía Poppins y el modelo
completo van embebidos. Se abre con doble clic o se publica en GitHub Pages
(Settings → Pages → rama `main`, carpeta `/ (root)`).

## Secciones

| Sección | Contenido |
|---|---|
| 01 Modelo | Qué es Manizales Más, hacia dónde va y sus cuatro frentes de trabajo |
| 02 Teoría de cambio | La cadena de cada frente, de la problemática al impacto, por línea o por programa, con la hipótesis y la evidencia que la sustenta. Debajo, «Cómo lo medimos»: los indicadores, filtrados por lo que se seleccione en la cadena |
| 03 Glosario | Qué significa exactamente cada término al medir y reportar, y las reglas para contar |
| 04 Referencias | Evidencia, marcos, fuentes de datos y programas |

## Cambios de la versión 7.0

- **Impacto:** crecimiento económico de Manizales y Caldas (ventas reales y empleo formal de
  las empresas, empleo formal de los jóvenes, siempre frente a grupo de comparación), en lugar
  de mejora de ingresos. Cada ficha dice qué permite afirmar su cifra: gestión, seguimiento,
  efecto o contexto. Contexto regional sin atribución.
- **Ecosistema:** el resultado es mejores condiciones del entorno para crecer (dominios de
  Babson, actores de MIT REAP), no acceso a financiación. Nuevo resultado de cultura de crecimiento.
- **Empresas:** fórmula de las 3C (clientes, capacidad, caja), apertura de mercados y canales,
  conversión comercial; emprendimiento temprano medido por validación, supervivencia y resiliencia.
- **Talento:** rutas separadas de empleabilidad (colocación, permanencia a 90 días, pertinencia)
  y emprendimiento (validación, ventas), más índice de agencia.
- **Mentoría y transferencia:** compromisos estratégicos cumplidos, retribución (give back),
  toolkits, territorios diagnosticados y madurez institucional.
- **Contribución multiactor** como supuesto explícito y **glosario** unificado.
- **Evidencia:** cada cadena causal presenta los estudios que sustentan su diseño.
- Se reconstruyó la interfaz: navegación con enlaces, diseño adaptable a celular, accesibilidad
  (foco, etiquetas, contraste, movimiento reducido) e impresión de todas las secciones.

Siete actividades con la misma fórmula se miden con un indicador común (`ACT_0`), así que hay
54 indicadores distintos.

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
Los programas declaran sus elementos; programas por indicador, conteos y usos del glosario
se calculan solos, así que basta editar en un lugar.

## Principios

1. **Impacto solo con comparación.** Sin grupo de comparación es seguimiento.
2. **Ninguna cifra sola.** Las ventas se reportan con empleo formal, margen y caja.
3. **Contribución, no atribución.** Se nombran los aliados que cofinancian.
4. **Definiciones únicas.** Toda cifra pública usa el glosario.
5. **Sin datos personales.** El repositorio no aloja bases con identificadores.
