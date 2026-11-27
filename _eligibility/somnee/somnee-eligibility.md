---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories and possessions.
  entity_types:
  - text: The Service is offered and available to users who are 18 years of age or older and reside in the United States or any of its territories and possessions.
    type: individual
  - text: If you are using or accessing the Service on behalf of an entity, such as a company, a sports team or organization, then you represent to us that you have the power and authority to bind such company
    type: business
  minimum_age:
    text: The Service is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Medical eligibility exclusions
    text: (ii) are not pregnant or possibly pregnant, (iii) are not utilizing an active implanted medical device, (iv) do not have a skull defect or any implant in his/her skull, and (v) do not have epilepsy or a history of seizures.
  - summary: Personal non-commercial use only
    text: for your personal and non-commercial use only
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you must create an account by providing us with a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Somnee
provenance_date: '2026-11-10'
provider_name: Somnee
provider_slug: somnee
slug: somnee-eligibility
source_date: '2026-11-10'
source_filename: somnee-eligibility.yml
source_heading: Eligibility
source_page: https://somneesleep.com/pages/privacy-policy-and-terms-of-use#terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Somnee\naid: somnee\nurl: https://somneesleep.com/pages/privacy-policy-and-terms-of-use#terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories and possessions.\nentity_types:\n- type: individual\n  text: The Service is offered and available to users who are 18 years of age or older and reside in the United\n    States or any of its territories and possessions.\n- type: business\n  text: If you are using or accessing the Service on behalf\
  \ of an entity, such as a company, a sports team or organization,\n    then you represent to us that you have the power and authority to bind such company\nrestricted_uses:\n- summary: Medical eligibility exclusions\n  text: (ii) are not pregnant or possibly pregnant, (iii) are not utilizing an active implanted medical device,\n    (iv) do not have a skull defect or any implant in his/her skull, and (v) do not have epilepsy or a history of\n    seizures.\n- summary: Personal non-commercial use only\n  text: for your personal and non-commercial use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you must create an account by providing us with a valid email address.\nminimum_age:\n  value: '18'\n  text: The Service is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/somnee/eligibility/somnee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Somnee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sleep
- Sleep Technology
- Neurotechnology
- Neurostimulation
- Wearables
- Digital Health
- EEG
- Consumer Electronics
---
