---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is operated in the United States, and is primarily intended for users located in the United States. Breezy makes no representation that the Service is appropriate or available for use beyond the United States.
  entity_types:
  - text: If you are accessing and using the Service on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: The Service is offered and available to users who are at least eighteen (18) years of age and can form a legally binding contract under applicable law.
    value: '18'
  restricted_uses:
  - summary: Recording features consent
    text: you, as the meeting organizer, must obtain all necessary consents, notices, or authorizations from any third parties required by applicable laws and regulations.
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
name: Breezy
provenance_date: '2026-11-09'
provider_name: Breezy
provider_slug: breezy
slug: breezy-eligibility
source_date: '2026-11-09'
source_filename: breezy-eligibility.yml
source_heading: Eligibility
source_page: https://app.breezy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Breezy\naid: breezy\nurl: https://app.breezy.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is operated in the United States, and is primarily intended for users located in the United\n    States. Breezy makes no representation that the Service is appropriate or available for use beyond the United\n    States.\nentity_types:\n- type: business\n  text: If you are accessing and using the Service on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind that entity to these Terms.\nrestricted_uses:\n\
  - summary: Recording features consent\n  text: you, as the meeting organizer, must obtain all necessary consents, notices, or authorizations from any third\n    parties required by applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is offered and available to users who are at least eighteen (18) years of age and can form a\n    legally binding contract under applicable law.\n"
source_yaml_url: https://artifacts.apis.io/breezy/eligibility/breezy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Breezy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Real Estate Technology
- Artificial Intelligence
- CRM
- Mobile
---
