---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Site is intended for companies and individuals located in the United States.
  entity_types:
  - text: The Site is intended for business use by employers, their human resources, finance, and leadership teams, their advisors, and the users those companies designate to use the client portal.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Portal use limited to assigned company
    text: You may use the portal only for the company and purposes for which your access was granted.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access to the client portal is by invitation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beni
provenance_date: '2026-11-09'
provider_name: Beni
provider_slug: beni
slug: beni-eligibility
source_date: '2026-11-09'
source_filename: beni-eligibility.yml
source_heading: Eligibility
source_page: https://www.beniglobal.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beni\naid: beni\nurl: https://www.beniglobal.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Site is intended for companies and individuals located in the United States.\nentity_types:\n- type: business\n  text: The Site is intended for business use by employers, their human resources, finance, and leadership teams,\n    their advisors, and the users those companies designate to use the client portal.\nrestricted_uses:\n- summary: Portal use limited to assigned company\n  text: You may use the portal only for the company and purposes for which your access\
  \ was granted.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access to the client portal is by invitation.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/beni/eligibility/beni-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Beni's own page on 2026-11-09.
synthetic: false
tags:
- Employee Benefits
- Consulting
- Technology
- Health
- Solutions
---
