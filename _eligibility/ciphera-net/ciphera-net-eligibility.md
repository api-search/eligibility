---
api_specs:
- filename: ciphera-net-openapi-generated.yml
  format: yaml
  label: Ciphera API
  slug: ciphera-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciphera-net/openapi/_ae-authored/ciphera-net-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available to individuals who are at least 16 years of age.
    type: individual
  - text: If you are accepting these Terms on behalf of an organization, you represent and warrant that you have the authority to bind that organization.
    type: business
  minimum_age:
    text: The Services are available to individuals who are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Unlawful content
    text: Upload, share, store, or distribute any content that is unlawful under applicable law
  - summary: Malware
    text: Distribute malware, viruses, ransomware, or any other harmful or malicious code
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
name: Ciphera
provenance_date: '2026-11-09'
provider_name: Ciphera
provider_slug: ciphera-net
slug: ciphera-net-eligibility
source_date: '2026-11-09'
source_filename: ciphera-net-eligibility.yml
source_heading: Eligibility
source_page: https://ciphera.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ciphera\naid: ciphera-net\nurl: https://ciphera.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available to individuals who are at least 16 years of age.\n- type: business\n  text: If you are accepting these Terms on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization.\nrestricted_uses:\n- summary: Unlawful content\n  text: Upload, share, store, or distribute any content that is unlawful under applicable law\n- summary: Malware\n  text: Distribute\
  \ malware, viruses, ransomware, or any other harmful or malicious code\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services are available to individuals who are at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/ciphera-net/eligibility/ciphera-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Ciphera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Security
- Europe
- Open Source
---
