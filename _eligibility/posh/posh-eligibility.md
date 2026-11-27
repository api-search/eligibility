---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We grant you a right to use these Services expressly for business and professional purposes.
    type: business
  minimum_age:
    text: you represent that you are of legal age and have the authority to bind the Customer to the Order
    value: null
  restricted_uses:
  - summary: Embargoed countries and export law
    text: Customer shall not permit its users to access or use any Service or Content in a U.S. embargoed country or in violation of any U.S. export law or regulation.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Acceptance of your Order may be subject to our verification and credit approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Posh
provenance_date: '2026-11-10'
provider_name: Posh
provider_slug: posh
slug: posh-eligibility
source_date: '2026-11-10'
source_filename: posh-eligibility.yml
source_heading: Eligibility
source_page: https://cdn.prod.website-files.com/61eb2514f01c7b377af34831/622bb1c684167fcca5a82a3d_posh-terms-of-use.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Posh\naid: posh\nurl: https://cdn.prod.website-files.com/61eb2514f01c7b377af34831/622bb1c684167fcca5a82a3d_posh-terms-of-use.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We grant you a right to use these Services expressly for business and professional purposes.\nrestricted_uses:\n- summary: Embargoed countries and export law\n  text: Customer shall not permit its users to access or use any Service or Content in a U.S. embargoed country\n    or in violation of any U.S. export law or regulation.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: true\n  text: Acceptance of your Order may be subject to our verification and credit approval.\nminimum_age:\n  value: null\n  text: you represent that you are of legal age and have the authority to bind the Customer to the Order\n"
source_yaml_url: https://artifacts.apis.io/posh/eligibility/posh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Posh's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Conversational AI
- AI Agents
- Banking
- Credit Union
- Financial Services
- Customer Service
- Contact Center
- Voice
- Chatbots
- Knowledge Management
- RegTech
---
