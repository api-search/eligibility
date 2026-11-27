---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for US residents who are at least 18 years old. Persons not US-based residents or under the age of 18 are not permitted to use or register for the Site.
  entity_types:
  - text: By using the Site, you represent and warrant that you are a U.S. resident who is at least 18 years old.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Industry-specific regulated uses
    text: The Site is not tailored to comply with industry-specific regulations (including, but not limited to, the Health Insurance Portability and Accountability Act (HIPAA) and the Federal Information Security Management Act (FISMA)), so if your interactions would be subjected to such laws, you may not use the Site.
  - summary: Commercial endeavors
    text: The Site may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
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
name: Givers
provenance_date: '2026-11-09'
provider_name: Givers
provider_slug: givers
slug: givers-eligibility
source_date: '2026-11-09'
source_filename: givers-eligibility.yml
source_heading: Eligibility
source_page: https://www.givers.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Givers\naid: givers\nurl: https://www.givers.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for US residents who are at least 18 years old. Persons not US-based residents or under\n    the age of 18 are not permitted to use or register for the Site.\nentity_types:\n- type: individual\n  text: By using the Site, you represent and warrant that you are a U.S. resident who is at least 18 years old.\nrestricted_uses:\n- summary: Industry-specific regulated uses\n  text: The Site is not tailored to comply with industry-specific regulations (including,\
  \ but not limited to, the\n    Health Insurance Portability and Accountability Act (HIPAA) and the Federal Information Security Management\n    Act (FISMA)), so if your interactions would be subjected to such laws, you may not use the Site.\n- summary: Commercial endeavors\n  text: The Site may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/givers/eligibility/givers-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Givers's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Caregiving
- Family Caregivers
- Medicaid
- Home Care
- Payments
---
