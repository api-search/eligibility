---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - MX
    text: Esta App es administrada en los Estados Unidos Mexicanos, y está dirigido a Usuarios en México
  entity_types:
  - text: a personas físicas, morales y toda clase de negocios permitidos por la ley
    type: individual
  - text: a personas físicas, morales y toda clase de negocios permitidos por la ley
    type: business
  minimum_age:
    text: Tienes por lo menos 18 años de edad
    value: '18'
  restricted_uses:
  - summary: Legitimate purposes only
    text: Utilizarás esta App de acuerdo con estos Términos y Condiciones y con fines legítimos para ti u otra persona para la cual estás legalmente autorizado a actuar.
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
name: Custodian
provenance_date: '2026-11-09'
provider_name: Custodian
provider_slug: custodian
slug: custodian-eligibility
source_date: '2026-11-09'
source_filename: custodian-eligibility.yml
source_heading: Eligibility
source_page: https://getcustodian.com/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Custodian\naid: custodian\nurl: https://getcustodian.com/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MX\n  excluded: []\n  text: Esta App es administrada en los Estados Unidos Mexicanos, y está dirigido a Usuarios en México\nentity_types:\n- type: individual\n  text: a personas físicas, morales y toda clase de negocios permitidos por la ley\n- type: business\n  text: a personas físicas, morales y toda clase de negocios permitidos por la ley\nrestricted_uses:\n- summary: Legitimate purposes only\n  text: Utilizarás esta App de acuerdo con estos Términos y Condiciones y con fines\
  \ legítimos para ti u otra persona\n    para la cual estás legalmente autorizado a actuar.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Tienes por lo menos 18 años de edad\n"
source_yaml_url: https://artifacts.apis.io/custodian/eligibility/custodian-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Custodian's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Claims Management
- Automotive
- Mobile App
- Mexico
- Consumer
---
