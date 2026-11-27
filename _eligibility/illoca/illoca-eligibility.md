---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: we do not knowingly collect or solicit personally identifiable information from children under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Violating laws or Terms restrictions
    text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy laws
  - summary: Reselling or third-party use
    text: You will only use the Services for your own internal use, and not on behalf of or for the benefit of any third party
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
name: illoca
provenance_date: '2026-11-09'
provider_name: illoca
provider_slug: illoca
slug: illoca-eligibility
source_date: '2026-11-09'
source_filename: illoca-eligibility.yml
source_heading: Eligibility
source_page: https://illoca.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: illoca\naid: illoca\nurl: https://illoca.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses:\n- summary: Violating laws or Terms restrictions\n  text: violates any law or regulation, including,\
  \ without limitation, any applicable export control laws, privacy\n    laws\n- summary: Reselling or third-party use\n  text: You will only use the Services for your own internal use, and not on behalf of or for the benefit of any\n    third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: we do not knowingly collect or solicit personally identifiable information from children under 18 years\n    of age.\n"
source_yaml_url: https://artifacts.apis.io/illoca/eligibility/illoca-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from illoca's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Architecture
- Design
- Generative AI
- Architectural Design
- CAD
- BIM
---
