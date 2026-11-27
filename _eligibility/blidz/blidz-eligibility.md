---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - AU
    - GB
    text: The market for Blidz's services is the United States, Canada, Australia, and the United Kingdom. Blidz may also offer limited or pre-launch availability in the European Economic Area
  entity_types:
  - text: The Platform is intended for use by individuals who are at least 18 years old or the age of legal majority in their jurisdiction.
    type: individual
  - text: If you are using the Platform on behalf of a company, entity, or organization, you represent that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age to open an account, participate in Deals, purchase goods offered through the Service, or otherwise use the Service.
    value: '18'
  restricted_uses:
  - summary: One account per person
    text: You may establish only one account per person.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Blidz may require identity verification before processing any redemption.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blidz
provenance_date: '2026-11-09'
provider_name: Blidz
provider_slug: blidz
slug: blidz-eligibility
source_date: '2026-11-09'
source_filename: blidz-eligibility.yml
source_heading: Eligibility
source_page: https://blidz.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blidz\naid: blidz\nurl: https://blidz.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  - AU\n  - GB\n  excluded: []\n  text: The market for Blidz's services is the United States, Canada, Australia, and the United Kingdom. Blidz may\n    also offer limited or pre-launch availability in the European Economic Area\nentity_types:\n- type: individual\n  text: The Platform is intended for use by individuals who are at least 18 years old or the age of legal majority\n    in their jurisdiction.\n- type: business\n  text: If you are using the Platform on\
  \ behalf of a company, entity, or organization, you represent that you have\n    the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: One account per person\n  text: You may establish only one account per person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Blidz may require identity verification before processing any redemption.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to open an account, participate in Deals, purchase goods offered through\n    the Service, or otherwise use the Service.\n"
source_yaml_url: https://artifacts.apis.io/blidz/eligibility/blidz-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Blidz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- E-Commerce
- Shopping
- Marketplace
- Mobile
- Retail
---
