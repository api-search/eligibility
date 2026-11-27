---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AR
    - BR
    - CO
    - CR
    - EC
    - DO
    - UY
    text: El Servicio se ofrece en Argentina, en Brasil, en Colombia, en Costa Rica, en Ecuador, en la República Dominicana y en Uruguay.
  entity_types:
  - text: Contratas el Servicio para el ejercicio de tu actividad profesional o la de tu despacho, no como consumidor final
    type: business
  minimum_age:
    text: tienes al menos dieciocho (18) años
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: que te pedimos antes de contratar cualquier plan de pago
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Custodio Legal
provenance_date: '2026-11-09'
provider_name: Custodio Legal
provider_slug: custodio-legal
slug: custodio-legal-eligibility
source_date: '2026-11-09'
source_filename: custodio-legal-eligibility.yml
source_heading: Eligibility
source_page: https://custodio.legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Custodio Legal\naid: custodio-legal\nurl: https://custodio.legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AR\n  - BR\n  - CO\n  - CR\n  - EC\n  - DO\n  - UY\n  excluded: []\n  text: El Servicio se ofrece en Argentina, en Brasil, en Colombia, en Costa Rica, en Ecuador, en la República Dominicana\n    y en Uruguay.\nentity_types:\n- type: business\n  text: Contratas el Servicio para el ejercicio de tu actividad profesional o la de tu despacho, no como consumidor\n    final\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: que\
  \ te pedimos antes de contratar cualquier plan de pago\nminimum_age:\n  value: '18'\n  text: tienes al menos dieciocho (18) años\n"
source_yaml_url: https://artifacts.apis.io/custodio-legal/eligibility/custodio-legal-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Custodio Legal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Practice Management
- Judicial Monitoring
- Artificial Intelligence
- MCP
- Latin America
- Colombia
---
