# Health Mastery Learning System 2.0

A modular, portable Agent Skill for learning health and biomedical science from beginner to advanced level.

## What it does

- Builds a progressive curriculum across Levels 0–10.
- Teaches anatomy, physiology, mechanisms, pathophysiology, measurement, interventions, and system integration.
- Uses visual learning, active recall, adaptive quizzes, and mastery checks.
- Supports scientific research, journal appraisal, and health-claim evaluation.
- Tracks learning with a portable progress record.
- Includes medical-safety boundaries and evidence-calibration rules.

## Repository structure

```text
health-mastery-learning/
├── SKILL.md
├── README.md
├── LICENSE
└── references/
    ├── curriculum-map.md
    ├── lesson-design.md
    ├── evidence-and-research.md
    └── progress-and-assessment.md
```

## Use

Place this skill in the skills directory supported by your agent platform, or paste `SKILL.md` into an agent's skill/instructions interface. Platform-specific installation procedures differ.

Start with:

> MULAI sistem pencernaan

Other commands include `LANJUT`, `KUPAS TUNTAS`, `VISUAL`, `DIAGRAM`, `QUIZ`, `UJI MASTERY`, `ANALISIS JURNAL`, `MITOS VS FAKTA`, and `EXPORT PROGRESS`.

## Compatibility

The skill uses plain Markdown and YAML frontmatter. It is designed to be portable across LLM platforms, but each platform may require a different installation wrapper or metadata convention. Web research is optional; the model must not claim to have verified current evidence when it has not browsed.

## Versioning

- **2.0.0** — modularized and expanded learning workflow, curriculum, research methods, safety boundaries, and portable progress tracking.

## Safety

Educational use only. This skill does not replace clinical assessment, diagnosis, or treatment by a qualified healthcare professional.
