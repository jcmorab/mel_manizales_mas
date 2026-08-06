# Teoría de cambio de Manizales Más

Modelo conceptual de la teoría de cambio de la alianza Manizales Más, publicado como
un documento web interactivo de un solo archivo.

**Versión 2.2** · Julio de 2026

---

## Contenido

```
mel_manizales_mas/
├── index.html      Documento interactivo, autocontenido
├── README.md
└── .gitignore
```

`index.html` no depende de ningún recurso externo. El CSS, el JavaScript, el modelo
completo y el logo institucional en base64 están embebidos en el archivo. Se puede
abrir con doble clic, enviar por correo o publicar en cualquier servidor estático.
Los únicos enlaces salientes son las referencias bibliográficas, que abren en una
pestaña nueva.

---

## Publicar en GitHub Pages

1. Cree el repositorio en GitHub y suba los tres archivos.

   ```bash
   git init
   git add .
   git commit -m "Teoría de cambio de Manizales Más, versión 2.2"
   git branch -M main
   git remote add origin https://github.com/USUARIO/mel_manizales_mas.git
   git push -u origin main
   ```

2. En el repositorio, vaya a **Settings → Pages**.
3. En **Source** elija **Deploy from a branch**.
4. En **Branch** elija `main` y la carpeta `/ (root)`. Guarde.
5. Espere entre uno y dos minutos. La URL será
   `https://USUARIO.github.io/mel_manizales_mas/`.

Si la página aparece en blanco, la causa casi siempre es una de estas tres:

- El commit no incluyó `index.html`. Verifíquelo con `git ls-files`, que debe
  listarlo.
- La rama o la carpeta seleccionada en Pages no es la que contiene el archivo.
- El despliegue todavía no terminó. La pestaña **Actions** del repositorio muestra
  el estado.

El documento incluye una red de seguridad: si el navegador no logra ejecutar el
JavaScript, muestra todas las secciones desplegadas y un aviso con el detalle del
error, en lugar de quedar en blanco.

---

## Cómo se lee el documento

Seis secciones, navegables desde el menú lateral o con las flechas del teclado.

| Sección | Qué contiene |
|---|---|
| Modelo institucional | El impacto que persigue la alianza y las cinco líneas de trabajo |
| Teoría de cambio | Todos los elementos ordenados de la problemática al impacto |
| Cadenas causales | Las cinco secuencias, cada una con su hipótesis y sus supuestos |
| Programas | Mapa bidireccional entre los 14 programas y los elementos de la teoría |
| Indicadores | La batería de medición, con resumen y filtros |
| Referencias | Las 23 fuentes, con lo que aporta cada una y su fecha de verificación |

### Distinción entre enunciado e indicador

Un elemento de la teoría de cambio y un indicador no son la misma cosa. El elemento
se enuncia como el cambio que se espera; el indicador es la forma de medirlo. El
diagrama muestra el enunciado y la ficha de cada tarjeta revela el indicador.

| Elemento | Cambio esperado | Indicador |
|---|---|---|
| `IMP_1` | Aumento de las ventas de las empresas del ecosistema | Efecto sobre las ventas reales a 24 meses |
| `RES_3` | Los jóvenes avanzan hacia el empleo formal o hacia un emprendimiento activo | Proporción de participantes con transición verificada |
| `HAB_5` | Lo que reportamos está respaldado por evidencia, no por declaración | Resultados con evidencia documental sobre resultados reportados |

---

## El modelo

Cuatro líneas sustantivas, cada una con impacto propio, y una capa habilitante que
se declara deliberadamente sin impacto porque su efecto ya está contabilizado en las
otras cadenas. Presentarla con impacto propio sería contar dos veces lo mismo.

| Código | Línea | Impacto propio |
|---|---|---|
| `EMP` | Empresas y emprendimientos | Ventas, empleo formal y supervivencia |
| `TAL` | Talento y empleabilidad | Acceso de los jóvenes a empleo formal |
| `ECO` | Ecosistema y movilización | Acceso de las empresas a financiación y contratos |
| `REP` | Réplica y transferencia | El de `EMP` y `TAL` medido en el territorio replicador |
| `TRA` | Capacidad habilitante | Ninguno, por decisión explícita |

**Capas y códigos.** `PRB` problemática · `ACT` actividades · `PRD` productos ·
`RES` resultados · `IMP` impacto · `CTX` contexto territorial · `SUP` supuestos ·
`HAB` habilitadores de evidencia. El prefijo del código siempre coincide con la capa.

**Cifras.** 42 elementos en la teoría, de los cuales 35 llevan indicador propio.
El núcleo de rendición de cuentas son 19 indicadores de producto, resultado e
impacto. 5 cadenas causales y 14 programas mapeados.

Las siete actividades compartían una fórmula idéntica de cumplimiento de hitos, de
modo que se consolidaron en un solo indicador con desglose obligatorio por
actividad, línea y programa. La información se conserva completa y la batería deja
de cargar seis medidas redundantes.

---

## Alcance de esta versión

El documento presenta únicamente la teoría de cambio. Instrumentos de levantamiento,
matriz de cobertura, metas, banco de preguntas, agenda de aprendizaje, intervención
mínima viable, hallazgos de auditoría y análisis de potencia estadística existen en
el libro técnico de Excel que acompaña al proyecto, pero no se presentan aquí por una
razón deliberada: primero hay que estar seguros de la teoría de cambio.

Tres decisiones esperan validación del comité:

1. Si los cinco enunciados de impacto son los que la institución quiere defender.
2. Si la capa habilitante debe seguir declarada sin impacto propio.
3. Si la línea de réplica se activa ahora o queda enunciada para un ciclo posterior.

---

## Principios que sostienen el modelo

1. **Impacto solo con comparación.** Un dato sin grupo de comparación se reporta
   como seguimiento, nunca como impacto.
2. **Ningún indicador huérfano.** Todo indicador debe tener al menos una fuente que
   lo alimente.
3. **Metas ancladas.** Una meta de resultado o de impacto necesita línea base y una
   referencia externa verificada. Una cifra sin sustento produce una falsa sensación
   de precisión.
4. **Sin datos personales.** Este repositorio no aloja bases con identificadores de
   participantes ni cifras empresariales. El `.gitignore` bloquea los formatos
   habituales, pero la responsabilidad es de quien hace el commit.

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

El listado completo, con lo que aporta cada fuente y su fecha de verificación, está
en la sección de referencias del propio documento.
