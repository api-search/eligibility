---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and have the legal capacity to enter into a binding agreement to use our services.
    type: individual
  - text: If you are using our services on behalf of a company or other legal entity, you represent that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age and have the legal capacity to enter into a binding agreement to use our services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: Use our services to store or transmit any content that infringes the intellectual property rights of any third party.
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
name: Intellova
provenance_date: '2026-11-09'
provider_name: Intellova
provider_slug: intellova
slug: intellova-eligibility
source_date: '2026-11-09'
source_filename: intellova-eligibility.yml
source_heading: Eligibility
source_page: https://www.intellova.com.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intellova\naid: intellova\nurl: https://www.intellova.com.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and have the legal capacity to enter into a binding agreement to use\n    our services.\n- type: business\n  text: If you are using our services on behalf of a company or other legal entity, you represent that you have\n    the authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Use our services to store or transmit any\
  \ content that infringes the intellectual property rights of any\n    third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and have the legal capacity to enter into a binding agreement to use\n    our services.\n"
source_yaml_url: https://artifacts.apis.io/intellova/eligibility/intellova-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Intellova's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- Automation
- Australian Business
- Cloud Services
---
