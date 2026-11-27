---
api_specs:
- filename: azumio-food-recognition-api-api-openapi.yml
  format: yaml
  label: Azumio Food Recognition API
  slug: azumio-food-recognition-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azumio/openapi/azumio-food-recognition-api-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Azumio product features that integrate with the Helix Platform are only available in the US.
  entity_types:
  - text: The Service is only available for your private use and is not intended for commercial use.
    type: individual
  minimum_age:
    text: To use Azumio, you must be at least 13 years old. To use Azumio product features that integrate with the Helix platform, you must be 18 and over.
    value: '13'
  restricted_uses:
  - summary: Minimum age 13
    text: Azumio is not intended for use by persons under the age of 13.
  - summary: Healthy adults only
    text: Our Services are only intended for healthy adults, and please do not use our Services if you suffer from, or might suffer from, any medical condition that may be impaired by diet or exercise.
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
name: Azumio
provenance_date: '2026-11-09'
provider_name: Azumio
provider_slug: azumio
slug: azumio-eligibility
source_date: '2026-11-09'
source_filename: azumio-eligibility.yml
source_heading: Eligibility
source_page: https://azumio.com/privacy-policy-and-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azumio\naid: azumio\nurl: https://azumio.com/privacy-policy-and-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Azumio product features that integrate with the Helix Platform are only available in the US.\nentity_types:\n- type: individual\n  text: The Service is only available for your private use and is not intended for commercial use.\nrestricted_uses:\n- summary: Minimum age 13\n  text: Azumio is not intended for use by persons under the age of 13.\n- summary: Healthy adults only\n  text: Our Services are only intended for healthy adults, and please do not use\
  \ our Services if you suffer from,\n    or might suffer from, any medical condition that may be impaired by diet or exercise.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To use Azumio, you must be at least 13 years old. To use Azumio product features that integrate with the\n    Helix platform, you must be 18 and over.\n"
source_yaml_url: https://artifacts.apis.io/azumio/eligibility/azumio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Azumio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Digital Health
- Nutrition
- Food Recognition
- Machine Learning
- Artificial Intelligence
- Fitness
- Diabetes
---
