---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company does not represent that the Service is appropriate or available in other jurisdictions.
  entity_types:
  - text: You must be at least 18 years old to create an account.
    type: individual
  - text: If you use the Service on behalf of a company, organization, or other legal entity ("Organization"), you represent that you have authority to bind that Organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Export compliance
    text: You agree to comply with all applicable export control laws including United States export regulations.
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
name: skuit-ai
provenance_date: '2026-11-10'
provider_name: skuit-ai
provider_slug: skuit-ai
slug: skuit-ai-eligibility
source_date: '2026-11-10'
source_filename: skuit-ai-eligibility.yml
source_heading: Eligibility
source_page: https://skuit.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: skuit-ai\naid: skuit-ai\nurl: https://skuit.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company does not represent that the Service is appropriate or available in other jurisdictions.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account.\n- type: business\n  text: If you use the Service on behalf of a company, organization, or other legal entity (\"Organization\"), you\n    represent that you have authority to bind that Organization to these Terms.\nrestricted_uses:\n- summary: Export compliance\n  text: You agree to\
  \ comply with all applicable export control laws including United States export regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/skuit-ai/eligibility/skuit-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from skuit-ai's own page on 2026-11-10.
synthetic: false
tags:
- Networking
- BOM
- Artificial Intelligence
- Automation
- Cloud
---
