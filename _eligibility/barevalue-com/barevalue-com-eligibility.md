---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: not located in a country that is subject to a U.S. Government embargo or designated by the U.S. Government as a "terrorist supporting" country
  entity_types:
  - text: over eighteen (18) years of age or the age of majority in your jurisdiction, whichever is greater
    type: individual
  - text: If you are entering into the Terms on behalf of a company or other legal entity, you represent and warrant that you are authorized and lawfully able to bind such entity to the Terms
    type: business
  minimum_age:
    text: over eighteen (18) years of age or the age of majority in your jurisdiction, whichever is greater
    value: '18'
  restricted_uses:
  - summary: Sanctioned or restricted parties
    text: not listed on any U.S. Government list of prohibited or restricted parties, including the Specially Designated Nationals List.
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
name: Barevalue
provenance_date: '2026-11-09'
provider_name: Barevalue
provider_slug: barevalue-com
slug: barevalue-com-eligibility
source_date: '2026-11-09'
source_filename: barevalue-com-eligibility.yml
source_heading: Eligibility
source_page: https://barevalue.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Barevalue\naid: barevalue-com\nurl: https://barevalue.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: not located in a country that is subject to a U.S. Government embargo or designated by the U.S. Government\n    as a \"terrorist supporting\" country\nentity_types:\n- type: individual\n  text: over eighteen (18) years of age or the age of majority in your jurisdiction, whichever is greater\n- type: business\n  text: If you are entering into the Terms on behalf of a company or other legal entity, you represent and warrant\n    that you are authorized and lawfully able to\
  \ bind such entity to the Terms\nrestricted_uses:\n- summary: Sanctioned or restricted parties\n  text: not listed on any U.S. Government list of prohibited or restricted parties, including the Specially Designated\n    Nationals List.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: over eighteen (18) years of age or the age of majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/barevalue-com/eligibility/barevalue-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Barevalue's own page on 2026-11-09.
synthetic: false
tags:
- Audio
- Video
- Podcasts
- Editing
- Artificial Intelligence
---
