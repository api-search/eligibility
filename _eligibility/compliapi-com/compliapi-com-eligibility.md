---
api_specs:
- filename: compliapi-com-screen-api-openapi.yml
  format: yaml
  label: compliapi-com Screen API
  slug: compliapi-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compliapi-com/openapi/compliapi-com-screen-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: GLBA
    text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register to use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: compliapi-com
provenance_date: '2026-11-09'
provider_name: compliapi-com
provider_slug: compliapi-com
slug: compliapi-com-eligibility
source_date: '2026-11-09'
source_filename: compliapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://compliapi.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: compliapi-com\naid: compliapi-com\nurl: https://compliapi.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability\n    and Accountability Act (HIPAA), Federal Information\
  \ Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: GLBA\n  text: You may not use the Services in a way that would violate the Gramm-Leach-Bliley Act (GLBA).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register to use the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/compliapi-com/eligibility/compliapi-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from compliapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- Sanctions
- Screening
- Fintech
- Cryptocurrency
---
