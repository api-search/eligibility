---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and operated from the U.S. If you access them from another jurisdiction, you are responsible for compliance with local laws.
  entity_types:
  - text: Our Services are offered only to individuals who are 18 years of age or older and capable of forming a binding contract.
    type: individual
  minimum_age:
    text: Our Services are offered only to individuals who are 18 years of age or older and capable of forming a binding contract.
    value: '18'
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
name: AMZ Vault
provenance_date: '2026-11-09'
provider_name: AMZ Vault
provider_slug: amz-vault-com
slug: amz-vault-com-eligibility
source_date: '2026-11-09'
source_filename: amz-vault-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.amz-vault.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AMZ Vault\naid: amz-vault-com\nurl: https://www.amz-vault.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and operated from the U.S. If you access them from another jurisdiction, you\n    are responsible for compliance with local laws.\nentity_types:\n- type: individual\n  text: Our Services are offered only to individuals who are 18 years of age or older and capable of forming a binding\n    contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our\
  \ Services are offered only to individuals who are 18 years of age or older and capable of forming a binding\n    contract.\n"
source_yaml_url: https://artifacts.apis.io/amz-vault-com/eligibility/amz-vault-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from AMZ Vault's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- E-Commerce
- Amazon
- PPC
- Artificial Intelligence
- Software-as-a-Service
---
