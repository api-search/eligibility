---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Licensed Users who have purchased a subscription to a Gartner Product through an Order
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Automation use
    text: As it relates to use or indication of automation, regardless of the technical means used, Gartner further reserves the right at its sole discretion to immediately disable the impacted Licensed User(s)’ license(s) until the concern is addressed with the client.
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
name: Gartner
provenance_date: '2026-11-09'
provider_name: Gartner
provider_slug: gartner
slug: gartner-eligibility
source_date: '2026-11-09'
source_filename: gartner-eligibility.yml
source_heading: Eligibility
source_page: https://www.gartner.com/en/about/policies/usage-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gartner\naid: gartner\nurl: https://www.gartner.com/en/about/policies/usage-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Licensed Users who have purchased a subscription to a Gartner Product through an Order\nrestricted_uses:\n- summary: Automation use\n  text: As it relates to use or indication of automation, regardless of the technical means used, Gartner further\n    reserves the right at its sole discretion to immediately disable the impacted Licensed User(s)’ license(s) until\n    the concern is addressed with the client.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gartner/eligibility/gartner-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Gartner's own page on 2026-11-09.
synthetic: false
tags:
- Research
- Advisory
- Analyst
- Enterprise
- Fortune 1000
---
