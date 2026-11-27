---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted parties or located in (or a national of) a country that is subject to a U.S. government embargo
  entity_types:
  - text: If you are accessing or using the Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  - text: If you are accessing or using the Service in your individual capacity, all references to “User” herein mean you, the Customer.
    type: individual
  - text: If the user or licensee of the Service is an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Private Health Information without BAA
    text: Customer agrees not to Submit to the Service any Private Health Information unless (i) the Order Form specifies the applicable Module and (ii) Customer has entered into a Business Associate Agreement (“BAA”) with Cipherome.
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
name: Cipherome
provenance_date: '2026-11-09'
provider_name: Cipherome
provider_slug: cipherome
slug: cipherome-eligibility
source_date: '2026-11-09'
source_filename: cipherome-eligibility.yml
source_heading: Eligibility
source_page: https://www.cipherome.com/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cipherome\naid: cipherome\nurl: https://www.cipherome.com/terms-and-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not listed on any U.S. government list of prohibited or restricted\n    parties or located in (or a national of) a country that is subject to a U.S. government embargo\nentity_types:\n- type: business\n  text: If you are accessing or using the Services on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company\n- type: individual\n  text: If you are accessing\
  \ or using the Service in your individual capacity, all references to “User” herein mean\n    you, the Customer.\n- type: government\n  text: If the user or licensee of the Service is an agency, department, or other entity of the United States Government\nrestricted_uses:\n- summary: No Private Health Information without BAA\n  text: Customer agrees not to Submit to the Service any Private Health Information unless (i) the Order Form specifies\n    the applicable Module and (ii) Customer has entered into a Business Associate Agreement (“BAA”) with Cipherome.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cipherome/eligibility/cipherome-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from Cipherome's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare Data Analysis
- Clinical Research
- Genomic Analysis
- AI Model Training
- Data Transformation
---
