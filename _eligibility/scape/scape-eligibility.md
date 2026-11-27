---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    - CO
    - CL
    text: Sections for Scape México, Scape Colombia ("Términos y condiciones Scape Colombia") and Scape Chile ("Términos y condiciones Scape Chile").
  entity_types:
  - text: Podrán utilizar Servicios ofrecidos por Scape los Usuarios Finales como persona capaz
    type: individual
  minimum_age:
    text: El "Usuario" garantiza poseer la edad mínima necesaria de18 (dieciocho) años para utilizar los "Servicios" de la "Aplicación".
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: Sea falso o engañoso.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Scape podrá rechazar una solicitud de registro o cancelar un registro en la Plataforma o la App, sin que lo anterior genere derecho a resarcimiento de ningún tipo.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Scape
provenance_date: '2026-11-10'
provider_name: Scape
provider_slug: scape
slug: scape-eligibility
source_date: '2026-11-10'
source_filename: scape-eligibility.yml
source_heading: Eligibility
source_page: https://www.scapewellness.com/terms-conditions-general
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scape\naid: scape\nurl: https://www.scapewellness.com/terms-conditions-general\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - MX\n  - CO\n  - CL\n  excluded: []\n  text: Sections for Scape México, Scape Colombia (\"Términos y condiciones Scape Colombia\") and Scape Chile (\"Términos\n    y condiciones Scape Chile\").\nentity_types:\n- type: individual\n  text: Podrán utilizar Servicios ofrecidos por Scape los Usuarios Finales como persona capaz\nrestricted_uses:\n- summary: Prohibited content\n  text: Sea falso o engañoso.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Scape podrá rechazar una solicitud de registro o cancelar un registro en la Plataforma o la App, sin que\n    lo anterior genere derecho a resarcimiento de ningún tipo.\nminimum_age:\n  value: '18'\n  text: El \"Usuario\" garantiza poseer la edad mínima necesaria de18 (dieciocho) años para utilizar los \"Servicios\"\n    de la \"Aplicación\".\n"
source_yaml_url: https://artifacts.apis.io/scape/eligibility/scape-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Scape's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wellness
- Spa
- On-Demand
- Massage
- Health
- Consumer
- Latin America
- Mobile App
- Booking
---
