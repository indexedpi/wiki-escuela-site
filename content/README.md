# 🏫 Wiki Escolar — Pulpo

**Colegio:** Casa Salesiana San José (Sanjo) — Rosario
**Curso:** 6º 1ª — Técnico en Informática Profesional y Personal
**Año:** 2026

---

## 📁 Estructura

```
wiki/
├── diario/           → Bitácora diaria (1 archivo por día de clase)
│   ├── 03-march/
│   ├── 04-april/
│   └── 05-may/
├── materias/         → Notas de clase por materia
│   ├── redes/
│   ├── programacion-ii/
│   ├── ...
│   └── README.md (índice general)
├── auditorias/       → Auditorías automáticas (Classroom + mail)
└── README.md         ← Estás acá
```

## 📚 Materias

| Materia | Docente | Clases |
|---|---|---|
| Redes | Volonté, H (0) | 23 |
| Programación II | Martín, J F (1) | 22 |
| Matemática Aplicada | Vernazza, C (1) | 15 |
| Proyecto Tecnológico | De Miguel, A (-2) | 14 |
| Formación Cristiana | Oliva, M (0) | 12 |
| Formación Ética | Fasciolo, P (-2) | 12 |
| Hardware IV | Tonella, F (2) | 12 |
| Inglés Técnico | Alberich, Y (1) | 12 |
| Lengua | Rodrigo, G (0) | 12 |
| Prácticas Profesionalizantes | Bidart/Tonella (-1/2) | 12 |
| Software IV | De Miguel, A (-2) | 11 |
| Org. y Gestión Comercial | Zampol, L (-1) | 11 |

*Nivel de comportamiento: -2(ambiente libre) -1(relajado) 0(normal) 1(estricto) 2(riguroso)*

## 🗓️ Calendario 2026

- **Inicio:** 2 de marzo
- **Días de clase hasta hoy:** 57
- **Receso invernal:** 6-17 de julio
- **Feriados cursados:** Mar 23-24, Abr 2-3, May 1, May 25

## 🤖 Automatización

El cron de Hermes Escuela corre auditoría diaria (6:00 y 13:00) que escanea Gmail escolar y escribe en `auditorias/`.
