---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: all marketing or promotional materials found on this Website are solely directed to individuals, companies or other entities located in India
  entity_types:
  - text: you represent that you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: The Service is not available to minors under the age of 18
    value: '18'
  restricted_uses:
  - summary: No account transfer or multiple accounts
    text: users are prohibited from selling, trading, or otherwise transferring their accounts to another party.
  - summary: Minors and suspended users excluded
    text: The Service is not available to minors under the age of 18 or to any users suspended or removed from the system by Policybazaar for any reason.
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
name: Policybazaar
provenance_date: '2026-11-10'
provider_name: Policybazaar
provider_slug: policybazaar
slug: policybazaar-eligibility
source_date: '2026-11-10'
source_filename: policybazaar-eligibility.yml
source_heading: Eligibility
source_page: https://www.policybazaar.com/legal-and-admin-policies/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Policybazaar\naid: policybazaar\nurl: https://www.policybazaar.com/legal-and-admin-policies/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: all marketing or promotional materials found on this Website are solely directed to individuals, companies\n    or other entities located in India\nentity_types:\n- type: individual\n  text: you represent that you are of legal age to form a binding contract\nrestricted_uses:\n- summary: No account transfer or multiple accounts\n  text: users are prohibited from selling, trading, or otherwise transferring their accounts\
  \ to another party.\n- summary: Minors and suspended users excluded\n  text: The Service is not available to minors under the age of 18 or to any users suspended or removed from the\n    system by Policybazaar for any reason.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is not available to minors under the age of 18\n"
source_yaml_url: https://artifacts.apis.io/policybazaar/eligibility/policybazaar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Policybazaar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Insurance
- Insurtech
- Marketplace
- India
- Insurance Aggregator
---
