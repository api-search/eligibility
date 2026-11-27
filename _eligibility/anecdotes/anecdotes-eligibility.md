---
api_specs:
- filename: anecdotes-analysis-rules-api-openapi.yml
  format: yaml
  label: anecdotes Analysis Rules API
  slug: anecdotes-analysis-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-analysis-rules-api-openapi.yml
- filename: anecdotes-authorization-api-openapi.yml
  format: yaml
  label: anecdotes Authorization API
  slug: anecdotes-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-authorization-api-openapi.yml
- filename: anecdotes-create-controls-api-openapi.yml
  format: yaml
  label: anecdotes Create Controls API
  slug: anecdotes-create-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-create-controls-api-openapi.yml
- filename: anecdotes-create-evidence-api-openapi.yml
  format: yaml
  label: anecdotes Create Evidence API
  slug: anecdotes-create-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-create-evidence-api-openapi.yml
- filename: anecdotes-custom-fields-api-openapi.yml
  format: yaml
  label: anecdotes Custom Fields API
  slug: anecdotes-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-custom-fields-api-openapi.yml
- filename: anecdotes-download-evidence-api-openapi.yml
  format: yaml
  label: anecdotes Download Evidence API
  slug: anecdotes-download-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-download-evidence-api-openapi.yml
- filename: anecdotes-findings-api-openapi.yml
  format: yaml
  label: anecdotes Findings API
  slug: anecdotes-findings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-findings-api-openapi.yml
- filename: anecdotes-framework-api-openapi.yml
  format: yaml
  label: anecdotes Framework API
  slug: anecdotes-framework-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-framework-api-openapi.yml
- filename: anecdotes-gated-api-openapi.yml
  format: yaml
  label: anecdotes Gated API
  slug: anecdotes-gated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-gated-api-openapi.yml
- filename: anecdotes-policy-manager-api-openapi.yml
  format: yaml
  label: anecdotes Policy Manager API
  slug: anecdotes-policy-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-policy-manager-api-openapi.yml
- filename: anecdotes-public-api-openapi.yml
  format: yaml
  label: anecdotes Public API
  slug: anecdotes-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-public-api-openapi.yml
- filename: anecdotes-read-controls-api-openapi.yml
  format: yaml
  label: anecdotes Read Controls API
  slug: anecdotes-read-controls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-read-controls-api-openapi.yml
- filename: anecdotes-read-evidence-metadata-api-openapi.yml
  format: yaml
  label: anecdotes Read Evidence Metadata API
  slug: anecdotes-read-evidence-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-read-evidence-metadata-api-openapi.yml
- filename: anecdotes-requirements-api-openapi.yml
  format: yaml
  label: anecdotes Requirements API
  slug: anecdotes-requirements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-requirements-api-openapi.yml
- filename: anecdotes-risk-api-openapi.yml
  format: yaml
  label: anecdotes Risk API
  slug: anecdotes-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-risk-api-openapi.yml
- filename: anecdotes-token-api-openapi.yml
  format: yaml
  label: anecdotes Token API
  slug: anecdotes-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-token-api-openapi.yml
- filename: anecdotes-update-control-metadata-api-openapi.yml
  format: yaml
  label: anecdotes Update Control Metadata API
  slug: anecdotes-update-control-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anecdotes/openapi/anecdotes-update-control-metadata-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating an account, you represent and warrant to us that you are not a bot or other automated methods.
    type: individual
  minimum_age:
    text: This Website and/or service of the Company are not intended for use by minors. In the event that it is brought to our attention that a person under the age of eighteen (18) years makes use of our Website and/or services, we reserve the right to prevent his/her access to the Website.
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: is unlawful or fraudulent or has any unlawful or fraudulent purpose or effect
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, mobile phone number, and any other information requested in order to complete the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: anecdotes
provenance_date: '2026-11-09'
provider_name: anecdotes
provider_slug: anecdotes
slug: anecdotes-eligibility
source_date: '2026-11-09'
source_filename: anecdotes-eligibility.yml
source_heading: Eligibility
source_page: https://www.anecdotes.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: anecdotes\naid: anecdotes\nurl: https://www.anecdotes.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By creating an account, you represent and warrant to us that you are not a bot or other automated methods.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text: is unlawful or fraudulent or has any unlawful or fraudulent purpose or effect\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, a valid email address, mobile phone number, and any\
  \ other information\n    requested in order to complete the registration process.\nminimum_age:\n  value: '18'\n  text: This Website and/or service of the Company are not intended for use by minors. In the event that it is brought\n    to our attention that a person under the age of eighteen (18) years makes use of our Website and/or services,\n    we reserve the right to prevent his/her access to the Website.\n"
source_yaml_url: https://artifacts.apis.io/anecdotes/eligibility/anecdotes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from anecdotes's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Governance
- Risk Management
- Security
- GRC
- Audit
- Evidence
- Continuous Compliance
- FedRAMP
- Artificial Intelligence
- Agents
---
