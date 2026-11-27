---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    - CO
    - CR
    - EC
    - SV
    - GT
    - HN
    - MX
    - NI
    - PE
    - DO
    text: Destination Send to ---- Brazil Colombia Costa Rica Ecuador El Salvador Guatemala Honduras Mexico Nicaragua Peru Dominican Republic
  entity_types:
  - text: By registering with Félix, or by using the Services, you agree to be bound by these Terms and affirm that you are at least eighteen (18) years of age
    type: individual
  - text: Usted tiene derecho a cancelar una Transferencia realizada con fines comerciales o empresariales
    type: business
  minimum_age:
    text: affirm that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Own account only; one registration
    text: Solo puede registrarse en Félix una vez, salvo que aprobemos expresamente el uso de varias cuentas de WhatsApp.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Si utiliza ciertos Servicios, la ley federal exige que verifiquemos parte de su información.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Felix
provenance_date: '2026-11-09'
provider_name: Felix
provider_slug: felix
slug: felix-eligibility
source_date: '2026-11-09'
source_filename: felix-eligibility.yml
source_heading: Eligibility
source_page: https://www.felixpago.com/en/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Felix\naid: felix\nurl: https://www.felixpago.com/en/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - BR\n  - CO\n  - CR\n  - EC\n  - SV\n  - GT\n  - HN\n  - MX\n  - NI\n  - PE\n  - DO\n  excluded: []\n  text: Destination Send to ---- Brazil Colombia Costa Rica Ecuador El Salvador Guatemala Honduras Mexico Nicaragua\n    Peru Dominican Republic\nentity_types:\n- type: individual\n  text: By registering with Félix, or by using the Services, you agree to be bound by these Terms and affirm that\n    you are at least eighteen (18) years of age\n- type: business\n  text:\
  \ Usted tiene derecho a cancelar una Transferencia realizada con fines comerciales o empresariales\nrestricted_uses:\n- summary: Own account only; one registration\n  text: Solo puede registrarse en Félix una vez, salvo que aprobemos expresamente el uso de varias cuentas de WhatsApp.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Si utiliza ciertos Servicios, la ley federal exige que verifiquemos parte de su información.\nminimum_age:\n  value: '18'\n  text: affirm that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/felix/eligibility/felix-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Felix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Remittances
- Money Transfer
- Latin America
- Financial Services
---
