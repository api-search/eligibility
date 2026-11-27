---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated from facilities in the United States. AnimalBiome makes no representations that the Service is appropriate or available for use in other locations.
  entity_types:
  - text: You must be eighteen (18) years of age or older to agree to these Terms on behalf of yourself or those for whom you have legal authority to agree
    type: individual
  minimum_age:
    text: If your use of the Services includes creating an AnimalBiome account, without submitting a sample or otherwise providing Microbiome Information, you must be thirteen (13) years of age or older to use the Services and accept these Terms.
    value: '13'
  restricted_uses:
  - summary: Export/embargo restriction
    text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
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
name: AnimalBiome
provenance_date: '2026-11-09'
provider_name: AnimalBiome
provider_slug: animalbiome
slug: animalbiome-eligibility
source_date: '2026-11-09'
source_filename: animalbiome-eligibility.yml
source_heading: Eligibility
source_page: https://www.animalbiome.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnimalBiome\naid: animalbiome\nurl: https://www.animalbiome.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated from facilities in the United States. AnimalBiome makes no representations\n    that the Service is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: You must be eighteen (18) years of age or older to agree to these Terms on behalf of yourself or those for\n    whom you have legal authority to agree\nrestricted_uses:\n- summary: Export/embargo\
  \ restriction\n  text: You may not use the Service if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United States government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If your use of the Services includes creating an AnimalBiome account, without submitting a sample or otherwise\n    providing Microbiome Information, you must be thirteen (13) years of age or older to use the Services and accept\n    these Terms.\n"
source_yaml_url: https://artifacts.apis.io/animalbiome/eligibility/animalbiome-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AnimalBiome's own page on 2026-11-09.
synthetic: false
tags:
- Microbiome
- Pet Health
- Veterinary Products
- Probiotics
- Gut Health
---
