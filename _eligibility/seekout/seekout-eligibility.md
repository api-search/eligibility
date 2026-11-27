---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not access the SeekOut Services if ... the laws of the country in which you reside prohibit use of the SeekOut Services
  entity_types:
  - text: If you are an individual accepting this Agreement on behalf of a company or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitors need consent
    text: Our competitors are prohibited from accessing or using the SeekOut Services without first obtaining our prior written consent.
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
name: SeekOut
provenance_date: '2026-11-10'
provider_name: SeekOut
provider_slug: seekout
slug: seekout-eligibility
source_date: '2026-11-10'
source_filename: seekout-eligibility.yml
source_heading: Eligibility
source_page: https://www.seekout.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SeekOut\naid: seekout\nurl: https://www.seekout.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not access the SeekOut Services if ... the laws of the country in which you reside prohibit use\n    of the SeekOut Services\nentity_types:\n- type: business\n  text: If you are an individual accepting this Agreement on behalf of a company or other legal entity, you represent\n    that you have the authority to bind such entity\nrestricted_uses:\n- summary: Competitors need consent\n  text: Our competitors are prohibited from accessing or using the SeekOut Services without\
  \ first obtaining our\n    prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/seekout/eligibility/seekout-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from SeekOut's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Recruiting
- Talent Acquisition
- Human Resources
- Sourcing
- Artificial Intelligence
- Candidate Search
- MCP
- Recruiting Automation
---
