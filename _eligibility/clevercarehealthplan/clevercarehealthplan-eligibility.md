---
api_specs:
- filename: clevercarehealthplan-drug-formulary-api-openapi.yml
  format: yaml
  label: Clever Care Health Plan Drug Formulary API
  slug: clevercarehealthplan-drug-formulary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevercarehealthplan/openapi/clevercarehealthplan-drug-formulary-api-openapi.yml
- filename: clevercarehealthplan-patient-access-api-openapi.yml
  format: yaml
  label: Clever Care Health Plan Patient Access API
  slug: clevercarehealthplan-patient-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevercarehealthplan/openapi/clevercarehealthplan-patient-access-api-openapi.yml
- filename: clevercarehealthplan-provider-directory-api-openapi.yml
  format: yaml
  label: Clever Care Health Plan Provider Directory API
  slug: clevercarehealthplan-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clevercarehealthplan/openapi/clevercarehealthplan-provider-directory-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Clever Care controls and operates this site from its headquarters in Arcadia, California, USA, and makes no representation that these materials are appropriate or available for use in locations outside the jurisdiction of the state of California.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal health information on social media
    text: Users shall not post any personal or private health information, such as policy numbers, claim numbers, phone numbers, personal e-mail addresses, or any unique identifying information on a Clever Care social media page.
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
name: Clever Care Health Plan
provenance_date: '2026-11-09'
provider_name: Clever Care Health Plan
provider_slug: clevercarehealthplan
slug: clevercarehealthplan-eligibility
source_date: '2026-11-09'
source_filename: clevercarehealthplan-eligibility.yml
source_heading: Eligibility
source_page: https://clevercarehealthplan.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clever Care Health Plan\naid: clevercarehealthplan\nurl: https://clevercarehealthplan.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Clever Care controls and operates this site from its headquarters in Arcadia, California, USA, and makes\n    no representation that these materials are appropriate or available for use in locations outside the jurisdiction\n    of the state of California.\nentity_types: []\nrestricted_uses:\n- summary: No personal health information on social media\n  text: Users shall not post any personal or private health information, such\
  \ as policy numbers, claim numbers,\n    phone numbers, personal e-mail addresses, or any unique identifying information on a Clever Care social media\n    page.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clevercarehealthplan/eligibility/clevercarehealthplan-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Clever Care Health Plan's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health Insurance
- Medicare Advantage
- FHIR
- Interoperability
- Patient Access
- Provider Directory
- Drug Formulary
- CMS-9115-F
---
