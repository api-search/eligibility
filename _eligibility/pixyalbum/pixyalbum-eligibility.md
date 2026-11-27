---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Sólo se permitirá el registro de mayores de 18 (dieciocho) años.
    type: individual
  minimum_age:
    text: Sólo se permitirá el registro de mayores de 18 (dieciocho) años.
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: Para cualquier propósito comercial;
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: PIXYALBUM podrá a su único y exclusivo criterio no aceptar los registros de Usuarios, no teniendo la obligación de dar explicación alguna de esta decisión.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pixyalbum
provenance_date: '2026-11-10'
provider_name: Pixyalbum
provider_slug: pixyalbum
slug: pixyalbum-eligibility
source_date: '2026-11-10'
source_filename: pixyalbum-eligibility.yml
source_heading: Eligibility
source_page: https://www.pixyalbum.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pixyalbum\naid: pixyalbum\nurl: https://www.pixyalbum.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Sólo se permitirá el registro de mayores de 18 (dieciocho) años.\nrestricted_uses:\n- summary: Commercial purposes\n  text: Para cualquier propósito comercial;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: PIXYALBUM podrá a su único y exclusivo criterio no aceptar los registros de Usuarios, no teniendo la obligación\n    de dar explicación alguna de esta decisión.\nminimum_age:\n  value: '18'\n\
  \  text: Sólo se permitirá el registro de mayores de 18 (dieciocho) años.\n"
source_yaml_url: https://artifacts.apis.io/pixyalbum/eligibility/pixyalbum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Pixyalbum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Photo Printing
- Photo Books
- Consumer
- E-Commerce
- Printing
- Mexico
- Photography
---
