---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the Platform or register a Guest Account.
    type: individual
  - text: If you are acting on behalf of an entity, you represent that you have the right, authority, and capacity to act on behalf of, and bind to this Agreement, such entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the Platform or register a Guest Account.
    value: '18'
  restricted_uses:
  - summary: Guest Content restrictions
    text: its Guest Content is not, and will not be, false, misleading, untruthful, disparaging, libelous, threatening, offensive, harassing, deceptive, abusive
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Guest acknowledges and agrees that a condition to creating a Guest Account is Guest providing Company with valid identification means in order to verify its identity, as may be requested by Company (such as a social media account) and/or a valid driver's license or passport.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gable
provenance_date: '2026-11-09'
provider_name: Gable
provider_slug: gable
slug: gable-eligibility
source_date: '2026-11-09'
source_filename: gable-eligibility.yml
source_heading: Eligibility
source_page: https://www.gable.to/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gable\naid: gable\nurl: https://www.gable.to/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the\n    Platform or register a Guest Account.\n- type: business\n  text: If you are acting on behalf of an entity, you represent that you have the right, authority, and capacity\n    to act on behalf of, and bind to this Agreement, such entity.\nrestricted_uses:\n- summary: Guest Content restrictions\n  text:\
  \ its Guest Content is not, and will not be, false, misleading, untruthful, disparaging, libelous, threatening,\n    offensive, harassing, deceptive, abusive\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Guest acknowledges and agrees that a condition to creating a Guest Account is Guest providing Company with\n    valid identification means in order to verify its identity, as may be requested by Company (such as a social\n    media account) and/or a valid driver's license or passport.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to enter into legally binding contracts to access and use the\n    Platform or register a Guest Account.\n"
source_yaml_url: https://artifacts.apis.io/gable/eligibility/gable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Gable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workplace Management
- Desk Booking
- Hybrid Work
- Room Scheduling
- Visitor Management
- Co-Working
- Real Estate Analytics
---
