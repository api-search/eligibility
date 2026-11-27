---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and use the Service for business purposes. If you accept these Terms on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18
    value: '18'
  restricted_uses:
  - summary: Sensitive personal information
    text: (b) collect or solicit sensitive personal information (such as health records, financial account numbers, government IDs, or children's data) through the assistant;
  - summary: High-risk activities
    text: (g) use the Service for high-risk activities where errors could lead to death, personal injury, or serious property or environmental damage.
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
name: tryneverclosed-com
provenance_date: '2026-11-10'
provider_name: tryneverclosed-com
provider_slug: tryneverclosed-com
slug: tryneverclosed-com-eligibility
source_date: '2026-11-10'
source_filename: tryneverclosed-com-eligibility.yml
source_heading: Eligibility
source_page: https://tryneverclosed.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tryneverclosed-com\naid: tryneverclosed-com\nurl: https://tryneverclosed.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be at least 18 and use the Service for business purposes. If you accept these Terms on behalf of\n    an organization, you represent that you have authority to bind that organization.\nrestricted_uses:\n- summary: Sensitive personal information\n  text: (b) collect or solicit sensitive personal information (such as health records, financial account numbers,\n    government IDs, or children's data)\
  \ through the assistant;\n- summary: High-risk activities\n  text: (g) use the Service for high-risk activities where errors could lead to death, personal injury, or serious\n    property or environmental damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\n"
source_yaml_url: https://artifacts.apis.io/tryneverclosed-com/eligibility/tryneverclosed-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from tryneverclosed-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Receptionist
- Automation
- Customer Service
- Scheduling
- Company
---
