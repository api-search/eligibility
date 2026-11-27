---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (g) are not a citizen or resident of, or located in, a geographic area that is subject to U.S. sanctions or embargoes
  entity_types:
  - text: You represent that you have the authority to contractually bind the company, business, or other legal entity (“Client Entity”) on whose behalf you are accepting this Agreement
    type: business
  minimum_age:
    text: are eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Competing or adverse use
    text: are not using the Platform for reasons that are in competition with or adverse to Arc
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
name: Arc
provenance_date: '2026-11-09'
provider_name: Arc
provider_slug: arc
slug: arc-eligibility
source_date: '2026-11-09'
source_filename: arc-eligibility.yml
source_heading: Eligibility
source_page: https://arc.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arc\naid: arc\nurl: https://arc.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (g) are not a citizen or resident of, or located in, a geographic area that is subject to U.S. sanctions\n    or embargoes\nentity_types:\n- type: business\n  text: You represent that you have the authority to contractually bind the company, business, or other legal entity\n    (“Client Entity”) on whose behalf you are accepting this Agreement\nrestricted_uses:\n- summary: Competing or adverse use\n  text: are not using the Platform for reasons that are in competition with or adverse to Arc\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: are eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/arc/eligibility/arc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Hiring
- Talent Marketplace
- Remote Work
- Developers
- Freelance
---
