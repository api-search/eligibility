---
api_specs:
- filename: penn-medicine-bulk-data-api-openapi.yml
  format: yaml
  label: Penn Medicine Bulk Data API
  slug: penn-medicine-bulk-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penn-medicine/openapi/penn-medicine-bulk-data-api-openapi.yml
- filename: penn-medicine-patient-access-api-openapi.yml
  format: yaml
  label: Penn Medicine Patient Access API
  slug: penn-medicine-patient-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penn-medicine/openapi/penn-medicine-patient-access-api-openapi.yml
- filename: penn-medicine-provider-directory-api-openapi.yml
  format: yaml
  label: Penn Medicine Provider Directory API
  slug: penn-medicine-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penn-medicine/openapi/penn-medicine-provider-directory-api-openapi.yml
- filename: penn-medicine-smart-api-openapi.yml
  format: yaml
  label: Penn Medicine SMART API
  slug: penn-medicine-smart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/penn-medicine/openapi/penn-medicine-smart-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or offensive submissions
    text: You may not post or transmit any information that is illegal, threatening, libelous, defamatory, obscene, ethnically or racially offensive or discriminatory, profane, infringes the copyright or other intellectual property right of any third party
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
name: Penn Medicine
provenance_date: '2026-11-10'
provider_name: Penn Medicine
provider_slug: penn-medicine
slug: penn-medicine-eligibility
source_date: '2026-11-10'
source_filename: penn-medicine-eligibility.yml
source_heading: Eligibility
source_page: https://www.pennmedicine.org/patient-resources/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Penn Medicine\naid: penn-medicine\nurl: https://www.pennmedicine.org/patient-resources/policies/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or offensive submissions\n  text: You may not post or transmit any information that is illegal, threatening, libelous, defamatory, obscene,\n    ethnically or racially offensive or discriminatory, profane, infringes the copyright or other intellectual property\n    right of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/penn-medicine/eligibility/penn-medicine-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Penn Medicine's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Hospitals
- Academic Medical Center
- FHIR
- SMART on FHIR
- Patient Access
- Provider Directory
- CMS Interoperability
- US Core
- Bulk Data
- Epic
---
