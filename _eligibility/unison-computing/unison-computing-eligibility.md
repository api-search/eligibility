---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We provide the Service from the United States. We make no claims that the Service is accessible or appropriate in all locations inside the United States or outside of the United States.
  entity_types:
  - text: you hereby represent that you are of legal age in the jurisdiction from which you are accessing the Service
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have the right to bind such organization to this Agreement
    type: business
  minimum_age:
    text: The Service is not directed to users under the age of 18.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Service, you will be required to provide us with certain information including an email address and password, or to sign in using your Google or Github credentials.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unison Computing
provenance_date: '2026-11-10'
provider_name: Unison Computing
provider_slug: unison-computing
slug: unison-computing-eligibility
source_date: '2026-11-10'
source_filename: unison-computing-eligibility.yml
source_heading: Eligibility
source_page: https://www.unison.cloud/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unison Computing\naid: unison-computing\nurl: https://www.unison.cloud/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We provide the Service from the United States. We make no claims that the Service is accessible or appropriate\n    in all locations inside the United States or outside of the United States.\nentity_types:\n- type: individual\n  text: you hereby represent that you are of legal age in the jurisdiction from which you are accessing the Service\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you\
  \ have the right to bind\n    such organization to this Agreement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Service, you will be required to provide us with certain information including an email address\n    and password, or to sign in using your Google or Github credentials.\nminimum_age:\n  value: '18'\n  text: The Service is not directed to users under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/unison-computing/eligibility/unison-computing-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Unison Computing's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Programming Language
- Cloud Computing
- Developer Tools
- Functional Programming
- Distributed Systems
- Platform-as-a-Service
---
