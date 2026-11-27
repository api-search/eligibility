---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only use the Site if you are a current or prospective customer of Company, or otherwise interested in learning more about Company for a legitimate business purpose.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-legitimate business purposes
    text: The Site may not be used for any unlawful, fraudulent, harassing, objectionable or other non-legitimate business purpose.
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
name: Omnicom Group
provenance_date: '2026-11-10'
provider_name: Omnicom Group
provider_slug: omnicom
slug: omnicom-eligibility
source_date: '2026-11-10'
source_filename: omnicom-eligibility.yml
source_heading: Eligibility
source_page: https://www.omc.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Omnicom Group\naid: omnicom\nurl: https://www.omc.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You may only use the Site if you are a current or prospective customer of Company, or otherwise interested\n    in learning more about Company for a legitimate business purpose.\nrestricted_uses:\n- summary: Non-legitimate business purposes\n  text: The Site may not be used for any unlawful, fraudulent, harassing, objectionable or other non-legitimate\n    business purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/omnicom/eligibility/omnicom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Omnicom Group's own page on 2026-11-10.
synthetic: false
tags:
- Fortune 500
- Advertising
- Marketing
- Holding Company
- Media
- Public Relations
- Marketing Technology
- Commerce
- Data & Analytics
---
