---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - GB
    served:
    - US
    - CA
    text: Our Products and our Services are currently available for purchase and use primarily in the United States of America (“US”) and Canada, and elsewhere in the world except in the United Kingdom, Economic European Region (“ EER ”), the European Union (“ EU ”) and Switzerland
  entity_types:
  - text: Persons under the age of 18 are not permitted to access or use the Services unless their parent or legal guardian gives written consent
    type: individual
  minimum_age:
    text: Persons under the age of 18 are not permitted to access or use the Services unless their parent or legal guardian gives written consent
    value: '18'
  restricted_uses:
  - summary: Export restriction
    text: you will not knowingly, directly or indirectly, export, re-export, transfer, make available, or release (collectively, “Export”) the Services to any destination, person, entity, or end user outside of the United States
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: KiddoWear
provenance_date: '2026-11-09'
provider_name: KiddoWear
provider_slug: kiddowear
slug: kiddowear-eligibility
source_date: '2026-11-09'
source_filename: kiddowear-eligibility.yml
source_heading: Eligibility
source_page: https://kiddo.health/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KiddoWear\naid: kiddowear\nurl: https://kiddo.health/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded:\n  - GB\n  text: Our Products and our Services are currently available for purchase and use primarily in the United States\n    of America (“US”) and Canada, and elsewhere in the world except in the United Kingdom, Economic European Region\n    (“ EER ”), the European Union (“ EU ”) and Switzerland\nentity_types:\n- type: individual\n  text: Persons under the age of 18 are not permitted to access or use the Services unless their parent or legal\n    guardian gives written consent\n\
  restricted_uses:\n- summary: Export restriction\n  text: you will not knowingly, directly or indirectly, export, re-export, transfer, make available, or release\n    (collectively, “Export”) the Services to any destination, person, entity, or end user outside of the United\n    States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons under the age of 18 are not permitted to access or use the Services unless their parent or legal\n    guardian gives written consent\n"
source_yaml_url: https://artifacts.apis.io/kiddowear/eligibility/kiddowear-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from KiddoWear's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Pediatrics
- Behavioral Health
- Digital Health
- Connected Care
- Remote Patient Monitoring
- Pediatric
- Wearables
- Data
---
