---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Your Payment Accounts must be held with U.S. financial institutions, be denominated in U.S. Dollars, and all funds must originate in the United States.
  entity_types:
  - text: you are acting solely on behalf of a commercial entity and have the power and authority to enter into this Agreement on behalf of such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No individual or household bill payments
    text: (B) you will not use the Service for individual, household and personal bill payment activities;
  - summary: Not on OFAC SDN list
    text: (E) you are not now and have never been on the Office of Foreign Assets Control (OFAC) Specially Designated Nationals list;
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
name: CoreChain Technologies
provenance_date: '2026-11-09'
provider_name: CoreChain Technologies
provider_slug: corechain-technologies
slug: corechain-technologies-eligibility
source_date: '2026-11-09'
source_filename: corechain-technologies-eligibility.yml
source_heading: Eligibility
source_page: https://corechain.tech/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoreChain Technologies\naid: corechain-technologies\nurl: https://corechain.tech/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Your Payment Accounts must be held with U.S. financial institutions, be denominated in U.S. Dollars, and\n    all funds must originate in the United States.\nentity_types:\n- type: business\n  text: you are acting solely on behalf of a commercial entity and have the power and authority to enter into this\n    Agreement on behalf of such entity\nrestricted_uses:\n- summary: No individual or household bill payments\n\
  \  text: (B) you will not use the Service for individual, household and personal bill payment activities;\n- summary: Not on OFAC SDN list\n  text: (E) you are not now and have never been on the Office of Foreign Assets Control (OFAC) Specially Designated\n    Nationals list;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corechain-technologies/eligibility/corechain-technologies-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from CoreChain Technologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fintech
- B2B
- Supply Chain
---
