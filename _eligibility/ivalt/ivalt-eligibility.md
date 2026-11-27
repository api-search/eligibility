---
api_specs:
- filename: ivalt-openapi-generated.yml
  format: yaml
  label: iVALT API
  slug: ivalt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ivalt/openapi/_ae-authored/ivalt-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least 18 years of age and have the legal authority to enter into these Terms on behalf of yourself
    type: individual
  - text: If you are accessing the Site or Services on behalf of a company or other legal entity, you represent that you have authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you represent that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful use of the Site
    text: Violates any applicable federal, state, local, or international law or regulation
  - summary: Spam and unsolicited communications
    text: Transmits unsolicited commercial communications or spam
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
name: iVALT
provenance_date: '2026-11-09'
provider_name: iVALT
provider_slug: ivalt
slug: ivalt-eligibility
source_date: '2026-11-09'
source_filename: ivalt-eligibility.yml
source_heading: Eligibility
source_page: https://www.ivalt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: iVALT\naid: ivalt\nurl: https://www.ivalt.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least 18 years of age and have the legal authority to enter into these Terms\n    on behalf of yourself\n- type: business\n  text: If you are accessing the Site or Services on behalf of a company or other legal entity, you represent that\n    you have authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Unlawful use of the Site\n  text: Violates any applicable federal, state, local,\
  \ or international law or regulation\n- summary: Spam and unsolicited communications\n  text: Transmits unsolicited commercial communications or spam\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/ivalt/eligibility/ivalt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from iVALT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Identity
- Security
- HumanAuthority
---
