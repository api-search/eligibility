---
api_specs:
- filename: checkmails-eu-bulk-api-openapi.yml
  format: yaml
  label: checkmails Bulk API
  slug: checkmails-eu-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmails-eu/openapi/checkmails-eu-bulk-api-openapi.yml
- filename: checkmails-eu-jobs-api-openapi.yml
  format: yaml
  label: checkmails Jobs API
  slug: checkmails-eu-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmails-eu/openapi/checkmails-eu-jobs-api-openapi.yml
- filename: checkmails-eu-verify-api-openapi.yml
  format: yaml
  label: checkmails Verify API
  slug: checkmails-eu-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/checkmails-eu/openapi/checkmails-eu-verify-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Le service est destiné à des usages professionnels (B2B).
    type: business
  - text: lorsque, par exception, le Client a la qualité de consommateur
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No B2C use without legal basis
    text: l'usage du service dans un contexte B2C sans base légale appropriée
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: L'inscription requiert une adresse e-mail valide (vérifiée par code)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: checkmails
provenance_date: '2026-11-09'
provider_name: checkmails
provider_slug: checkmails-eu
slug: checkmails-eu-eligibility
source_date: '2026-11-09'
source_filename: checkmails-eu-eligibility.yml
source_heading: Eligibility
source_page: https://checkmails.eu/cgv
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: checkmails\naid: checkmails-eu\nurl: https://checkmails.eu/cgv\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Le service est destiné à des usages professionnels (B2B).\n- type: individual\n  text: lorsque, par exception, le Client a la qualité de consommateur\nrestricted_uses:\n- summary: No B2C use without legal basis\n  text: l'usage du service dans un contexte B2C sans base légale appropriée\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: L'inscription requiert une adresse e-mail valide (vérifiée par\
  \ code)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/checkmails-eu/eligibility/checkmails-eu-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from checkmails's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- SMTP
- GDPR
- Data Quality
- European Union
- MCP
- Odoo
---
