---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is intended for use only by individuals age 18 or over located in the United States.
  entity_types:
  - text: THE WEBSITE IS INTENDED FOR USE ONLY BY INDIVIDUALS AGE 18 OR OVER LOCATED IN THE UNITED STATES.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Persons suspended or removed
    text: THE WEBSITE IS NOT AVAILABLE TO ANY PERSONS SUSPENDED OR REMOVED FROM THE WEBSITE BY THE COMPANY.
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
name: Ferguson
provenance_date: '2026-11-09'
provider_name: Ferguson
provider_slug: ferguson
slug: ferguson-eligibility
source_date: '2026-11-09'
source_filename: ferguson-eligibility.yml
source_heading: Eligibility
source_page: https://www.ferguson.com/content/customer-support/website-information/terms-of-site-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ferguson\naid: ferguson\nurl: https://www.ferguson.com/content/customer-support/website-information/terms-of-site-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is intended for use only by individuals age 18 or over located in the United States.\nentity_types:\n- type: individual\n  text: THE WEBSITE IS INTENDED FOR USE ONLY BY INDIVIDUALS AGE 18 OR OVER LOCATED IN THE UNITED STATES.\nrestricted_uses:\n- summary: Persons suspended or removed\n  text: THE WEBSITE IS NOT AVAILABLE TO ANY PERSONS SUSPENDED OR REMOVED FROM THE WEBSITE BY THE\
  \ COMPANY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ferguson/eligibility/ferguson-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Ferguson's own page on 2026-11-09.
synthetic: false
tags:
- Distribution
- Plumbing
- HVAC
- Building Supplies
- Waterworks
- Pipe Valves Fittings
- Wholesale Distribution
- B2B
- Fortune 500
---
