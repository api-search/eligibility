---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human to create an Account.
    type: individual
  - text: Special terms may apply for business or government Accounts
    type: business
  minimum_age:
    text: A User must be at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: No use by sanctioned persons
    text: You may not use GitHub if you are or are working on behalf of a Specially Designated National (SDN) or a person subject to similar blocking or denied party prohibitions administered by a U.S. government agency.
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
name: GitHub CLI
provenance_date: '2026-11-09'
provider_name: GitHub CLI
provider_slug: github-cli
slug: github-cli-eligibility
source_date: '2026-11-09'
source_filename: github-cli-eligibility.yml
source_heading: Eligibility
source_page: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GitHub CLI\naid: github-cli\nurl: https://docs.github.com/en/site-policy/github-terms/github-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human to create an Account.\n- type: business\n  text: Special terms may apply for business or government Accounts\nrestricted_uses:\n- summary: No use by sanctioned persons\n  text: You may not use GitHub if you are or are working on behalf of a Specially Designated National (SDN) or a\n    person subject to similar blocking or denied party prohibitions administered\
  \ by a U.S. government agency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: A User must be at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/github-cli/eligibility/github-cli-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from GitHub CLI's own page on 2026-11-09.
synthetic: false
tags:
- Command Line Interface
- Platform CLI
- Developer Tools
- Version Control
- Open Source
- GitHub
---
