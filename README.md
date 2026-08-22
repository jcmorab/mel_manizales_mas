# Teoría de cambio de Manizales Más

Documento web interactivo de un solo archivo.

**Versión 2.4** · Agosto de 2026

---

## Contenido

```
mel_manizales_mas/
├── index.html      Documento interactivo, autocontenido
├── README.md
└── .gitignore
```

`index.html` no depende de recursos externos: CSS, JavaScript, modelo, logo y las
tres variantes de Poppins van embebidos. Se abre con doble clic, se envía por correo
o se publica en cualquier servidor estático. Los únicos enlaces salientes son las
referencias bibliográficas.

---

## Publicar en GitHub Pages

```bash
git init
git add .
git commit -m "Teoría de cambio de Manizales Más, versión 2.4"
git branch -M main
git remote add origin https://github.com/USUARIO/mel_manizales_mas.git
git push -u origin main
```

En **Settings → Pages**, elegir *Deploy from a branch*, rama `main`, carpeta
`/ (root)`. La URL será `https://USUARIO.github.io/mel_manizales_mas/`.

Si la página sale en blanco: verificar con `git ls-files` que `index.html` esté en el
commit, revisar que la rama y carpeta en Pages sean las correctas, y mirar la pestaña
Actions. El documento tiene una red de seguridad: si el JavaScript falla, despliega
todas las secciones con un aviso en lugar de quedar en blanco.

---

## Las cinco secciones

| Sección | Contenido |
|---|---|
| 01 Modelo institucional | Quiénes somos, el impacto que persigue la alianza, las cifras del sistema y las cuatro líneas |
| 02 Teoría de cambio | La rejilla completa, con interruptor por línea o por programa |
| 03 Cadenas causales | Las cuatro secuencias con su hipótesis y sus supuestos, cada uno con riesgo, señal de alerta y respuesta |
| 04 Indicadores | Los 39 indicadores en tabla filtrable, con ficha completa al abrir cada fila |
| 05 Referencias | Las 22 fuentes, con su uso y su fecha de verificación |

### El interruptor de la rejilla

**Por línea** filtra con la leyenda de colores, que incluye un chip "Todas" para
volver al conjunto. **Por programa** muestra dos hileras separadas: arriba los cinco
programas de portafolio, abajo los demás. Al seleccionar uno se ilumina su recorrido
completo por la teoría y el resto se atenúa; al abrir una tarjeta se muestra qué hace
ese programa concretamente en esa parte de la cadena, no el indicador.

### Enunciado e indicador

Un elemento de la teoría y un indicador no son lo mismo. El diagrama muestra el
enunciado; la sección 04 muestra la medición. Abrir una fila de la tabla despliega la
ficha completa: definición, forma de cálculo, lógica, periodicidad, responsable,
desagregación, línea base, estado de la meta, instrumento de recolección y
referencias que la respaldan.

| Elemento | Enunciado | Indicador |
|---|---|---|
| `IMP_1` | Crecimiento de las ventas de las empresas acompañadas | Efecto sobre las ventas reales a 24 meses |
| `IMP_3` | Vinculación laboral de los jóvenes participantes | Efecto sobre la vinculación laboral de los participantes |
| `IMP_5` | Crecimiento de las empresas atendidas en los territorios replicadores | Diferencia en el crecimiento de ventas frente a un grupo de comparación local |

---

## El modelo

Cuatro líneas, cada una con problemática, cadena e impacto propios.

| Código | Línea | A quién atiende | Impacto |
|---|---|---|---|
| `EMP` | Empresas | Empresas con operación establecida y capacidad de crecer | Ventas y empleo |
| `TAL` | Talento | Jóvenes entre 18 y 25 años en búsqueda de empleo o con un emprendimiento | Vinculación laboral |
| `ECO` | Ecosistema | Oportunidades de negocio y financiación que requieren varios actores | Negocios de mayor escala |
| `TRF` | Transferencia | Territorios y organizaciones que adoptan la metodología | Crecimiento en el territorio replicador |

Transferencia reúne dos cosas que antes estaban separadas: formar mentores y
docentes, y replicar el modelo en otros territorios. Es el mismo mecanismo,
sistematizar y enseñar, y su impacto ocurre sobre unidades distintas de las que
atiende Manizales Más directamente, así que no genera doble conteo.

**Capas.** `PRB` problemática · `ACT` actividades · `PRD` productos · `RES`
resultados · `IMP` impacto · `SUP` supuestos · `CTX` contexto. El prefijo del código
siempre coincide con la capa.

**Cifras.** 39 indicadores: 4 de problemática, 8 de actividad, 8 de producto, 9 de
resultado, 5 de impacto, 4 supuestos y 1 referente de contexto. 4 cadenas, 15
programas mapeados (5 de portafolio), 10 instrumentos de recolección, 74 preguntas de
formulario y 22 referencias. Ningún indicador queda sin fuente.

