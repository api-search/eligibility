---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that Clicker.com is appropriate or available for use in the country, geographic area or jurisdiction where you are located
  entity_types:
  - text: Clicker.com is for your personal use only
    type: individual
  - text: Clicker.com is a consumer service and is not designed to be used in connection with your, your employers' or contractors' commercial activities.
    type: business
  minimum_age:
    text: You must be legally competent to enter into contracts.
    value: null
  restricted_uses:
  - summary: Personal, entertainment and informational use only
    text: Clicker.com is a video search product designed for personal, entertainment and informational purposes only.
  - summary: Lawful use only
    text: You will use Clicker.com for lawful purposes only.
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
name: Clicker
provenance_date: '2026-11-09'
provider_name: Clicker
provider_slug: clicker
slug: clicker-eligibility
source_date: '2026-11-09'
source_filename: clicker-eligibility.yml
source_heading: Eligibility
source_page: https://www.clicker.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clicker\naid: clicker\nurl: https://www.clicker.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that Clicker.com is appropriate or available for use in the country, geographic\n    area or jurisdiction where you are located\nentity_types:\n- type: individual\n  text: Clicker.com is for your personal use only\n- type: business\n  text: Clicker.com is a consumer service and is not designed to be used in connection with your, your employers'\n    or contractors' commercial activities.\nrestricted_uses:\n- summary: Personal, entertainment\
  \ and informational use only\n  text: Clicker.com is a video search product designed for personal, entertainment and informational purposes only.\n- summary: Lawful use only\n  text: You will use Clicker.com for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be legally competent to enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/clicker/eligibility/clicker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Clicker's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Streaming
- Entertainment
- Media
- Movies
- Television
- Discovery
- Video
---
