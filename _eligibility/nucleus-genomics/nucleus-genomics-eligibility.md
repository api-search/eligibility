---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is operated in the United States, and is primarily intended for users located in the United States. Nucleus makes no representation that the Services or Products are appropriate or available for use beyond the United States.
  entity_types:
  - text: The Services and Products are offered and made available to individuals who are 18 years or older.
    type: individual
  minimum_age:
    text: By using the Services, including this Website, or Products, you represent and warrant that you are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Sex selection (India)
    text: Nucleus and its affiliates do not design, configure, or intend their Services or Products to enable sex selection in any form.
  - summary: Genetic testing where unlawful
    text: If you reside in a location where genetic testing requires authorization or is unlawful, you must not use our Services or order our Products.
  - summary: New York DNA samples
    text: Nucleus does not accept DNA samples that are collected in or returned from the state of New York.
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
name: Nucleus Genomics
provenance_date: '2026-11-10'
provider_name: Nucleus Genomics
provider_slug: nucleus-genomics
slug: nucleus-genomics-eligibility
source_date: '2026-11-10'
source_filename: nucleus-genomics-eligibility.yml
source_heading: Eligibility
source_page: https://mynucleus.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nucleus Genomics\naid: nucleus-genomics\nurl: https://mynucleus.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is operated in the United States, and is primarily intended for users located in the United\n    States. Nucleus makes no representation that the Services or Products are appropriate or available for use beyond\n    the United States.\nentity_types:\n- type: individual\n  text: The Services and Products are offered and made available to individuals who are 18 years or older.\nrestricted_uses:\n- summary: Sex selection (India)\n  text:\
  \ Nucleus and its affiliates do not design, configure, or intend their Services or Products to enable sex\n    selection in any form.\n- summary: Genetic testing where unlawful\n  text: If you reside in a location where genetic testing requires authorization or is unlawful, you must not use\n    our Services or order our Products.\n- summary: New York DNA samples\n  text: Nucleus does not accept DNA samples that are collected in or returned from the state of New York.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Services, including this Website, or Products, you represent and warrant that you are at least\n    18 years old.\n"
source_yaml_url: https://artifacts.apis.io/nucleus-genomics/eligibility/nucleus-genomics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Nucleus Genomics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Genomics
- Health
- Consumer Genetics
- Whole Genome Sequencing
- Fertility
- IVF
- Carrier Screening
- Precision Medicine
- Biotechnology
---
