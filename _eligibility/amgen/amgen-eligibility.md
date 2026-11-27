---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are based in the State of California in the United States. Amgen makes no representation that the Services are appropriate or available for access or use in other locations.
  entity_types:
  - text: You must be the age of legal majority or older in your place of residence to use the Services.
    type: individual
  - text: IF YOU ARE USING THE SERVICES ON BEHALF OF YOUR EMPLOYER, YOUR ACCEPTANCE OF THESE TERMS IS DEEMED AN AGREEMENT BETWEEN YOUR EMPLOYER AND AMGEN
    type: business
  minimum_age:
    text: You must be the age of legal majority or older in your place of residence to use the Services.
    value: age of legal majority
  restricted_uses:
  - summary: Export control restrictions
    text: You shall not, directly or indirectly, export, re-export or release the Services to, or make the Services accessible from, any jurisdiction or country to which export, re-export or release is prohibited by law
  - summary: Lawful purposes only
    text: You may use the Services for lawful purposes only.
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
name: Amgen
provenance_date: '2026-11-09'
provider_name: Amgen
provider_slug: amgen
slug: amgen-eligibility
source_date: '2026-11-09'
source_filename: amgen-eligibility.yml
source_heading: Eligibility
source_page: https://www.amgen.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amgen\naid: amgen\nurl: https://www.amgen.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are based in the State of California in the United States. Amgen makes no representation that\n    the Services are appropriate or available for access or use in other locations.\nentity_types:\n- type: individual\n  text: You must be the age of legal majority or older in your place of residence to use the Services.\n- type: business\n  text: IF YOU ARE USING THE SERVICES ON BEHALF OF YOUR EMPLOYER, YOUR ACCEPTANCE OF THESE TERMS IS DEEMED AN\
  \ AGREEMENT\n    BETWEEN YOUR EMPLOYER AND AMGEN\nrestricted_uses:\n- summary: Export control restrictions\n  text: You shall not, directly or indirectly, export, re-export or release the Services to, or make the Services\n    accessible from, any jurisdiction or country to which export, re-export or release is prohibited by law\n- summary: Lawful purposes only\n  text: You may use the Services for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of legal majority\n  text: You must be the age of legal majority or older in your place of residence to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/amgen/eligibility/amgen-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Amgen's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Biopharmaceutical
- Oncology
- inflammation
- Cardiovascular
- Rare Disease
- Biosimilars
- Life Sciences
- Fortune 500
---
