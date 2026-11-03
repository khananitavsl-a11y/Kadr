# Модели

Исходники лежат здесь; рисунки в работе `docs/Team01_Glavy_1-3.pdf` — их версии, оформленные для печати (папка `print/`), готовые картинки — в `png/`.

## Глава 2
| Файл | Рисунок в работе |
|---|---|
| `scope.png` | 2.1 — Границы версии 1.0 |
| `stakeholder_matrix.drawio`, `stakeholder_matrix.png` | 2.2 — Матрица влияния стейкхолдеров |
| `customer_journey.drawio`, `customer_journey.png` | 2.3 — Карта пути владельца бизнеса |
| `moscow.png`, `traceability_chain.png` | Схемы этапа 2 (приоритеты MoSCoW и цепочка трассируемости) |

## Глава 3
| Исходник | Версия для печати (`print/`) | Рисунок в работе |
|---|---|---|
| `process_as_is.bpmn`, `process_to_be.bpmn` | `bpmn_as_is_print.bpmn`, `bpmn_to_be_print.bpmn` | 3.1, 3.2 — процесс «как есть» и «как будет» (BPMN 2.0) |
| `use_case.svg` | — | 3.3 — варианты использования |
| `activity_payment.mmd`, `activity_acceptance.mmd` | `activity_payment.dot`, `activity_acceptance.dot` | 3.4 — деятельность: оплата и приёмка |
| `sequence_payment.mmd` | `sequence_payment.svg` | 3.5 — последовательность «Оплата заказа» |
| `class_diagram.mmd` | `class_diagram.dot` | 3.6 — диаграмма классов (17 классов) |
| `db_schema.dbml`, `db_schema.mmd` | `db_schema_ru.html` | 3.7 — схема базы данных (17 таблиц, 24 связи) |
| `architecture.html` | `architecture.html` | 3.8 — архитектура: пять уровней |
| `modules.html` | — | 3.9 — связи модулей М1–М8 |

Те же схемы в формате draw.io — в папке `drawio/`. Как открыть:
- `.bpmn` — [demo.bpmn.io](https://demo.bpmn.io) или Camunda Modeler;
- `.mmd` — [mermaid.live](https://mermaid.live);
- `.dbml` — [dbdiagram.io](https://dbdiagram.io);
- `.dot` — Graphviz (`dot -Tpng file.dot -o file.png`);
- `.drawio` — [app.diagrams.net](https://app.diagrams.net): «Файл → Открыть с устройства»;
- `.html`, `.svg` — любой браузер.
