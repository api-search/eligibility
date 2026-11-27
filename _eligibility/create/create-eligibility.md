---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: CREATE makes no representation that the Site or its content is appropriate or available for use in locations outside of the United States.
  entity_types:
  - text: If you are using the Site on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least the age of majority in your jurisdiction to submit information through the Site.
    value: age of majority
  restricted_uses:
  - summary: No medical or investment advice
    text: Nothing on this Site constitutes medical or healthcare advice
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
name: CREATE Medicines
provenance_date: '2026-11-09'
provider_name: CREATE Medicines
provider_slug: create
slug: create-eligibility
source_date: '2026-11-09'
source_filename: create-eligibility.yml
source_heading: Eligibility
source_page: https://createmedicines.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CREATE Medicines\naid: create\nurl: https://createmedicines.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: CREATE makes no representation that the Site or its content is appropriate or available for use in locations\n    outside of the United States.\nentity_types:\n- type: business\n  text: If you are using the Site on behalf of an organization, you represent that you have the authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: No medical or investment advice\n  text: Nothing on this Site constitutes medical or healthcare advice\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You must be at least the age of majority in your jurisdiction to submit information through the Site.\n"
source_yaml_url: https://artifacts.apis.io/create/eligibility/create-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CREATE Medicines's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biopharmaceutical
- Cell Therapy
- mRNA
- Oncology
- Immunology
- Biotechnology
---
