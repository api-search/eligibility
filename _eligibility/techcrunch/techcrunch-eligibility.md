---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services is intended for use only by residents of the United States over the age of 13.
  entity_types:
  - text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: You must be 13 years or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Not for trading, investing or commercial use
    text: The Services is provided for informational purposes only, and is not intended for trading or investing purposes, or for commercial use.
  - summary: No high-risk activities
    text: The Services should not be used in any high-risk activities where damage or injury to persons, property, environment, finances or business may result if an error occurs.
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
name: TechCrunch
provenance_date: '2026-11-10'
provider_name: TechCrunch
provider_slug: techcrunch
slug: techcrunch-eligibility
source_date: '2026-11-10'
source_filename: techcrunch-eligibility.yml
source_heading: Eligibility
source_page: https://techcrunch.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TechCrunch\naid: techcrunch\nurl: https://techcrunch.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services is intended for use only by residents of the United States over the age of 13.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of an entity, you represent and warrant that you have the authority to\n    bind that entity\nrestricted_uses:\n- summary: Not for trading, investing or commercial use\n  text: The Services is provided for informational purposes only, and is not intended for trading or investing purposes,\n\
  \    or for commercial use.\n- summary: No high-risk activities\n  text: The Services should not be used in any high-risk activities where damage or injury to persons, property,\n    environment, finances or business may result if an error occurs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/techcrunch/eligibility/techcrunch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TechCrunch's own page on 2026-11-10.
synthetic: false
tags:
- Media
- News
- Startups
- Technology News
- Venture Capital
---
