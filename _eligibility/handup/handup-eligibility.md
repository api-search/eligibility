---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: HandUp makes no representation that the HandUp Website is appropriate or available in locations outside the United States.
  entity_types:
  - text: Any use or access of the site from users under 18 is strictly prohibited and a violation of these Terms. By using the HandUp Website you represent and warrant that you are 18 years of age or older.
    type: individual
  minimum_age:
    text: Any use or access of the site from users under 18 is strictly prohibited and a violation of these Terms.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: use the HandUp Website for any illegal or unauthorized purpose
  - summary: Raffles and lotteries
    text: operate, conduct, or promote, directly or indirectly, raffles, lotteries or other similar gaming activities, whether for charitable purposes or otherwise
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
name: HandUp
provenance_date: '2026-11-09'
provider_name: HandUp
provider_slug: handup
slug: handup-eligibility
source_date: '2026-11-09'
source_filename: handup-eligibility.yml
source_heading: Eligibility
source_page: https://handup.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HandUp\naid: handup\nurl: https://handup.org/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: HandUp makes no representation that the HandUp Website is appropriate or available in locations outside\n    the United States.\nentity_types:\n- type: individual\n  text: Any use or access of the site from users under 18 is strictly prohibited and a violation of these Terms.\n    By using the HandUp Website you represent and warrant that you are 18 years of age or older.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: use the HandUp Website for any illegal or\
  \ unauthorized purpose\n- summary: Raffles and lotteries\n  text: operate, conduct, or promote, directly or indirectly, raffles, lotteries or other similar gaming activities,\n    whether for charitable purposes or otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access of the site from users under 18 is strictly prohibited and a violation of these Terms.\n"
source_yaml_url: https://artifacts.apis.io/handup/eligibility/handup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from HandUp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crowdfunding
- Non-Profit
- Donations
- Philanthropy
- Fundraising
- Homelessness
- Poverty
- Social Impact
---
