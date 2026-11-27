---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country subject to a U.S. Government embargo or designated as a "terrorist supporting" country
  entity_types:
  - text: You must be at least 18 years old to use Bonsave. By creating an account, you represent that you are at least 18 years of age and have the legal capacity to enter into these Terms.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use Bonsave.
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
name: Bonsave
provenance_date: '2026-11-09'
provider_name: Bonsave
provider_slug: bonsave-app
slug: bonsave-app-eligibility
source_date: '2026-11-09'
source_filename: bonsave-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.bonsave.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonsave\naid: bonsave-app\nurl: https://www.bonsave.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country subject to a U.S. Government embargo or designated as\n    a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use Bonsave. By creating an account, you represent that you are at\n    least 18 years of age and have the legal capacity to enter into these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Bonsave.\n"
source_yaml_url: https://artifacts.apis.io/bonsave-app/eligibility/bonsave-app-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Bonsave's own page on 2026-11-09.
synthetic: false
tags:
- Financial Planning
- Net Worth Tracking
- AI Insights
- Retirement Planning
- Investment Tracking
---
