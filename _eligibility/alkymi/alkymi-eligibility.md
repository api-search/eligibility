---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You will only use the Site in a manner that complies with all laws that apply to you.
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
name: Alkymi
provenance_date: '2026-11-09'
provider_name: Alkymi
provider_slug: alkymi
slug: alkymi-eligibility
source_date: '2026-11-09'
source_filename: alkymi-eligibility.yml
source_heading: Eligibility
source_page: https://www.alkymi.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alkymi\naid: alkymi\nurl: https://www.alkymi.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You will only use the Site in a manner that complies\
  \ with all laws that apply to you.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly collect or solicit personally identifiable information from children under 18 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/alkymi/eligibility/alkymi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Alkymi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Private Markets
- Document Processing
- Data Extraction
- Artificial Intelligence
- Alternative Investments
- Webhook
---
