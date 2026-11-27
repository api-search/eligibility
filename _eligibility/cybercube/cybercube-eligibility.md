---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Website is not for use by any minors (defined as those who are not at least 18 years of age)
    value: '18'
  restricted_uses:
  - summary: Use contrary to law
    text: using this Website contrary to applicable laws and regulations
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
name: CyberCube
provenance_date: '2026-11-09'
provider_name: CyberCube
provider_slug: cybercube
slug: cybercube-eligibility
source_date: '2026-11-09'
source_filename: cybercube-eligibility.yml
source_heading: Eligibility
source_page: https://www.cybcube.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CyberCube\naid: cybercube\nurl: https://www.cybcube.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use contrary to law\n  text: using this Website contrary to applicable laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is not for use by any minors (defined as those who are not at least 18 years of age)\n"
source_yaml_url: https://artifacts.apis.io/cybercube/eligibility/cybercube-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from CyberCube's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cyber Risk
- Insurance
- Analytics
- Risk Modeling
- Cybersecurity
- Reinsurance
- Catastrophe Modeling
- Underwriting
- Insurtech
---
