---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: by and between the individual or entity (“ Client ”) named in the GoodUnited Order Form
    type: individual
  - text: by and between the individual or entity (“ Client ”) named in the GoodUnited Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No EU or California personal data disclosed without addendum
    text: Client acknowledges and agrees that it will not disclose to GoodUnited any personal data of EU data subjects
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
name: GoodUnited
provenance_date: '2026-11-09'
provider_name: GoodUnited
provider_slug: goodunited
slug: goodunited-eligibility
source_date: '2026-11-09'
source_filename: goodunited-eligibility.yml
source_heading: Eligibility
source_page: https://www.goodunited.io/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GoodUnited\naid: goodunited\nurl: https://www.goodunited.io/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: by and between the individual or entity (“ Client ”) named in the GoodUnited Order Form\n- type: business\n  text: by and between the individual or entity (“ Client ”) named in the GoodUnited Order Form\nrestricted_uses:\n- summary: No EU or California personal data disclosed without addendum\n  text: Client acknowledges and agrees that it will not disclose to GoodUnited any personal data of EU data subjects\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/goodunited/eligibility/goodunited-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from GoodUnited's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Social Media
- Fundraising
- Donor Engagement
---
