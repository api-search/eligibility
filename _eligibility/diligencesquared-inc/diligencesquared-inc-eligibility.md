---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for business use by professionals who are at least 18 years of age.
    type: business
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Automated scraping and data gathering
    text: Use any data mining, robots, scraping, or similar automated data gathering methods on the Services;
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
name: Diligencesquared
provenance_date: '2026-11-09'
provider_name: Diligencesquared
provider_slug: diligencesquared-inc
slug: diligencesquared-inc-eligibility
source_date: '2026-11-09'
source_filename: diligencesquared-inc-eligibility.yml
source_heading: Eligibility
source_page: https://www.diligencesquared.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diligencesquared\naid: diligencesquared-inc\nurl: https://www.diligencesquared.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Services are intended for business use by professionals who are at least 18 years of age.\nrestricted_uses:\n- summary: Automated scraping and data gathering\n  text: Use any data mining, robots, scraping, or similar automated data gathering methods on the Services;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/diligencesquared-inc/eligibility/diligencesquared-inc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Diligencesquared's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Due Diligence
- Market Research
- Private Equity
- Artificial Intelligence
- AI Agents
- Investment Research
- Y Combinator
---
