---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated from facilities in India. Arya makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: Only those persons who can form legally binding contracts under Indian Contract Act, 1872 (“1872 Act”) are permitted to use the Services.
    type: individual
  minimum_age:
    text: If You are a minor i.e. under the age of 18 (eighteen) years, You are prohibited from accessing or using Services, except through Your legal guardian or parents who have registered as users on the Website.
    value: '18'
  restricted_uses:
  - summary: Unlawful purpose
    text: for any unlawful purpose
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
name: Arya
provenance_date: '2026-11-09'
provider_name: Arya
provider_slug: arya
slug: arya-eligibility
source_date: '2026-11-09'
source_filename: arya-eligibility.yml
source_heading: Eligibility
source_page: https://arya.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arya\naid: arya\nurl: https://arya.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated from facilities in India. Arya makes no representations that the\n    Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: Only those persons who can form legally binding contracts under Indian Contract Act, 1872 (“1872 Act”) are\n    permitted to use the Services.\nrestricted_uses:\n- summary: Unlawful purpose\n  text: for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If You are a minor i.e. under the age of 18 (eighteen) years, You are prohibited from accessing or using\n    Services, except through Your legal guardian or parents who have registered as users on the Website.\n"
source_yaml_url: https://artifacts.apis.io/arya/eligibility/arya-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arya's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Enterprise
- Banking
- Insurance
- Lending
---
