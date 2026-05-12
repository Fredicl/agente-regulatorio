# Aprendizajes del Agente Regulatorio

## Feedback

_Preferencias y correcciones del usuario — el agente las aplica en cada ejecución._

| Fecha | Feedback |
|-------|----------|
| 2026-05-12 | Solo documentos oficiales primarios (boe.es, cnmc.es, ree.es, miteco.gob.es). No noticias. |
| 2026-05-12 | Validar fecha de publicación del documento antes de incluirlo. Solo últimos 7 días. |
| 2026-05-12 | Incluir enlace directo al documento oficial, nunca a una noticia sobre él. |

---

## Temas ya cubiertos

| Fecha | Fuente | Descripción del tema | Referencia |
|-------|--------|---------------------|------------|
| 2026-05-12 | MITECO | Cuatro consultas públicas RDL 7/2026: ZAR, excelencia social, beneficios territoriales, biometano (cierre 15 mayo) | k-817, k-819 |
| 2026-05-12 | BOE | RDL 7/2026: medidas almacenamiento — derogación garantías, devolución desde 22 mayo | BOE-A-2026-6544 |
| 2026-05-12 | BOE | Instalación híbrida Olinda 110,53 MW BESS+FV, Lightsource bp, Castellón | BOE-B-2026-14192 |
| 2026-05-12 | BOE | BESS Delphinus+Draco 36 MW + FV 91,2 MW, Solaria, Zamora | BOE-B-2026-14191 |
| 2026-05-12 | BOE | Hibridación Los Arcos 26,74 MW BESS + FV 43,9 MW, Teruel | BOE-B-2026-14564 |
| 2026-05-12 | BOE | RD 88/2026 Reglamento suministro, comercialización y agregación — agregadores independientes | BOE-A-2026-3212 |
| 2026-05-12 | BOE | Precio interrumpibilidad Q2 2026: 43,67 €/MWh territorios no peninsulares | BOE-A-2026-9789 |
| 2026-05-12 | CNMC | Consulta patrones funcionamiento almacenamiento acceso redes distribución | cnmc.es/consultas-publicas |
| 2026-05-12 | CNMC | Mapas capacidad redes eléctricas — publicación mensual desde feb 2026 | cnmc.es/prensa/mapas-capacidad-20260415 |
| 2026-05-12 | REE | Informe Sistema Eléctrico 2025: renovables 68,7%, +11,6 GW nuevos, demanda +2,8% | sistemaelectrico-ree.es |
| 2026-05-12 | REE | 1.725 MW respuesta activa demanda (SRAD) H1 2026 | ree.es/sala-prensa |
| 2026-05-12 | BOE/EU | Recomendación UE 2026/1008 condiciones contractuales contratos suministro | DOUE-L-2026-80666 |
| 2026-05-12 | EU | Prohibición financiación BESS inversores países alto riesgo (ext. desde FV a BESS) | Decisión CE mayo 2026 |
| 2026-05-12 | EU/BOE | Comunicación CE áreas infraestructura red y almacenamiento (Directiva renovables art.15 sexies) | DOUE-Z-2026-70003 |

---

## Errores registrados

_El agente añade aquí cada error encontrado durante la ejecución para mejorar las siguientes._

| Fecha | Fuente/URL | Tipo de error | Acción tomada |
|-------|------------|---------------|---------------|
| 2026-05-12 | boe.es datosabiertos API | HTTP 403 desde entorno cloud | Cambiado a RSS oficial (boe.php?s=1/3/5) |
| 2026-05-12 | cnmc.es, ree.es, miteco.gob.es | HTTP 403 en WebFetch directo | Usar WebSearch + WebFetch selectivo solo en URLs prometedoras |

---

## Patrones detectados

_Observaciones del agente sobre frecuencia de publicación, temas en auge, etc._

| Fecha | Patrón |
|-------|--------|
| 2026-05-12 | BOE MUY ACTIVO en proyectos BESS hibridación: semana 5-11 mayo = 4 proyectos, 116 MW BESS + 136 MW FV. El ritmo de hibridación es elevado (decenas de proyectos/mes). |
| 2026-05-12 | MITECO tiene 4 consultas abiertas simultáneas derivadas del RDL 7/2026 (ZAR, excelencia, beneficios, biometano) — plazo muy corto (15 mayo). Patrón de regulación secundaria derivada de RDL urgente. |
| 2026-05-12 | Almacenamiento es el tema más activo. Casi todas las semanas hay proyectos BESS/hibridación en información pública. |
| 2026-05-12 | Apagón 28 abril ha generado regulación reactiva: CNMC acelera procedimiento control tensión P.O.7.4, investigaciones de expedientes, tensión institucional CNMC-REE. |
| 2026-05-12 | La API REST del BOE (boe.es/datosabiertos/api/) está bloqueada por el sandbox del agente — usar WebSearch como alternativa. Los sites boe.es y miteco.gob.es devuelven 403 en WebFetch. |
