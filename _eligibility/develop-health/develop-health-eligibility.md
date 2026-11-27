---
api_specs:
- filename: develop-health-eligibility-check-api-openapi.yml
  format: yaml
  label: Develop Health Eligibility Check API
  slug: develop-health-eligibility-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/develop-health/openapi/develop-health-eligibility-check-api-openapi.yml
- filename: develop-health-support-program-api-openapi.yml
  format: yaml
  label: Develop Health Support Program API
  slug: develop-health-support-program-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/develop-health/openapi/develop-health-support-program-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  entity_types:
  - text: You represent and warrant that you are 18 years old or older.
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Non-medical advice
    text: Develop Health is not a medical group and does not provide medical advice, care, and/or treatment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Develop Health may contact you by telephone, mail, or e-mail to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Develop Health
provenance_date: '2026-11-09'
provider_name: Develop Health
provider_slug: develop-health
slug: develop-health-eligibility
source_date: '2026-11-09'
source_filename: develop-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.develophealth.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Develop Health\naid: develop-health\nurl: https://www.develophealth.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are 18 years old or older.\nrestricted_uses:\n- summary: Non-medical advice\n  text: Develop Health is not a medical group and does not provide medical\
  \ advice, care, and/or treatment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Develop Health may contact you by telephone, mail, or e-mail to verify your information.\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/develop-health/eligibility/develop-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Develop Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Prior Authorization
- Benefit Verification
- Medication Access
- Insurance
- Health Tech
- Artificial Intelligence
---
