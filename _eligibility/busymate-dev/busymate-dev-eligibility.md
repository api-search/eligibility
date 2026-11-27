---
api_specs:
- filename: busymate-dev-core-openapi-generated.yml
  format: yaml
  label: Busymate DevTools core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busymate-dev/openapi/_ae-authored/busymate-dev-core-openapi-generated.yml
- filename: busymate-dev-federation-openapi-generated.yml
  format: yaml
  label: Busymate DevTools federation API
  slug: federation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busymate-dev/openapi/_ae-authored/busymate-dev-federation-openapi-generated.yml
- filename: busymate-dev-mcp-openapi-generated.yml
  format: yaml
  label: Busymate DevTools mcp API
  slug: mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busymate-dev/openapi/_ae-authored/busymate-dev-mcp-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old (or the minimum age of digital consent where you live) and able to form a binding contract to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old (or the minimum age of digital consent where you live)
    value: '13'
  restricted_uses:
  - summary: Lawful, authorized monitoring only
    text: You may only inspect traffic on devices, apps, and services that you own or have explicit authorization to monitor.
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
name: Busymate DevTools
provenance_date: '2026-11-09'
provider_name: Busymate DevTools
provider_slug: busymate-dev
slug: busymate-dev-eligibility
source_date: '2026-11-09'
source_filename: busymate-dev-eligibility.yml
source_heading: Eligibility
source_page: https://busymate.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Busymate DevTools\naid: busymate-dev\nurl: https://busymate.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old (or the minimum age of digital consent where you live) and able to form\n    a binding contract to use the Service.\nrestricted_uses:\n- summary: Lawful, authorized monitoring only\n  text: You may only inspect traffic on devices, apps, and services that you own or have explicit authorization\n    to monitor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old (or the minimum age of digital consent where you live)\n"
source_yaml_url: https://artifacts.apis.io/busymate-dev/eligibility/busymate-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Busymate DevTools's own page on 2026-11-09.
synthetic: false
tags:
- Developer Tools
- Network Monitoring
- HTTPS Debugging
- AI Assistance
- Mobile Development
---
