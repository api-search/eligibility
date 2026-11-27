---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of a company, you represent that you have authority to bind that company to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years old and have the legal capacity to enter into a contract to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unauthorized brand tracking
    text: Use the Service to track brands or domains you do not own or have authorization to monitor.
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
name: AskAiRank
provenance_date: '2026-11-09'
provider_name: AskAiRank
provider_slug: askairank-com
slug: askairank-com-eligibility
source_date: '2026-11-09'
source_filename: askairank-com-eligibility.yml
source_heading: Eligibility
source_page: https://askairank.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AskAiRank\naid: askairank-com\nurl: https://askairank.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of a company, you represent that you have authority to bind that\n    company to these Terms.\nrestricted_uses:\n- summary: Unauthorized brand tracking\n  text: Use the Service to track brands or domains you do not own or have authorization to monitor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at\
  \ least 16 years old and have the legal capacity to enter into a contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/askairank-com/eligibility/askairank-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AskAiRank's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Software-as-a-Service
- Marketing
- Visibility
- Analytics
- Company
---
