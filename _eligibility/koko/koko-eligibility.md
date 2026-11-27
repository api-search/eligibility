---
api_specs:
- filename: koko-countries-api-openapi.yml
  format: yaml
  label: Koko Countries API
  slug: koko-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koko/openapi/koko-countries-api-openapi.yml
- filename: koko-helplines-api-openapi.yml
  format: yaml
  label: Koko Helplines API
  slug: koko-helplines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koko/openapi/koko-helplines-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Koko from its facilities in the United States of America. Koko makes no representations that the Services are appropriate or available for use in other locations.
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH KOKO.
    value: null
  restricted_uses:
  - summary: Not for medical advice or clinical services
    text: (l) may constitute the receipt or provision of clinical services, including but not limited to the practice of medicine or psychology
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
name: Koko
provenance_date: '2026-11-09'
provider_name: Koko
provider_slug: koko
slug: koko-eligibility
source_date: '2026-11-09'
source_filename: koko-eligibility.yml
source_heading: Eligibility
source_page: https://kokocares.org/terms-of-use-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Koko\naid: koko\nurl: https://kokocares.org/terms-of-use-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Koko from its facilities in the United States of America. Koko\n    makes no representations that the Services are appropriate or available for use in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Not for medical advice or clinical services\n  text: (l) may constitute the receipt or provision of clinical services, including but not limited to the practice\n    of medicine or psychology\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH KOKO.\n"
source_yaml_url: https://artifacts.apis.io/koko/eligibility/koko-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Koko's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Crisis Support
- Suicide Prevention
- Trust and Safety
- Content Moderation
- Non-Profit
- Health
- Helplines
---
