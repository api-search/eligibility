---
api_specs:
- filename: airpipe-io-examples-openapi-generated.yml
  format: yaml
  label: Air Pipe Examples API
  slug: examples-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airpipe-io/openapi/_ae-authored/airpipe-io-examples-openapi-generated.yml
- filename: airpipe-io-tutorial-openapi-generated.yml
  format: yaml
  label: Air Pipe tutorial API
  slug: tutorial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airpipe-io/openapi/_ae-authored/airpipe-io-tutorial-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Site may be accessed throughout Australia and internationally.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal Business Purpose only
    text: does not extend to any use outside your Internal Business Purpose, including the activities prohibited by clause 7.1
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to verify the accuracy of the information provided and to reject or suspend account creation if any discrepancies are found.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Air Pipe
provenance_date: '2026-11-09'
provider_name: Air Pipe
provider_slug: airpipe-io
slug: airpipe-io-eligibility
source_date: '2026-11-09'
source_filename: airpipe-io-eligibility.yml
source_heading: Eligibility
source_page: https://airpipe.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Air Pipe\naid: airpipe-io\nurl: https://airpipe.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Site may be accessed throughout Australia and internationally.\nentity_types: []\nrestricted_uses:\n- summary: Internal Business Purpose only\n  text: does not extend to any use outside your Internal Business Purpose, including the activities prohibited by\n    clause 7.1\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to verify the accuracy of the information provided and to reject or suspend account\n    creation if any\
  \ discrepancies are found.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airpipe-io/eligibility/airpipe-io-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Air Pipe's own page on 2026-11-09.
synthetic: false
tags:
- Platform
- Automation
- Artificial Intelligence
- Backend
- Company
---
