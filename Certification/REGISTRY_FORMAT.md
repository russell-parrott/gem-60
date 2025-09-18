# GEM-60 Exposure Registry — Listing Format

> All certified systems must be listed in a consistent, verifiable format.
> Listings reflect proof of structural governability under live conditions—not organisational endorsement.

---

## Required Fields

| Field Name       | Description                                                                |
| ---------------- | -------------------------------------------------------------------------- |
| `System Name`    | Public or internal name of the system under test                           |
| `Organisation`   | Legal entity that owns or operates the system                              |
| `Scope Summary`  | Concise description of tested system boundaries and role                   |
| `Observer`       | Full name of authorised structural observer present at the drill           |
| `Result`         | ✅ Pass only—partial or invalid results are not listed                      |
| `Date Certified` | Date the drill was passed and verified                                     |
| `Expiry Date`    | 12 months after certification date, or sooner if system materially changes |

---

## Example Listing

```markdown
| System Name       | Organisation         | Scope Summary                          | Observer             | Result  | Date Certified | Expiry Date  |
|-------------------|----------------------|----------------------------------------|----------------------|---------|----------------|--------------|
| *ClassifyX API*   | Confidential (APAC)  | Decision endpoint + refusal pathways   | [Redacted]           | ✅ Pass | 2025-09-17     | 2026-09-17   |
```

---

## Validation Rules

* Only systems that passed all four GEM-60 structural tests are eligible
* Listings must correspond exactly to the scope declared at drill time
* No aggregated systems, stack claims, or platform-level certification allowed
* Observers must be pre-authorised under `OBSERVER_AGREEMENT.md`

---

To submit a new registry entry, email your signed `RECORDING_TEMPLATE.md` to:
📩 **[parrott.russell@gmail.com](mailto:parrott.russell@gmail.com)**
