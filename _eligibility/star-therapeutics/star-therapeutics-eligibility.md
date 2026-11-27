---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Site
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract
    value: null
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
name: Star Therapeutics
provenance_date: '2026-11-10'
provider_name: Star Therapeutics
provider_slug: star-therapeutics
slug: star-therapeutics-eligibility
source_date: '2026-11-10'
source_filename: star-therapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://star-therapeutics.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Star Therapeutics\naid: star-therapeutics\nurl: https://star-therapeutics.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Site\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\n\
  restricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/star-therapeutics/eligibility/star-therapeutics-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Star Therapeutics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biotechnology
- Pharmaceuticals
- Hematology
- Immunology
- Rare Disease
- Antibody Therapeutics
- Clinical Trials
- Life Sciences
- content-api
---
