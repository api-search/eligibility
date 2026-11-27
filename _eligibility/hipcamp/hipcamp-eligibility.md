---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - AU
    - CA
    text: The Hipcamp Materials are controlled and offered by Hipcamp from its facilities in the United States of America and made available to end users in the United States, the United Kingdom, Australia, and Canada
  entity_types:
  - text: THE TERM “ YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE WEBSITE.
    type: business
  minimum_age:
    text: You represent that you are (1) at least eighteen (18) years old; (2) of legal age to form a binding contract
    value: '18'
  restricted_uses:
  - summary: Export and embargo restrictions
    text: You may not use, export, import, or transfer the Hipcamp Materials except as authorized by U.S. law, the laws of the jurisdiction in which you obtained the Hipcamp Materials, and any other applicable laws.
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
name: Hipcamp
provenance_date: '2026-11-09'
provider_name: Hipcamp
provider_slug: hipcamp
slug: hipcamp-eligibility
source_date: '2026-11-09'
source_filename: hipcamp-eligibility.yml
source_heading: Eligibility
source_page: https://www.hipcamp.com/en-US/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hipcamp\naid: hipcamp\nurl: https://www.hipcamp.com/en-US/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - GB\n  - AU\n  - CA\n  excluded: []\n  text: The Hipcamp Materials are controlled and offered by Hipcamp from its facilities in the United States of\n    America and made available to end users in the United States, the United Kingdom, Australia, and Canada\nentity_types:\n- type: business\n  text: THE TERM “ YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE WEBSITE.\nrestricted_uses:\n- summary: Export\
  \ and embargo restrictions\n  text: You may not use, export, import, or transfer the Hipcamp Materials except as authorized by U.S. law, the\n    laws of the jurisdiction in which you obtained the Hipcamp Materials, and any other applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are (1) at least eighteen (18) years old; (2) of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/hipcamp/eligibility/hipcamp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Hipcamp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Camping
- Travel
- Booking
- Reservations
- Outdoors
- Hospitality
- Marketplace
---
