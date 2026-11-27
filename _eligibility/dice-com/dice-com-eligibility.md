---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that materials in the Site are appropriate or available for use in locations outside the United States.
  entity_types:
  - text: If you are using this Site or its services as the representative of an employer, recruiter, staffing agency, or other business, you represent that you have the authority to bind such employer, recruiter, staffing agency, or other business entity to this Agreement
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Site.
    value: '18'
  restricted_uses:
  - summary: Discriminatory or unlawful job postings
    text: Post or transmit any job advertisement or posting that does not comply with applicable law, including, but not limited to, United States federal, state and local laws relating to equal employment opportunity and employment eligibility verification.
  - summary: Non-technology job postings
    text: Post any employment opportunities that are not technology-related or are outside a technology-related field or organization.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Because user authentication on the Internet is difficult, the Company cannot and does not confirm that users are who they claim to be.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dice
provenance_date: '2026-11-09'
provider_name: Dice
provider_slug: dice-com
slug: dice-com-eligibility
source_date: '2026-11-09'
source_filename: dice-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.dice.com/about/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dice\naid: dice-com\nurl: https://www.dice.com/about/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that materials in the Site are appropriate or available for use in locations outside\n    the United States.\nentity_types:\n- type: business\n  text: If you are using this Site or its services as the representative of an employer, recruiter, staffing agency,\n    or other business, you represent that you have the authority to bind such employer, recruiter, staffing agency,\n    or other business entity to this Agreement\nrestricted_uses:\n\
  - summary: Discriminatory or unlawful job postings\n  text: Post or transmit any job advertisement or posting that does not comply with applicable law, including, but\n    not limited to, United States federal, state and local laws relating to equal employment opportunity and employment\n    eligibility verification.\n- summary: Non-technology job postings\n  text: Post any employment opportunities that are not technology-related or are outside a technology-related field\n    or organization.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Because user authentication on the Internet is difficult, the Company cannot and does not confirm that users\n    are who they claim to be.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/dice-com/eligibility/dice-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Dice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Job
- Job Search
- Recruiting
- Careers
- Technology Talent
- MCP
---
