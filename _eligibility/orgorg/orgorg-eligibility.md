---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: located within or a resident of, or a segment of the government of, any country or territory for which the United States maintains trade and economic sanctions or embargoes.
  entity_types:
  - text: You may use OrgOrg only if you can form a legally binding contract with us
    type: individual
  minimum_age:
    text: To use OrgOrg, you must be at least 16 years old, and in some circumstances even older
    value: '16'
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
name: OrgOrg
provenance_date: '2026-11-10'
provider_name: OrgOrg
provider_slug: orgorg
slug: orgorg-eligibility
source_date: '2026-11-10'
source_filename: orgorg-eligibility.yml
source_heading: Eligibility
source_page: https://www.orgorg.com/trust/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OrgOrg\naid: orgorg\nurl: https://www.orgorg.com/trust/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: located within or a resident of, or a segment of the government of, any country or territory for which the\n    United States maintains trade and economic sanctions or embargoes.\nentity_types:\n- type: individual\n  text: You may use OrgOrg only if you can form a legally binding contract with us\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: To use OrgOrg, you must be at least 16\
  \ years old, and in some circumstances even older\n"
source_yaml_url: https://artifacts.apis.io/orgorg/eligibility/orgorg-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from OrgOrg's own page on 2026-11-10.
synthetic: false
tags:
- Organization
- Dashboards
- Remote Teams
- Startup Tools
---