Cada cadena tiene menos impactos que resultados, que es la disciplina de embudo que
la versión anterior no cumplía.

---

## Alcance de esta versión

El documento presenta solo la teoría de cambio. Instrumentos, cobertura, metas, banco
de preguntas, agenda de aprendizaje, intervención mínima viable, hallazgos de
auditoría y análisis de potencia estadística viven en el libro técnico de Excel
`Sistema_MEL_Manizales_Mas.xlsx`, que se genera del mismo modelo.

La información económica del portafolio comercial no está en ninguno de los dos
entregables por ahora. El deck conserva únicamente la marca de qué programas lo
integran.

Cuatro decisiones esperan al comité:

1. Si los cinco enunciados de impacto son los que la institución quiere defender.
2. Si la fusión de transferencia y capacidad en una sola línea es correcta.
3. Si el alcance de "Desarrollo de ecosistema", hoy marcado **en definición**, se
   precisa antes de ofrecerse.
4. Cuál es la lista canónica de programas: el documento tiene 15 y el portal muestra 9.

### El hallazgo que condiciona todo lo demás

Ningún instrumento registraba a los postulantes que no quedan seleccionados. Sin
ellos no hay grupo de comparación, y sin grupo de comparación ninguno de los impactos
de empresas se puede estimar. `INS_10`, el registro de convocatoria, se creó para
cerrar ese vacío y es la pieza que habilita todo lo demás.

Hay además una tensión estratégica: la línea de talento es la única con evaluación
prospectiva viable, y es la que no se vende. La de empresas concentra el portafolio y
es la que más lejos está de poder demostrar un efecto con una sola cohorte, donde el
efecto mínimo detectable ronda los 23 puntos porcentuales en ventas. La salida de
corto plazo es la evaluación retrospectiva de las cohortes 2013 a 2024 cruzadas con
RUES y PILA: con el conjunto de empresas acompañadas por los programas de esta línea,
cercano a 500, la precisión baja a unos 4 puntos.

---

## Identidad visual

| Elemento | Valor |
|---|---|
| Azul institucional | `#104380`, con `#0B2E5C` para degradados |
| Verde lima | `#CDDD00` |
| Azul claro | `#5BB7E7` y cian `#27B9E1` |
| Tipografía | Poppins en tres pesos, subconjuntada e incrustada |

Las capas usan una progresión de azules de la problemática al impacto. El lima queda
para la interacción y para el portafolio. Los tonos de texto sobre fondo claro se
oscurecieron para cumplir el contraste mínimo de WCAG 2.1 nivel AA. El documento
respeta `prefers-reduced-motion` e imprime en horizontal.

---

## Principios

1. **Impacto solo con comparación.** Sin grupo de comparación es seguimiento.
2. **Ningún indicador huérfano.** Todo indicador necesita una fuente que lo alimente.
3. **Metas ancladas.** Una meta de resultado o impacto necesita línea base y
   referencia externa verificada.
4. **Sin riesgo moral.** Ningún indicador puede mejorar porque el desempeño propio
   empeore, ni depender de una cifra que reporta quien es evaluado por ella.
5. **Sin datos personales.** El repositorio no aloja bases con identificadores.

---

## Fuentes

- [Portal de Manizales Más](https://manizalesmas.com.co/)
- [Cámara de Comercio de Manizales por Caldas, Dinámica Empresarial de Caldas 2025](https://estudios.ccmpc.org.co/wp-content/uploads/Din.-Empresarial-Caldas-2025.pdf)
- [Confecámaras, supervivencia empresarial en Colombia](https://confecamaras.org.co/wp-content/uploads/2024/01/estudio-supervivencia-mayo-9.pdf)
- [Confecámaras, supervivencia y crecimiento de las empresas](https://confecamaras.org.co/wp-content/uploads/2024/01/cartilla17.pdf)
- [DANE, Gran Encuesta Integrada de Hogares 2026](https://microdatos.dane.gov.co/index.php/catalog/900)
- [DANE, Registro Estadístico de Relaciones Laborales](https://www.dane.gov.co/files/operaciones/RELAB/pres-RELAB-abr2025.pdf)
- [Manual Eurostat y OCDE de demografía empresarial](https://ec.europa.eu/eurostat/web/business-demography/information-data)
- [Impact Evaluation in Practice, Banco Mundial y BID](https://www.worldbank.org/en/programs/sief-trust-fund/publication/impact-evaluation-in-practice)

El listado completo está en la sección de referencias del documento. Las fuentes
externas se verificaron el 29 de julio de 2026.
