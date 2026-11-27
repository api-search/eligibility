---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated by us in the United States.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health information
    text: transmit, receive or store Protected Health Information (as defined by the Health Insurance Portability and Accountability Act)
  - summary: No emergency services access
    text: The Services accordingly do not provide access to emergency services or emergency services providers
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In certain circumstances, we may require you to submit supplemental information for the purposes of verification (“Enhanced Verification”) before allowing or continuing your access to the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beside
provenance_date: '2026-11-09'
provider_name: Beside
provider_slug: beside
slug: beside-eligibility
source_date: '2026-11-09'
source_filename: beside-eligibility.yml
source_heading: Eligibility
source_page: https://www.beside.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beside\naid: beside\nurl: https://www.beside.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated by us in the United States.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity\nrestricted_uses:\n- summary: No protected health information\n  text: transmit, receive or store Protected Health Information (as defined by the Health Insurance Portability\n    and Accountability Act)\n- summary: No emergency services access\n  text: The Services accordingly\
  \ do not provide access to emergency services or emergency services providers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In certain circumstances, we may require you to submit supplemental information for the purposes of verification\n    (“Enhanced Verification”) before allowing or continuing your access to the Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beside/eligibility/beside-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Beside's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software
- Communications
- Voice
- Artificial Intelligence
- Receptionist
- Telephony
- Small Business
- CRM
---
