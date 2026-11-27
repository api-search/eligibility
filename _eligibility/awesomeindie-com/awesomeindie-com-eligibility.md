---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be 16 or older, and not barred from using services like this where you live.
    type: individual
  - text: If you are here on behalf of a company rather than as a person, mark the account as a business account.
    type: business
  minimum_age:
    text: You need to be 16 or older
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Ship anything harmful. No malware, phishing, scams, illegal content, or sexual content involving minors
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Every submission is reviewed.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Awesome Indie
provenance_date: '2026-11-09'
provider_name: Awesome Indie
provider_slug: awesomeindie-com
slug: awesomeindie-com-eligibility
source_date: '2026-11-09'
source_filename: awesomeindie-com-eligibility.yml
source_heading: Eligibility
source_page: https://awesomeindie.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Awesome Indie\naid: awesomeindie-com\nurl: https://awesomeindie.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be 16 or older, and not barred from using services like this where you live.\n- type: business\n  text: If you are here on behalf of a company rather than as a person, mark the account as a business account.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Ship anything harmful. No malware, phishing, scams, illegal content, or sexual content involving minors\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: true\n  text: Every submission is reviewed.\nminimum_age:\n  value: '16'\n  text: You need to be 16 or older\n"
source_yaml_url: https://artifacts.apis.io/awesomeindie-com/eligibility/awesomeindie-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Awesome Indie's own page on 2026-11-09.
synthetic: false
tags:
- Indie
- Launchpad
- Marketplace
- Tech
- Community
- Product
---
