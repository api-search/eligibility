---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in or ordinarily resident in a country or region subject to comprehensive sanctions, or if you appear on any government list of prohibited or restricted parties.
  entity_types:
  - text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    type: individual
  - text: If you use the Service on behalf of a company, organization, or other legal entity, you represent and warrant that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sexual exploitation of minors
    text: Create, solicit, or distribute content that sexually exploits or endangers minors, or that promotes terrorism or violent extremism.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use most of the Service you must create an account through our authentication provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Operator.io
provenance_date: '2026-11-10'
provider_name: Operator.io
provider_slug: operator
slug: operator-eligibility
source_date: '2026-11-10'
source_filename: operator-eligibility.yml
source_heading: Eligibility
source_page: https://operator.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Operator.io\naid: operator\nurl: https://operator.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in or ordinarily resident in a country or region subject\n    to comprehensive sanctions, or if you appear on any government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\n- type: business\n  text: If you use the Service on behalf of a company, organization, or other legal entity, you\
  \ represent and warrant\n    that you have authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Sexual exploitation of minors\n  text: Create, solicit, or distribute content that sexually exploits or endangers minors, or that promotes terrorism\n    or violent extremism.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use most of the Service you must create an account through our authentication provider.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/operator/eligibility/operator-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Operator.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Productivity
- Automation
- Software-as-a-Service
---
