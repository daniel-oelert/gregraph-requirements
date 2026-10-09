# Bootstrap map (temporary)

Provisional design-appendix-A keys to generated GREGraph identifiers
(design §19). Deleted once seeding is complete.

| Key | Identifier | Type | Title |
|---|---|---|---|
| BOOT-001 | RE-N33YEH | goal | Manage requirements as a Git-synchronised DAG |
| BOOT-002 | RE-V86WCG | goal | Tool-owned structure, human-owned prose |
| BOOT-003 | RE-3KVA84 | goal | Make every requirement change visible to dependents |
| BOOT-004 | RE-W6ZR5V | goal | Serve teams of up to 20 engineers without a server |
| BOOT-010 | RE-3YE8G3 | feature | Repository initialisation with shipped templates |
| BOOT-011 | RE-WYA8JY | feature | Document creation from versioned templates |
| BOOT-012 | RE-CQCF1R | feature | Typed, rule-checked, acyclic linking |
| BOOT-013 | RE-3KMQ1Y | feature | Content versioning and link freshness |
| BOOT-014 | RE-15HB08 | feature | Supersession, deprecation, and template migration |
| BOOT-015 | RE-0WHH13 | feature | Change requests outside the graph |
| BOOT-016 | RE-FBA09Y | feature | Glossary outside the graph |
| BOOT-017 | RE-W3D1B7 | feature | Validation as command, hook, and CI check |
| BOOT-018 | RE-DMAWGA | feature | Status and WIP reporting derived from Git |
| BOOT-019 | RE-YQTS3C | feature | Mermaid graph export |
| BOOT-020 | RE-YFEE3Q | feature | Assets owned and versioned by documents |
| BOOT-100 | RE-304X1P | functional-requirement | init creates the layout, templates, config, and hook |
| BOOT-101 | RE-6BT22E | functional-requirement | Identifiers are derived, prefixed, and regenerated on collision |
| BOOT-102 | RE-EH4ZTP | functional-requirement | Identifiers are never reused |
| BOOT-103 | RE-52TXFB | functional-requirement | Documents are stored as Markdown plus JSON sidecar |
| BOOT-104 | RE-QN5QSH | functional-requirement | Cycle-creating links are refused with the cycle path |
| BOOT-105 | RE-6V9J08 | functional-requirement | Kind-rule violations are refused with the rule named |
| BOOT-106 | RE-1033HC | functional-requirement | Directed edges live on the source only |
| BOOT-107 | RE-FMVXC1 | functional-requirement | The pre-commit hook bumps staged changed documents |
| BOOT-108 | RE-BWBF33 | functional-requirement | The pre-commit hook blocks newly outdated links |
| BOOT-109 | RE-5JQ3QE | functional-requirement | sync bumps versions without Git |
| BOOT-110 | RE-VB9DP6 | functional-requirement | check reports the hook's findings without modifying files |
| BOOT-111 | RE-EAZH2B | functional-requirement | link refresh --follow follows supersession chains |
| BOOT-112 | RE-P6K34S | functional-requirement | supersede accepts multiple targets |
| BOOT-113 | RE-SPT65J | functional-requirement | Documents are validated against their pinned template version |
| BOOT-114 | RE-9WB3XD | functional-requirement | Deprecated template versions warn per document |
| BOOT-115 | RE-E51K4R | functional-requirement | Modification after decision warns |
| BOOT-116 | RE-M89QMQ | functional-requirement | Scope entries record base versions |
| BOOT-117 | RE-EGYEV6 | functional-requirement | Glossary terms are slug-identified with usage reports |
| BOOT-118 | RE-3Y2KHH | functional-requirement | validate --strict fails on any warning or error |
| BOOT-119 | RE-5KN0GA | functional-requirement | status reports WIP, drafts, and unbumped modifications |
| BOOT-120 | RE-HJC7PH | functional-requirement | draft and active are derived from the baseline branch |
| BOOT-121 | RE-SMRGJF | functional-requirement | graph emits a styled Mermaid flowchart |
| BOOT-122 | RE-JR0NFT | functional-requirement | Asset changes count as content changes |
| BOOT-123 | RE-HHFDHC | functional-requirement | Missing arguments prompt or fail under --no-input |
| BOOT-124 | RE-B2A308 | functional-requirement | Unlinked identifier mentions warn |
| BOOT-125 | RE-VSNXNW | functional-requirement | Scope drift warns while a change request is open or accepted |
| BOOT-126 | RE-WR1S6W | functional-requirement | origin_cr and introduces are recorded with --cr |
| BOOT-127 | RE-NXSV09 | functional-requirement | Effective change request status comes from the baseline branch |
| BOOT-128 | RE-7426ND | functional-requirement | The hook ignores drift and CR scope changes |
| BOOT-200 | RE-378GGC | non-functional-requirement | Validate 5,000 documents within 5 seconds |
| BOOT-201 | RE-H2Q16N | non-functional-requirement | Only pydantic, jinja2, and markdown-it-py at runtime |
| BOOT-202 | RE-PXBP3C | non-functional-requirement | Byte-identical canonical sidecars |
| BOOT-203 | RE-SDJ080 | non-functional-requirement | Core operations without console I/O |
| BOOT-204 | RE-WSC7DQ | non-functional-requirement | Linux, macOS, and Windows on Python 3.12+ |
| BOOT-205 | RE-S399BD | constraint | No network communication |
| TC-100 | RE-X5V1N6 | test-case | Verify: init creates the layout, templates, config, and hook |
| TC-101 | RE-B32EMX | test-case | Verify: identifiers are derived, prefixed, and regenerated on collision |
| TC-102 | RE-F3BN1Z | test-case | Verify: identifiers are never reused |
| TC-103 | RE-W5R00Y | test-case | Verify: documents are stored as Markdown plus JSON sidecar |
| TC-104 | RE-55P0KR | test-case | Verify: cycle-creating links are refused with the cycle path |
| TC-105 | RE-NA9KW7 | test-case | Verify: kind-rule violations are refused with the rule named |
| TC-106 | RE-PND8HT | test-case | Verify: directed edges live on the source only |
| TC-107 | RE-Z74XH5 | test-case | Verify: the pre-commit hook bumps staged changed documents |
| TC-108 | RE-F9B68D | test-case | Verify: the pre-commit hook blocks newly outdated links |
| TC-109 | RE-TB5FHP | test-case | Verify: sync bumps versions without Git |
| TC-110 | RE-DE2A8Z | test-case | Verify: check reports the hook's findings without modifying files |
| TC-111 | RE-0G4S9X | test-case | Verify: link refresh --follow follows supersession chains |
| TC-112 | RE-9JFG6M | test-case | Verify: supersede accepts multiple targets |
| TC-113 | RE-1585DT | test-case | Verify: documents are validated against their pinned template version |
| TC-114 | RE-DDDN2V | test-case | Verify: deprecated template versions warn per document |
| TC-115 | RE-RAX4QN | test-case | Verify: modification after decision warns |
| TC-116 | RE-AEAQ3K | test-case | Verify: scope entries record base versions |
| TC-117 | RE-WAGRQV | test-case | Verify: glossary terms are slug-identified with usage reports |
| TC-118 | RE-2GX7F3 | test-case | Verify: validate --strict fails on any warning or error |
| TC-119 | RE-ZH109K | test-case | Verify: status reports WIP, drafts, and unbumped modifications |
| TC-120 | RE-ZBCJY6 | test-case | Verify: draft and active are derived from the baseline branch |
| TC-121 | RE-P9Z6BJ | test-case | Verify: graph emits a styled Mermaid flowchart |
| TC-122 | RE-XXWK6R | test-case | Verify: asset changes count as content changes |
| TC-123 | RE-5JAF9N | test-case | Verify: missing arguments prompt or fail under --no-input |
| TC-124 | RE-JRGCDC | test-case | Verify: unlinked identifier mentions warn |
| TC-125 | RE-PSWVZY | test-case | Verify: scope drift warns while a change request is open or accepted |
| TC-126 | RE-FJMW6P | test-case | Verify: origin_cr and introduces are recorded with --cr |
| TC-127 | RE-T0C8C5 | test-case | Verify: effective change request status comes from the baseline branch |
| TC-128 | RE-9R43FR | test-case | Verify: the hook ignores drift and CR scope changes |
