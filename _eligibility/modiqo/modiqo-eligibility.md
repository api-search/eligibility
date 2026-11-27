---
api_specs:
- filename: modiqo-sales-api-openapi.yml
  format: yaml
  label: Modiqo Sales API
  slug: modiqo-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modiqo/openapi/modiqo-sales-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: By downloading or using the Services, you represent that you are not located in a country subject to a US government embargo and are not listed on any US government list of prohibited or restricted parties.
  entity_types:
  - text: If you accept or agree to this Agreement on behalf of your employer or another legal entity, you represent and warrant that (i) you have full legal authority to bind your employer
    type: business
  - text: 'You represent and warrant that: you are at least 18 years of age (or the age of legal majority in your jurisdiction)'
    type: individual
  minimum_age:
    text: you are at least 18 years of age (or the age of legal majority in your jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Unlawful or journalistic/investigative use
    text: you do not have any motivation, status, or interest which Modiqo may reasonably wish to know about in connection with the Services, including without limitation, if you are using or will or intend to use the Services for any journalistic, investigative, or unlawful purpose
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
name: Modiqo
provenance_date: '2026-11-10'
provider_name: Modiqo
provider_slug: modiqo
slug: modiqo-eligibility
source_date: '2026-11-10'
source_filename: modiqo-eligibility.yml
source_heading: Eligibility
source_page: https://www.modiqo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Modiqo\naid: modiqo\nurl: https://www.modiqo.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: By downloading or using the Services, you represent that you are not located in a country subject to a US\n    government embargo and are not listed on any US government list of prohibited or restricted parties.\nentity_types:\n- type: business\n  text: If you accept or agree to this Agreement on behalf of your employer or another legal entity, you represent\n    and warrant that (i) you have full legal authority to bind your employer\n- type: individual\n  text: 'You represent and\
  \ warrant that: you are at least 18 years of age (or the age of legal majority in your\n    jurisdiction)'\nrestricted_uses:\n- summary: Unlawful or journalistic/investigative use\n  text: you do not have any motivation, status, or interest which Modiqo may reasonably wish to know about in connection\n    with the Services, including without limitation, if you are using or will or intend to use the Services for\n    any journalistic, investigative, or unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age (or the age of legal majority in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/modiqo/eligibility/modiqo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Modiqo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Workflows
- Automation
- Platform
---
