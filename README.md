# Teoría de cambio de Manizales Más

Documento web interactivo de un solo archivo. **Versión 7.0** · noviembre de 2026.

`index.html` es autocontenido: CSS, JavaScript, logo, tipografía Poppins y el modelo
completo van embebidos. Se abre con doble clic o se publica en GitHub Pages
(Settings → Pages → rama `main`, carpeta `/ (root)`).

## Secciones

| Sección | Para qué sirve |
|---|---|
| Modelo | Impacto, principio de contribución, tablero de la junta con los 19 indicadores clave, marco conceptual (Babson, MIT REAP, MIT VMS), el portafolio en los seis dominios del ecosistema, las cuatro líneas y los cambios de la versión |
| Teoría de cambio | La cadena por línea (problemática → actividades → productos → resultados → impacto), con resaltado por programa, hipótesis y supuestos |
| Programas | Qué hace cada programa, por qué indicadores responde y qué no debe reportarse como resultado |
| Indicadores | 54 fichas técnicas filtrables (19 clave), con exportación a CSV e instrumentos de recolección |
| Glosario | Definiciones operativas: qué cuenta, qué no cuenta y cómo comunicarlo; reglas comunes de cálculo |
| Referencias | Babson, MIT REAP, fuentes oficiales e institucionales, con el indicador que respalda cada una |

Cada ficha tiene enlace propio (por ejemplo `#indicadores/RES_6` o `#glosario/empleo_formal`)
para citarla en reportes y boletines.

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
- **Contribución multiactor** como supuesto explícito y **glosario operativo** unificado.
- Se reconstruyó la interfaz: navegación con enlaces, diseño adaptable a celular, accesibilidad
  (foco, etiquetas, contraste, movimiento reducido) e impresión de todas las secciones.

Siete actividades con la misma fórmula se miden con un indicador común (`ACT_0`), así que hay
54 indicadores distintos: 19 clave para la junta, cooperantes y medios, y el resto para gestión.

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
