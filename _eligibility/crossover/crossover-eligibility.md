---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country, and you are not listed on any U.S. Government list of prohibited or restricted parties.
  entity_types:
  - text: 'By using the Services, you represent and warrant that: You are a natural person'
    type: individual
  minimum_age:
    text: Our Services are intended solely to be accessed by Users and Candidates who are thirteen (13) years of age or older (or other age as required by local law)
    value: '13'
  restricted_uses:
  - summary: No operating accounts for others
    text: Register or operate a Candidate account on behalf of or for the benefit of any person other than yourself
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your account will be created and maintained with your real identity
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crossover
provenance_date: '2026-11-09'
provider_name: Crossover
provider_slug: crossover
slug: crossover-eligibility
source_date: '2026-11-09'
source_filename: crossover-eligibility.yml
source_heading: Eligibility
source_page: https://ed.crossover.com/website-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crossover\naid: crossover\nurl: https://ed.crossover.com/website-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent you are not located in a country that is subject to a U.S. Government embargo, or that has\n    been designated by the U.S. Government as a “terrorist supporting” country, and you are not listed on any U.S.\n    Government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: 'By using the Services, you represent and warrant that: You are a natural person'\nrestricted_uses:\n- summary: No operating accounts for others\n\
  \  text: Register or operate a Candidate account on behalf of or for the benefit of any person other than yourself\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your account will be created and maintained with your real identity\nminimum_age:\n  value: '13'\n  text: Our Services are intended solely to be accessed by Users and Candidates who are thirteen (13) years of age\n    or older (or other age as required by local law)\n"
source_yaml_url: https://artifacts.apis.io/crossover/eligibility/crossover-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Crossover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Recruiting
- Remote Work
- Artificial Intelligence
- Talent Marketplace
---
