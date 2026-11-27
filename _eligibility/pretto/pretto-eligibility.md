---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - FR
    text: Les services présentés par la PLATEFORME sont destinés aux personnes physiques majeures ainsi qu’aux résidents français.
  entity_types:
  - text: Les services présentés par la PLATEFORME sont destinés aux personnes physiques majeures
    type: individual
  - text: à des UTILISATEURS, particuliers (consommateurs) ou professionnels
    type: business
  minimum_age:
    text: Les services présentés par la PLATEFORME sont destinés aux personnes physiques majeures
    value: adult
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
name: Pretto
provenance_date: '2026-11-10'
provider_name: Pretto
provider_slug: pretto
slug: pretto-eligibility
source_date: '2026-11-10'
source_filename: pretto-eligibility.yml
source_heading: Eligibility
source_page: https://www.pretto.fr/cgu/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pretto\naid: pretto\nurl: https://www.pretto.fr/cgu/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - FR\n  excluded: []\n  text: Les services présentés par la PLATEFORME sont destinés aux personnes physiques majeures ainsi qu’aux résidents\n    français.\nentity_types:\n- type: individual\n  text: Les services présentés par la PLATEFORME sont destinés aux personnes physiques majeures\n- type: business\n  text: à des UTILISATEURS, particuliers (consommateurs) ou professionnels\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adult\n\
  \  text: Les services présentés par la PLATEFORME sont destinés aux personnes physiques majeures\n"
source_yaml_url: https://artifacts.apis.io/pretto/eligibility/pretto-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Pretto's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech Insurtech
- Mortgage
- Lending
- Real Estate
- Brokerage
- France
- Consumer Finance
- Financial Services
---
