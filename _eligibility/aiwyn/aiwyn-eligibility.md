---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Canadian and US users are referenced; no general country restriction stated.
  entity_types:
  - text: The Site and Services are intended for people 18 years or older.
    type: individual
  - text: If you are a representative of a company that is a customer of Aiwyn that has signed a separate agreement with Aiwyn (a “ Customer Agreement ”), then to the extent of any conflict between the terms of the Customer Agreement and these Terms of Use, the Customer Agreement shall govern.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of site
    text: The Site or any portion of this Site may not be reproduced, duplicated, copied, sold, resold, visited or otherwise exploited for any commercial purpose without express written consent of Aiwyn.
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
name: Aiwyn
provenance_date: '2026-11-09'
provider_name: Aiwyn
provider_slug: aiwyn
slug: aiwyn-eligibility
source_date: '2026-11-09'
source_filename: aiwyn-eligibility.yml
source_heading: Eligibility
source_page: https://www.aiwyn.ai/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aiwyn\naid: aiwyn\nurl: https://www.aiwyn.ai/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Canadian and US users are referenced; no general country restriction stated.\nentity_types:\n- type: individual\n  text: The Site and Services are intended for people 18 years or older.\n- type: business\n  text: If you are a representative of a company that is a customer of Aiwyn that has signed a separate agreement\n    with Aiwyn (a “ Customer Agreement ”), then to the extent of any conflict between the terms of the Customer\n    Agreement and these Terms of Use,\
  \ the Customer Agreement shall govern.\nrestricted_uses:\n- summary: Commercial use of site\n  text: The Site or any portion of this Site may not be reproduced, duplicated, copied, sold, resold, visited or\n    otherwise exploited for any commercial purpose without express written consent of Aiwyn.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiwyn/eligibility/aiwyn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Aiwyn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Accounting
- Fintech
- Payments
- Practice Management
- Tax
- CPA Firms
- Software-as-a-Service
- Client Experience
---
