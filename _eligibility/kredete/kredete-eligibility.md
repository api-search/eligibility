---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: These Terms are for customers located in or resident of the United States. To use the Services under these Terms you must have a US residential address and the legal right to use financial services in the United States.
  entity_types:
  - text: To use the Services you must be at least 18 years old (or the age of majority in your jurisdiction, if higher), have the legal capacity to enter into a binding contract
    type: individual
  minimum_age:
    text: you must be at least 18 years old (or the age of majority in your jurisdiction, if higher)
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons and jurisdictions
    text: You may not use the Services if you are located in, ordinarily resident in, or organised under the laws of any country or region subject to comprehensive sanctions
  - summary: Restricted activities
    text: transact in connection with activities we prohibit and disclose in-app (which may include, for example, unlawful gambling, controlled substances, weapons, or other restricted activity)
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
name: Kredete
provenance_date: '2026-11-09'
provider_name: Kredete
provider_slug: kredete
slug: kredete-eligibility
source_date: '2026-11-09'
source_filename: kredete-eligibility.yml
source_heading: Eligibility
source_page: https://kredete.io/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kredete\naid: kredete\nurl: https://kredete.io/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: These Terms are for customers located in or resident of the United States. To use the Services under these\n    Terms you must have a US residential address and the legal right to use financial services in the United States.\nentity_types:\n- type: individual\n  text: To use the Services you must be at least 18 years old (or the age of majority in your jurisdiction, if higher),\n    have the legal capacity to enter into a binding contract\nrestricted_uses:\n\
  - summary: Sanctioned persons and jurisdictions\n  text: You may not use the Services if you are located in, ordinarily resident in, or organised under the laws\n    of any country or region subject to comprehensive sanctions\n- summary: Restricted activities\n  text: transact in connection with activities we prohibit and disclose in-app (which may include, for example,\n    unlawful gambling, controlled substances, weapons, or other restricted activity)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old (or the age of majority in your jurisdiction, if higher)\n"
source_yaml_url: https://artifacts.apis.io/kredete/eligibility/kredete-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kredete's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Payments
- Remittances
- Cross-Border Payments
- Banking
- Credit
- Cards
- Savings
- Fintech
- Emerging Markets
- Africa
---
