---
api_specs:
- filename: empirical-security-cve-groups-api-openapi.yml
  format: yaml
  label: Empirical Security CVE Groups API
  slug: empirical-security-cve-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empirical-security/openapi/empirical-security-cve-groups-api-openapi.yml
- filename: empirical-security-search-api-openapi.yml
  format: yaml
  label: Empirical Security Search API
  slug: empirical-security-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empirical-security/openapi/empirical-security-search-api-openapi.yml
- filename: empirical-security-cves-api-openapi.yml
  format: yaml
  label: Empirical Security CV Es API
  slug: empirical-security-cves-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/empirical-security/openapi/empirical-security-cves-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: if you are not at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Noncommercial personal use only
    text: Company grants you a non-transferable, non-exclusive, revocable, limited license to use and access the Site solely for your own personal, noncommercial use.
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
name: Empirical Security
provenance_date: '2026-11-09'
provider_name: Empirical Security
provider_slug: empirical-security
slug: empirical-security-eligibility
source_date: '2026-11-09'
source_filename: empirical-security-eligibility.yml
source_heading: Eligibility
source_page: https://www.empiricalsecurity.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Empirical Security\naid: empirical-security\nurl: https://www.empiricalsecurity.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you may not access or use the Site or accept the Terms if you are not at least 18 years old.\nrestricted_uses:\n- summary: Noncommercial personal use only\n  text: Company grants you a non-transferable, non-exclusive, revocable, limited license to use and access the Site\n    solely for your own personal, noncommercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are not at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/empirical-security/eligibility/empirical-security-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Empirical Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Vulnerability Management
- Vulnerability Prioritization
- CVE
- EPSS
- Exploit Prediction
- Threat Intelligence
---
