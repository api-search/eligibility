---
api_specs:
- filename: konsentus-psp-checking-service-api-openapi.yml
  format: yaml
  label: Konsentus PSP Checking Service API
  slug: konsentus-psp-checking-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/konsentus/openapi/konsentus-psp-checking-service-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - source: https://www.konsentus.com/terms-conditions
    text: This website is intended for use by individuals in the course of trade (i.e. business use) only, and not for use by consumers.
    type: business
  minimum_age:
    text: Our website is not intended for use by minors.
    value: null
  restricted_uses:
  - summary: Minors
    text: Our website is not intended for use by minors. The use of any of our interactive services by a minor is subject to the consent of their parent or guardian.
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
name: Konsentus
provenance_date: '2026-11-09'
provider_name: Konsentus
provider_slug: konsentus
slug: konsentus-eligibility
source_date: '2026-11-09'
source_filename: konsentus-eligibility.yml
source_heading: Eligibility
source_page: https://www.konsentus.com/acceptable-use-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Konsentus\naid: konsentus\nurl: https://www.konsentus.com/acceptable-use-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.konsentus.com/acceptable-use-policy\n  - https://www.konsentus.com/terms-conditions\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This website is intended for use by individuals in the course of trade (i.e. business use) only, and not\n    for use by consumers.\n  source: https://www.konsentus.com/terms-conditions\nrestricted_uses:\n- summary: Minors\n  text: Our website is not intended for use by minors. The use of any of our\
  \ interactive services by a minor is\n    subject to the consent of their parent or guardian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Our website is not intended for use by minors.\n"
source_yaml_url: https://artifacts.apis.io/konsentus/eligibility/konsentus-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Konsentus's own page on 2026-11-09.
synthetic: false
tags:
- Open Banking
- Open Finance
- PSD2
- PSD3
- FIDA
- TPP Verification
- Identity
- eIDAS
- Trust Services
- Regulatory Checking
- Financial Services
---
