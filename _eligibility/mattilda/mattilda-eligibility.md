---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: El Sitio Web está dirigido principalmente a instituciones educativas privadas y personas relacionadas con ellas residentes en México. Mattilda no garantiza que el Sitio Web cumpla con legislaciones de otros países.
  entity_types:
  - text: Los Servicios descritos en la Sección V solo pueden ser contratados por instituciones educativas privadas con personalidad jurídica propia (personas físicas o morales).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use must be lawful and per Mexican law
    text: Hacer un uso lícito, diligente y correcto del Sitio Web, respetando la legislación mexicana vigente, la moral, el orden público y los derechos de terceros.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mattilda
provenance_date: '2026-11-10'
provider_name: Mattilda
provider_slug: mattilda
slug: mattilda-eligibility
source_date: '2026-11-10'
source_filename: mattilda-eligibility.yml
source_heading: Eligibility
source_page: https://mattilda.io/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mattilda\naid: mattilda\nurl: https://mattilda.io/terminos-y-condiciones/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: El Sitio Web está dirigido principalmente a instituciones educativas privadas y personas relacionadas con\n    ellas residentes en México. Mattilda no garantiza que el Sitio Web cumpla con legislaciones de otros países.\nentity_types:\n- type: business\n  text: Los Servicios descritos en la Sección V solo pueden ser contratados por instituciones educativas privadas\n    con personalidad jurídica propia (personas físicas o morales).\nrestricted_uses:\n- summary:\
  \ Use must be lawful and per Mexican law\n  text: Hacer un uso lícito, diligente y correcto del Sitio Web, respetando la legislación mexicana vigente, la\n    moral, el orden público y los derechos de terceros.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mattilda/eligibility/mattilda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Mattilda's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Education
- EdTech
- Tuition
- Latin America
- Mexico
---
