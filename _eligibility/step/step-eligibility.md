---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Certain features of the P2P Transfer service will only be available to you if you are at least 18 years of age or the age of majority in your state.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your state of residence) in order to use the Payment Portal.
    value: '18'
  restricted_uses:
  - summary: No commercial P2P transfers
    text: YOU MAY NOT SEND MONEY TO ANYONE FOR COMMERCIAL PURPOSES, INCLUDING THE PURCHASE OF GOODS AND SERVICES.
  - summary: Gift cards not resold
    text: Gift Cards may not be resold to a third party.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Bank Partner has sole discretion to approve or deny your application for a Step Account, or discontinue your Step Account, for any reason, subject to applicable law.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Step
provenance_date: '2026-11-10'
provider_name: Step
provider_slug: step
slug: step-eligibility
source_date: '2026-11-10'
source_filename: step-eligibility.yml
source_heading: Eligibility
source_page: https://step.com/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Step\naid: step\nurl: https://step.com/policies/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Certain features of the P2P Transfer service will only be available to you if you are at least 18 years\n    of age or the age of majority in your state.\nrestricted_uses:\n- summary: No commercial P2P transfers\n  text: YOU MAY NOT SEND MONEY TO ANYONE FOR COMMERCIAL PURPOSES, INCLUDING THE PURCHASE OF GOODS AND SERVICES.\n- summary: Gift cards not resold\n  text: Gift Cards may not be resold to a third party.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Bank Partner has sole discretion to approve or deny your application for a Step Account, or discontinue\n    your Step Account, for any reason, subject to applicable law.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your state of residence) in order to use the\n    Payment Portal.\n"
source_yaml_url: https://artifacts.apis.io/step/eligibility/step-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Step's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Banking
- Teens
- Credit Building
- Payments
- Investing
- Consumer Finance
- Financial Education
---
