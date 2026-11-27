---
claim_count: 8
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are operated in the United States and intended for users located in the United States.
  entity_types:
  - text: you have the authority to enter into the Terms of Use personally or on behalf of the company you have designated as the user of the Services, and to bind that company to these Terms of Use.
    type: business
  minimum_age:
    text: if you are below the age of 18 or the minimum age required in your country to consent to use the Services, you may not access or use the Services
    value: '18'
  restricted_uses:
  - summary: No PHI input
    text: You may not provide any Input that includes protected health information
  - source: https://www.sesame.com/aup
    summary: Professional advice
    text: Solicit or generate professional advice, such as legal, financial, health, medical, tax, or other professional advice
  - source: https://www.sesame.com/aup
    summary: Automated decisions with significant impact
    text: Perform automated decision-making with significant impacts on an individual or group
  - source: https://www.sesame.com/aup
    summary: Regulated personal information
    text: Provide any input that includes regulated personal information of others, such as protected health information
  - source: https://www.sesame.com/aup
    summary: Surveillance and profiling
    text: Engage in risk-based assessments of individuals’ likelihood of committing crimes or re-offending
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
name: Sesame
provenance_date: '2026-11-10'
provider_name: Sesame
provider_slug: sesame-com
slug: sesame-com-eligibility
source_date: '2026-11-10'
source_filename: sesame-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.sesame.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sesame\naid: sesame-com\nurl: https://www.sesame.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.sesame.com/aup\n  - https://www.sesame.com/terms\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are operated in the United States and intended for users located in the United States.\nentity_types:\n- type: business\n  text: you have the authority to enter into the Terms of Use personally or on behalf of the company you have designated\n    as the user of the Services, and to bind that company to these Terms of Use.\nrestricted_uses:\n- summary: No PHI input\n  text: You may\
  \ not provide any Input that includes protected health information\n- summary: Professional advice\n  text: Solicit or generate professional advice, such as legal, financial, health, medical, tax, or other professional\n    advice\n  source: https://www.sesame.com/aup\n- summary: Automated decisions with significant impact\n  text: Perform automated decision-making with significant impacts on an individual or group\n  source: https://www.sesame.com/aup\n- summary: Regulated personal information\n  text: Provide any input that includes regulated personal information of others, such as protected health information\n  source: https://www.sesame.com/aup\n- summary: Surveillance and profiling\n  text: Engage in risk-based assessments of individuals’ likelihood of committing crimes or re-offending\n  source: https://www.sesame.com/aup\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are below the age of 18 or the minimum\
  \ age required in your country to consent to use the Services,\n    you may not access or use the Services\n"
source_yaml_url: https://artifacts.apis.io/sesame-com/eligibility/sesame-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 8 quoted statements, read from Sesame's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Personal Agents
- Productivity
- Privacy
---
