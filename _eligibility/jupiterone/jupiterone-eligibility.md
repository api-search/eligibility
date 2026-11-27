---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Site.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Site.
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: JupiterOne grants you a limited, revocable license to access and use the Site solely for non-commercial purposes
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
name: JupiterOne
provenance_date: '2026-11-09'
provider_name: JupiterOne
provider_slug: jupiterone
slug: jupiterone-eligibility
source_date: '2026-11-09'
source_filename: jupiterone-eligibility.yml
source_heading: Eligibility
source_page: https://www.jupiterone.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JupiterOne\naid: jupiterone\nurl: https://www.jupiterone.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Site.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Non-commercial use only\n  text: JupiterOne grants you a limited, revocable license to access and use the Site solely for non-commercial\n\
  \    purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/jupiterone/eligibility/jupiterone-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from JupiterOne's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- CAASM
- Cyber Asset Management
- Attack Surface Management
- Cloud Security
- Graph
- GraphQL
- Compliance
- Asset Intelligence
---
