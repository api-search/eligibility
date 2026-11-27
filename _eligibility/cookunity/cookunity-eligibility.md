---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are available only to and may only be used by individuals in the contiguous United States of America, excluding Alaska, Hawaii, Puerto Rico, and other U.S. Territories
  entity_types:
  - text: Our Services are available only to and may only be used by individuals in the contiguous United States of America
    type: individual
  minimum_age:
    text: (2) Are at least 18 years old;
    value: '18'
  restricted_uses:
  - summary: Not for minors
    text: The Services are not intended for use by minors.
  - summary: Not for medical emergencies
    text: USE OF THE SERVICES IS NOT FOR MEDICAL EMERGENCIES. IF YOU THINK YOU HAVE A MEDICAL EMERGENCY, CALL 911.
  - summary: Alcohol purchases require age 21+
    text: You must be, and you must represent, warrant, and certify that you are, at least 21 years of age to purchase any alcoholic beverages.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: As a part of the verification process, CookUnity may require you to provide additional identification information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cookunity
provenance_date: '2026-11-09'
provider_name: Cookunity
provider_slug: cookunity
slug: cookunity-eligibility
source_date: '2026-11-09'
source_filename: cookunity-eligibility.yml
source_heading: Eligibility
source_page: https://www.cookunity.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cookunity\naid: cookunity\nurl: https://www.cookunity.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are available only to and may only be used by individuals in the contiguous United States of\n    America, excluding Alaska, Hawaii, Puerto Rico, and other U.S. Territories\nentity_types:\n- type: individual\n  text: Our Services are available only to and may only be used by individuals in the contiguous United States of\n    America\nrestricted_uses:\n- summary: Not for minors\n  text: The Services are not intended for use by minors.\n\
  - summary: Not for medical emergencies\n  text: USE OF THE SERVICES IS NOT FOR MEDICAL EMERGENCIES. IF YOU THINK YOU HAVE A MEDICAL EMERGENCY, CALL 911.\n- summary: Alcohol purchases require age 21+\n  text: You must be, and you must represent, warrant, and certify that you are, at least 21 years of age to purchase\n    any alcoholic beverages.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: As a part of the verification process, CookUnity may require you to provide additional identification information.\nminimum_age:\n  value: '18'\n  text: (2) Are at least 18 years old;\n"
source_yaml_url: https://artifacts.apis.io/cookunity/eligibility/cookunity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Cookunity's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Meal Delivery
- Food
- Marketplace
- Subscription
- Consumer
- Chef Marketplace
- Meal Kit
---
