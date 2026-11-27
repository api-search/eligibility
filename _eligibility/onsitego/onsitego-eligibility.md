---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Unless otherwise explicitly stated, all marketing or promotional materials found on this Website are solely directed to individuals, companies or other entities located in India and comply with the laws prevailing for the time being in force in India.
  entity_types:
  - text: The Service is not available to minors under the age of 18 or to any users suspended or removed from the system by Onsite for any reason.
    type: individual
  minimum_age:
    text: The Service is not available to minors under the age of 18
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use
    text: use this Site or its contents for any commercial purpose
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
name: Onsitego
provenance_date: '2026-11-10'
provider_name: Onsitego
provider_slug: onsitego
slug: onsitego-eligibility
source_date: '2026-11-10'
source_filename: onsitego-eligibility.yml
source_heading: Eligibility
source_page: https://onsitego.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Onsitego\naid: onsitego\nurl: https://onsitego.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Unless otherwise explicitly stated, all marketing or promotional materials found on this Website are solely\n    directed to individuals, companies or other entities located in India and comply with the laws prevailing for\n    the time being in force in India.\nentity_types:\n- type: individual\n  text: The Service is not available to minors under the age of 18 or to any users suspended or removed from the\n    system by Onsite for any reason.\nrestricted_uses:\n\
  - summary: Non-commercial personal use\n  text: use this Site or its contents for any commercial purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not available to minors under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/onsitego/eligibility/onsitego-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Onsitego's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Consumer Electronics
- Device Protection
- Extended Warranty
- Insurance
- Repair Services
- India
---
