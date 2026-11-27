---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CHARTBEAT MAKES NO REPRESENTATIONS THAT THE SERVICES ARE APPROPRIATE OR AVAILABLE FOR USE IN OTHER COUNTRIES.
  minimum_age:
    text: Chartbeat does not knowingly collect or solicit personally identifiable information from children under 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Restricted AI inputs
    text: 'Customer shall not submit Inputs containing: (i) personally identifiable information or sensitive data in violation of these Terms or applicable law'
  - summary: App Store embargo representation
    text: Customer represents and warrants that it is not located in a country subject to a U.S. Government embargo
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
name: Chartbeat
provenance_date: '2026-11-09'
provider_name: Chartbeat
provider_slug: chartbeat
slug: chartbeat-eligibility
source_date: '2026-11-09'
source_filename: chartbeat-eligibility.yml
source_heading: Eligibility
source_page: https://chartbeat.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chartbeat\naid: chartbeat\nurl: https://chartbeat.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: CHARTBEAT MAKES NO REPRESENTATIONS THAT THE SERVICES ARE APPROPRIATE OR AVAILABLE FOR USE IN OTHER COUNTRIES.\nentity_types: []\nrestricted_uses:\n- summary: Restricted AI inputs\n  text: 'Customer shall not submit Inputs containing: (i) personally identifiable information or sensitive data\n    in violation of these Terms or applicable law'\n- summary: App Store embargo representation\n  text: Customer represents and warrants that it is not located in a\
  \ country subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Chartbeat does not knowingly collect or solicit personally identifiable information from children under\n    16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/chartbeat/eligibility/chartbeat-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chartbeat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Analytics
- Content Analytics
- Real-Time Analytics
- Audience Engagement
- Publishing
- Media
- Web Analytics
- Video Analytics
---
