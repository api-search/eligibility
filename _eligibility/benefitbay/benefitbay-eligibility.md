---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.
    type: individual
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: You agree not to upload, download, display, perform, transmit, or otherwise distribute any content that (a) is libelous, defamatory, obscene, pornographic, abusive, or threatening
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
name: BenefitBay
provenance_date: '2026-11-09'
provider_name: BenefitBay
provider_slug: benefitbay
slug: benefitbay-eligibility
source_date: '2026-11-09'
source_filename: benefitbay-eligibility.yml
source_heading: Eligibility
source_page: https://app.benefitbay.com/home/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BenefitBay\naid: benefitbay\nurl: https://app.benefitbay.com/home/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.\nrestricted_uses:\n- summary: Prohibited content\n  text: You agree not to upload, download, display, perform, transmit, or otherwise distribute any content that\n    (a) is libelous, defamatory, obscene, pornographic, abusive, or threatening\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD AND THAT YOU ARE LEGALLY ABLE TO ENTER INTO THIS USER AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/benefitbay/eligibility/benefitbay-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BenefitBay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- ICHRA
- Benefits
- Health Tech
- Software-as-a-Service
- Employee Benefits
---
