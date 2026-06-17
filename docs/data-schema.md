# Data Schema

Last checked: 2026-06-17.

The CSV files in `data/` are public-source maps. Unknown fields should be written as `unknown`, not guessed.

## Common Source Columns

| Column | Meaning |
| --- | --- |
| `source_url` | Official or primary source URL for the row. |
| `source_title` | Human-readable title of the source. |
| `date_checked` | Date the source was checked, ISO format. |
| `status` | One of the source-policy statuses. |
| `confidence` | `high`, `medium`, or `low` based on source specificity. |

## `data/ai_factories.csv`

| Column | Meaning |
| --- | --- |
| `name` | Public AI Factory name. |
| `country` | Country or main country. |
| `lead_or_host` | Lead or host organisation if confirmed; otherwise `unknown`. |
| `base_system_or_infrastructure` | Supercomputer/system/factory infrastructure if confirmed. |
| `notes` | Short public-safe note. |

## `data/eurohpc_supercomputers.csv`

| Column | Meaning |
| --- | --- |
| `name` | EuroHPC supercomputer name. |
| `country` | Host country. |
| `host` | Hosting entity or operator. |
| `system_class` | `petascale`, `pre-exascale`, `exascale`, or `incoming`. |
| `notable_partitions_or_notes` | Short public-source summary. |

## `data/it4lia_infrastructure.csv`

| Column | Meaning |
| --- | --- |
| `component` | IT4LIA component name. |
| `location` | Publicly stated location. |
| `role` | Role in the IT4LIA compute continuum. |
| `public_specs_or_notes` | Short public-source summary. |
