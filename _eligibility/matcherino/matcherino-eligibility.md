---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'In the United States, prohibited jurisdictions, as of the “Updated” date above, include but are not limited to: Arizona, Colorado, Delaware, Louisiana, Montana, and Tennessee.'
  entity_types:
  - text: registered users who are event organizers, planners and organizations (“Organizers”)
    type: business
  minimum_age:
    text: you must be at least eighteen (18) years of age, or the legal age of majority where you reside, to use the Services
    value: '18'
  restricted_uses:
  - summary: Gambling/prize activities restricted
    text: facilitate gambling, gaming, lotteries, raffles, contests, sweepstakes and/or any other activity featuring the award of a prize except as explicitly authorized by these Terms
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
name: Matcherino
provenance_date: '2026-11-10'
provider_name: Matcherino
provider_slug: matcherino
slug: matcherino-eligibility
source_date: '2026-11-10'
source_filename: matcherino-eligibility.yml
source_heading: Eligibility
source_page: https://matcherino.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Matcherino\naid: matcherino\nurl: https://matcherino.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'In the United States, prohibited jurisdictions, as of the “Updated” date above, include but are not limited\n    to: Arizona, Colorado, Delaware, Louisiana, Montana, and Tennessee.'\nentity_types:\n- type: business\n  text: registered users who are event organizers, planners and organizations (“Organizers”)\nrestricted_uses:\n- summary: Gambling/prize activities restricted\n  text: facilitate gambling, gaming, lotteries, raffles, contests, sweepstakes\
  \ and/or any other activity featuring\n    the award of a prize except as explicitly authorized by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least eighteen (18) years of age, or the legal age of majority where you reside, to use the\n    Services\n"
source_yaml_url: https://artifacts.apis.io/matcherino/eligibility/matcherino-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Matcherino's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Esports
- Gaming
- Tournaments
- Crowdfunding
- Payments
- Payouts
- Sponsorship
---
