---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: The Website is intended solely for visitors located within the United States and Canada.
  entity_types:
  - text: The Website is offered and made available to users who are at least eighteen (18) years old.
    type: individual
  - text: 'If you are an entity, organization, or company, then: (i) the individual accepting these Terms of Use on your behalf represents and warrants that they have authority to bind you to these Terms of Use'
    type: business
  minimum_age:
    text: at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use
    text: You may access and use the Website for your personal, non-commercial use only.
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
name: Dcbel
provenance_date: '2026-11-09'
provider_name: Dcbel
provider_slug: dcbel
slug: dcbel-eligibility
source_date: '2026-11-09'
source_filename: dcbel-eligibility.yml
source_heading: Eligibility
source_page: https://www.dcbel.energy/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dcbel\naid: dcbel\nurl: https://www.dcbel.energy/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: The Website is intended solely for visitors located within the United States and Canada.\nentity_types:\n- type: individual\n  text: The Website is offered and made available to users who are at least eighteen (18) years old.\n- type: business\n  text: 'If you are an entity, organization, or company, then: (i) the individual accepting these Terms of Use on\n    your behalf represents and warrants that they have authority to bind you to these Terms of\
  \ Use'\nrestricted_uses:\n- summary: Non-commercial personal use\n  text: You may access and use the Website for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/dcbel/eligibility/dcbel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Dcbel's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Cleantech
- Home Energy
- Solar
- Battery
---
