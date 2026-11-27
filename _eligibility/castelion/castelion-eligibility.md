---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Site are solely directed to individuals, companies, or other entities located in the United States.
  entity_types:
  - text: all materials found on the Site are solely directed to individuals, companies, or other entities located in the United States.
    type: business
  minimum_age:
    text: Any access to or use of the Site by anyone under the age of 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Noncommercial personal use only
    text: you are hereby granted a non-exclusive, limited, non-transferable, freely revocable license to access and use the Site for your personal, noncommercial use only
  - summary: No commercial solicitation
    text: using the Site for any commercial solicitation purposes
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
name: Castelion
provenance_date: '2026-11-09'
provider_name: Castelion
provider_slug: castelion
slug: castelion-eligibility
source_date: '2026-11-09'
source_filename: castelion-eligibility.yml
source_heading: Eligibility
source_page: https://www.castelion.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Castelion\naid: castelion\nurl: https://www.castelion.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Site are solely directed to individuals,\n    companies, or other entities located in the United States.\nentity_types:\n- type: business\n  text: all materials found on the Site are solely directed to individuals, companies, or other entities located\n    in the United States.\nrestricted_uses:\n- summary: Noncommercial personal use only\n  text: you are hereby granted a non-exclusive, limited,\
  \ non-transferable, freely revocable license to access and\n    use the Site for your personal, noncommercial use only\n- summary: No commercial solicitation\n  text: using the Site for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any access to or use of the Site by anyone under the age of 13 is strictly prohibited and in violation of\n    this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/castelion/eligibility/castelion-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Castelion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Defense
- Aerospace
- Hypersonics
- Manufacturing
- Weapons Systems
- National Security
---
