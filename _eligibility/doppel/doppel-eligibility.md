---
api_specs:
- filename: doppel-alerts-api-openapi.yml
  format: yaml
  label: Doppel Alerts API
  slug: doppel-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-alerts-api-openapi.yml
- filename: doppel-brands-api-openapi.yml
  format: yaml
  label: Doppel Brands API
  slug: doppel-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-brands-api-openapi.yml
- filename: doppel-hrm-api-openapi.yml
  format: yaml
  label: Doppel Hrm API
  slug: doppel-hrm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-hrm-api-openapi.yml
- filename: doppel-phishing-simulation-api-openapi.yml
  format: yaml
  label: Doppel Phishing Simulation API
  slug: doppel-phishing-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-phishing-simulation-api-openapi.yml
- filename: doppel-protected-assets-api-openapi.yml
  format: yaml
  label: Doppel Protected Assets API
  slug: doppel-protected-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-protected-assets-api-openapi.yml
- filename: doppel-reports-api-openapi.yml
  format: yaml
  label: Doppel Reports API
  slug: doppel-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-reports-api-openapi.yml
- filename: doppel-scan-api-openapi.yml
  format: yaml
  label: Doppel Scan API
  slug: doppel-scan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-scan-api-openapi.yml
- filename: doppel-iocs-api-openapi.yml
  format: yaml
  label: Doppel Iocs API
  slug: doppel-iocs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-iocs-api-openapi.yml
- filename: doppel-reports-deprecated-api-openapi.yml
  format: yaml
  label: Doppel reports (deprecated) API
  slug: doppel-reports-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-reports-deprecated-api-openapi.yml
- filename: doppel-sms-responses-api-openapi.yml
  format: yaml
  label: Doppel Sms Responses API
  slug: doppel-sms-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-sms-responses-api-openapi.yml
- filename: doppel-urls-api-openapi.yml
  format: yaml
  label: Doppel URLS API
  slug: doppel-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doppel/openapi/doppel-urls-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for users who are at least 18 years old.
    type: individual
  - text: you are agreeing to these Terms on behalf of yourself and such Organization
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated data uses
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (“HIPAA”), Federal Information Security Management Act (“FISMA”), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
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
name: Doppel
provenance_date: '2026-11-09'
provider_name: Doppel
provider_slug: doppel
slug: doppel-eligibility
source_date: '2026-11-09'
source_filename: doppel-eligibility.yml
source_heading: Eligibility
source_page: https://www.doppel.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doppel\naid: doppel\nurl: https://www.doppel.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old.\n- type: business\n  text: you are agreeing to these Terms on behalf of yourself and such Organization\nrestricted_uses:\n- summary: Industry-regulated data uses\n  text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and\n    Accountability Act (“HIPAA”), Federal Information Security\
  \ Management Act (“FISMA”), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n"
source_yaml_url: https://artifacts.apis.io/doppel/eligibility/doppel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Doppel's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Digital Risk Protection
- Social Engineering Defense
- Brand Protection
- Anti-Phishing
- Threat Intelligence
- Human Risk Management
- Takedowns
- Artificial Intelligence
- Social-Engineering
- Defense
---
