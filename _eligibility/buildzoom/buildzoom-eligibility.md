---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Site on behalf of an organization, you represent and warrant that you have authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to create an account or use the Site.
    value: '18'
  restricted_uses:
  - summary: Competitive analysis or competing products
    text: use the Site for competitive analysis, benchmarking, or to develop a competing product or service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain features of the Site may require you to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BuildZoom
provenance_date: '2026-11-09'
provider_name: BuildZoom
provider_slug: buildzoom
slug: buildzoom-eligibility
source_date: '2026-11-09'
source_filename: buildzoom-eligibility.yml
source_heading: Eligibility
source_page: https://www.grydhq.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuildZoom\naid: buildzoom\nurl: https://www.grydhq.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Site on behalf of an organization, you represent and warrant that you have authority\n    to bind that organization to these Terms\nrestricted_uses:\n- summary: Competitive analysis or competing products\n  text: use the Site for competitive analysis, benchmarking, or to develop a competing product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain features\
  \ of the Site may require you to register for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to create an account or use the Site.\n"
source_yaml_url: https://artifacts.apis.io/buildzoom/eligibility/buildzoom-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from BuildZoom's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Building Permits
- Contractors
- Real Estate
- Home Improvement
- Property Data
- Marketplace
---
