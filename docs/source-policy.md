# Source Policy

Last checked: 2026-06-17.

Every row or factual map claim should include:

- `source_url`
- `source_title`
- `date_checked`
- `status`
- `confidence`

## Status Values

| Status | Meaning |
| --- | --- |
| `confirmed_public` | Supported by a public source checked by Limes. |
| `needs_verification` | Useful but not confirmed by reviewed public sources. |
| `stale` | Source exists but may be outdated or superseded. |
| `contact_pending` | A question has actually been sent and is awaiting response. |
| `deprecated` | Kept only for historical context; do not rely on it. |

Do not infer missing host organisations, contacts, capacities, partnerships, or access rights. Use `unknown` until confirmed by a public source or a logged public-safe contact.
