---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Residents of the United States will be contracting with Props2fantasy.com, Inc. By depositing money or entering a contest, you are representing and warranting that you are a citizen or resident of the United States of America and that you have an address in the United States of America; at the time of deposit or game entry you are physically located in the United States of America
  entity_types:
  - text: you are of 18 years of age or older (21 years of age or older in Massachusetts, 19 years of age or older in Nebraska)
    type: individual
  minimum_age:
    text: you are of 18 years of age or older (21 years of age or older in Massachusetts, 19 years of age or older in Nebraska)
    value: '18'
  restricted_uses:
  - summary: Excluded states for paid contests
    text: 'when depositing funds or entering a paid contest, you are not physically located in of any of the following states: Alabama, Arizona, Hawaii, Idaho, Indiana, Iowa, Louisiana, Maine, Mississippi, Missouri, Montana, Nevada, New Hampshire, New Jersey, New York, Pennsylvania, Tennessee, Vermont, Virginia, or Washington'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: By depositing funds or entering paid contests, you agree to provide us with a valid mailing address, date of birth and social security number and any other information we may require in order to run appropriate identity checks
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ThriveFantasy
provenance_date: '2026-11-10'
provider_name: ThriveFantasy
provider_slug: thrivefantasy
slug: thrivefantasy-eligibility
source_date: '2026-11-10'
source_filename: thrivefantasy-eligibility.yml
source_heading: Eligibility
source_page: https://www.thrivefantasy.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ThriveFantasy\naid: thrivefantasy\nurl: https://www.thrivefantasy.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Residents of the United States will be contracting with Props2fantasy.com, Inc. By depositing money or entering\n    a contest, you are representing and warranting that you are a citizen or resident of the United States of America\n    and that you have an address in the United States of America; at the time of deposit or game entry you are physically\n    located in the United States of America\nentity_types:\n- type: individual\n  text:\
  \ you are of 18 years of age or older (21 years of age or older in Massachusetts, 19 years of age or older\n    in Nebraska)\nrestricted_uses:\n- summary: Excluded states for paid contests\n  text: 'when depositing funds or entering a paid contest, you are not physically located in of any of the following\n    states: Alabama, Arizona, Hawaii, Idaho, Indiana, Iowa, Louisiana, Maine, Mississippi, Missouri, Montana, Nevada,\n    New Hampshire, New Jersey, New York, Pennsylvania, Tennessee, Vermont, Virginia, or Washington'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: By depositing funds or entering paid contests, you agree to provide us with a valid mailing address, date\n    of birth and social security number and any other information we may require in order to run appropriate identity\n    checks\nminimum_age:\n  value: '18'\n  text: you are of 18 years of age or older (21 years of age or older in Massachusetts, 19 years of age or older\n    in Nebraska)\n"
source_yaml_url: https://artifacts.apis.io/thrivefantasy/eligibility/thrivefantasy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ThriveFantasy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fantasy Sports
- Sports
- Gaming
- Player Props
- Contests
- Defunct
---
