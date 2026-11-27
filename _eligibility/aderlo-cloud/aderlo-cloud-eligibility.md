---
api_specs:
- filename: aderlo-cloud-api-openapi.json
  format: json
  label: Aderlo Cloud public API API
  slug: aderlo-cloud-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aderlo-cloud/openapi/_original/aderlo-cloud-api-openapi.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Client — a natural person with full legal capacity, a legal person, or an organisational unit without legal personality granted legal capacity by statute
    type: individual
  - text: a legal person, or an organisational unit without legal personality granted legal capacity by statute
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited uses listed in §10
    text: The Client undertakes to use the Hosting Service only in a manner consistent with the law, these Terms and good practices.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: creates an account in the Client Panel, providing the required data (e-mail address, name or company name, address, tax ID — for businesses)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aderlo Cloud
provenance_date: '2026-11-09'
provider_name: Aderlo Cloud
provider_slug: aderlo-cloud
slug: aderlo-cloud-eligibility
source_date: '2026-11-09'
source_filename: aderlo-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://aderlo.cloud/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aderlo Cloud\naid: aderlo-cloud\nurl: https://aderlo.cloud/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Client — a natural person with full legal capacity, a legal person, or an organisational unit without legal\n    personality granted legal capacity by statute\n- type: business\n  text: a legal person, or an organisational unit without legal personality granted legal capacity by statute\nrestricted_uses:\n- summary: Prohibited uses listed in §10\n  text: The Client undertakes to use the Hosting Service only in a manner consistent\
  \ with the law, these Terms and\n    good practices.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: creates an account in the Client Panel, providing the required data (e-mail address, name or company name,\n    address, tax ID — for businesses)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aderlo-cloud/eligibility/aderlo-cloud-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Aderlo Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- WooCommerce
- WordPress
- EU
- Managed
- Cloud
---
