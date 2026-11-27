---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no claims that the Website, Products, or any of its content is accessible or appropriate for use outside of the United States.
  entity_types:
  - text: Our Website and Products are intended for adult use only.
    type: individual
  minimum_age:
    text: 'The Website and Products are not intended for anyone under the age of eighteen (18) years in all states except the following:'
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: THE WEBSITE AND PRODUCTS ARE NOT FAULT-TOLERANT AND ARE NOT DESIGNED, MANUFACTURED, OR INTENDED FOR USE IN CONNECTION WITH HAZARDOUS ENVIRONMENTS REQUIRING FAIL-SAFE PERFORMANCE
  - summary: Direct competitors barred
    text: Company’s direct competitors are prohibited from accessing the Website or Products, except with Company’s prior written consent.
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
name: Harpoon
provenance_date: '2026-11-09'
provider_name: Harpoon
provider_slug: harpoon
slug: harpoon-eligibility
source_date: '2026-11-09'
source_filename: harpoon-eligibility.yml
source_heading: Eligibility
source_page: https://www.harpoon.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harpoon\naid: harpoon\nurl: https://www.harpoon.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no claims that the Website, Products, or any of its content is accessible or appropriate for use\n    outside of the United States.\nentity_types:\n- type: individual\n  text: Our Website and Products are intended for adult use only.\nrestricted_uses:\n- summary: High-risk activities\n  text: THE WEBSITE AND PRODUCTS ARE NOT FAULT-TOLERANT AND ARE NOT DESIGNED, MANUFACTURED, OR INTENDED FOR USE\n    IN CONNECTION WITH HAZARDOUS ENVIRONMENTS REQUIRING FAIL-SAFE PERFORMANCE\n\
  - summary: Direct competitors barred\n  text: Company’s direct competitors are prohibited from accessing the Website or Products, except with Company’s\n    prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'The Website and Products are not intended for anyone under the age of eighteen (18) years in all states\n    except the following:'\n"
source_yaml_url: https://artifacts.apis.io/harpoon/eligibility/harpoon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Harpoon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Kubernetes
- Deployment
- DevOps
- Cloud
- No-Code
- Containers
- Platform Engineering
---
