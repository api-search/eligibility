---
api_specs:
- filename: pixee-ai-findings-api-openapi.yml
  format: yaml
  label: Pixee Findings API
  slug: pixee-ai-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-findings-api-openapi.yml
- filename: pixee-ai-fixes-api-openapi.yml
  format: yaml
  label: Pixee Fixes API
  slug: pixee-ai-fixes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-fixes-api-openapi.yml
- filename: pixee-ai-repositories-api-openapi.yml
  format: yaml
  label: Pixee Repositories API
  slug: pixee-ai-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-repositories-api-openapi.yml
- filename: pixee-ai-scans-api-openapi.yml
  format: yaml
  label: Pixee Scans API
  slug: pixee-ai-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-scans-api-openapi.yml
- filename: pixee-ai-webhooks-api-openapi.yml
  format: yaml
  label: Pixee Webhooks API
  slug: pixee-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pixee-ai/openapi/pixee-ai-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity
    type: business
  minimum_age:
    text: (iv) you are eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may only use our services for lawful purposes.
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
name: Pixee
provenance_date: '2026-11-10'
provider_name: Pixee
provider_slug: pixee-ai
slug: pixee-ai-eligibility
source_date: '2026-11-10'
source_filename: pixee-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.pixee.ai/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pixee\naid: pixee-ai\nurl: https://www.pixee.ai/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company, business or other legal entity, you represent\n    that you have the authority to bind such entity\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may only use our services for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (iv) you are eighteen (18) years\
  \ of age or older.\n"
source_yaml_url: https://artifacts.apis.io/pixee-ai/eligibility/pixee-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pixee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Application Security
- AppSec
- Vulnerability-Remediation
- Static Analysis
- SARIF
- Code Security
- Artificial Intelligence
- Developer Tools
---
