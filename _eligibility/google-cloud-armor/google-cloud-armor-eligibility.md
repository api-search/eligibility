---
api_specs:
- filename: google-cloud-armor-securitypolicyrules-api-openapi.yml
  format: yaml
  label: Google Cloud Armor SecurityPolicyRules API
  slug: google-cloud-armor-securitypolicyrules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-armor/openapi/google-cloud-armor-securitypolicyrules-api-openapi.yml
- filename: google-cloud-armor-security-policies-api-openapi.yml
  format: yaml
  label: Google Cloud Armor Security Policies API
  slug: google-cloud-armor-security-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-armor/openapi/google-cloud-armor-security-policies-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: ITAR-controlled materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State
  - summary: HIPAA health information without BAA
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must verify a Domain Email Address or a Domain Name to use GWS Services or Cloud Identity Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Cloud Armor
provenance_date: '2026-11-09'
provider_name: Google Cloud Armor
provider_slug: google-cloud-armor
slug: google-cloud-armor-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-armor-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Armor\naid: google-cloud-armor\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: ITAR-controlled materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n    maintained by the United States Department of State\n- summary: HIPAA health information without BAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an\
  \ executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must verify a Domain Email Address or a Domain Name to use GWS Services or Cloud Identity Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-armor/eligibility/google-cloud-armor-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Google Cloud Armor's own page on 2026-11-09.
synthetic: false
tags:
- DDoS Protection
- Firewall
- Google Cloud
- Security
- WAF
---
