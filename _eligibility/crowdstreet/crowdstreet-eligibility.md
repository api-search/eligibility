---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Platform and the Services are intended for United States residents.
  entity_types:
  - text: Be at least 18 years old
    type: individual
  - text: or invest through an eligible U.S.-based entity
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No advertising or soliciting other Users
    text: Use the Platform Services, Content, or Materials to advertise or solicit other Users for any purpose, commercial or otherwise;
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
name: CrowdStreet
provenance_date: '2026-11-09'
provider_name: CrowdStreet
provider_slug: crowdstreet
slug: crowdstreet-eligibility
source_date: '2026-11-09'
source_filename: crowdstreet-eligibility.yml
source_heading: Eligibility
source_page: https://crowdstreet.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CrowdStreet\naid: crowdstreet\nurl: https://crowdstreet.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Platform and the Services are intended for United States residents.\nentity_types:\n- type: individual\n  text: Be at least 18 years old\n- type: business\n  text: or invest through an eligible U.S.-based entity\nrestricted_uses:\n- summary: No advertising or soliciting other Users\n  text: Use the Platform Services, Content, or Materials to advertise or solicit other Users for any purpose, commercial\n    or otherwise;\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/crowdstreet/eligibility/crowdstreet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CrowdStreet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Commercial Real Estate
- Investing
- Private Markets
- Alternative Investments
- Crowdfunding
- Financial Services
- Fintech
- Wealth Management
---
