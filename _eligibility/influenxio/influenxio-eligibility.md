---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are legally underage, including but not limited to juveniles under the age of twenty (20), please obtain consent from your guardian before using the Services.
    value: '20'
  restricted_uses:
  - summary: Advertising or selling through the Platform without permission
    text: You may not engage in any of the following acts without permission of the Platform. post advertising information or sell products through this Platform;
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
name: Influenxio
provenance_date: '2026-11-09'
provider_name: Influenxio
provider_slug: influenxio
slug: influenxio-eligibility
source_date: '2026-11-09'
source_filename: influenxio-eligibility.yml
source_heading: Eligibility
source_page: https://www.influenxio.com/en-US/terms/company
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Influenxio\naid: influenxio\nurl: https://www.influenxio.com/en-US/terms/company\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Advertising or selling through the Platform without permission\n  text: You may not engage in any of the following acts without permission of the Platform. post advertising information\n    or sell products through this Platform;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '20'\n  text: If you are legally underage, including but not limited\
  \ to juveniles under the age of twenty (20), please\n    obtain consent from your guardian before using the Services.\n"
source_yaml_url: https://artifacts.apis.io/influenxio/eligibility/influenxio-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Influenxio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Influencer Marketing
- Marketing
- Social Media
- Instagram
- Creator Economy
- Affiliate Marketing
- Software-as-a-Service
---
