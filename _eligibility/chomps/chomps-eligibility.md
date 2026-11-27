---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Free shipping on orders $30 or more within the continental US only.
  entity_types:
  - text: This Agreement applies to all users of our Services, including users who are browsers, vendors, customers, merchants, and/ or contributors of content.
    type: business
  minimum_age:
    text: you represent that you are at least the age of majority in your state of residence (18 years old in most states)
    value: age of majority (18 in most states)
  restricted_uses:
  - summary: Unlawful purposes
    text: for any unlawful purpose
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
name: Chomps
provenance_date: '2026-11-09'
provider_name: Chomps
provider_slug: chomps
slug: chomps-eligibility
source_date: '2026-11-09'
source_filename: chomps-eligibility.yml
source_heading: Eligibility
source_page: https://chomps.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chomps\naid: chomps\nurl: https://chomps.com/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Free shipping on orders $30 or more within the continental US only.\nentity_types:\n- type: business\n  text: This Agreement applies to all users of our Services, including users who are browsers, vendors, customers,\n    merchants, and/ or contributors of content.\nrestricted_uses:\n- summary: Unlawful purposes\n  text: for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: age of majority (18 in most states)\n  text: you represent that you are at least the age of majority in your state of residence (18 years old in most\n    states)\n"
source_yaml_url: https://artifacts.apis.io/chomps/eligibility/chomps-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chomps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food
- Snacks
- Beef
- Paleo
---
