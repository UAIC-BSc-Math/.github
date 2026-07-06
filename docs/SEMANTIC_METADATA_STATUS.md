# Semantic Metadata Status

The course repositories use a seed semantic model built from machine-readable JSON files.

## Metadata files

- `data/course.json`
- `data/concept.json`
- `data/relation.json`
- `data/curricula.json`
- `data/year.json`
- `data/unit.json`
- `data/lesson.json`
- `data/homework.json`
- `data/seminary.json`
- `data/material.json`
- `data/source.json`
- `data/curriculum_plan.json`

## v0.2 scaffold status

The archive broadly carries the v0.2 scaffold layer, which provides identity, file indexing, and conservative concept scaffolding.

## v0.3 enriched status

Selected important courses carry a richer v0.3 semantic layer with stronger concept, relation, and planning evidence.

## Metadata-version detection issue

The current repository map still reports `0.2.0` broadly because the course-level version field has not yet been normalized across the enriched repositories. The enriched course folders should be treated as semantically richer than that coarse flag suggests.

## Selected enriched courses

Examples of the enriched set include:

- `MF2CAF Special chapters on functional analysis`
- `M_6AnF Functional analysis`
- `M_1AlL Linear algebra`
- `M_2AlC Algorithms and complexity`
- `MF2EDP Partial differential equations`
- `M_3ALN Numerical linear algebra. Math software`
- `MF1GeR Differential geometry. Riemannian manifolds`

## Scaffold-only courses

Most repositories still follow the conservative scaffold pattern and should be reviewed manually before being treated as full semantic imports.

## Manual-review courses

- `A2CVC Variational calculus and optimal control`
- `A4RNe Neural networks`
- `M_1Ge1 Geometry I`

## Future fix

- add `metadata_manifest.json` per repository, or
- update `data/course.json` metadata detection from the full set of `data/*.json` files instead of a single version field.
