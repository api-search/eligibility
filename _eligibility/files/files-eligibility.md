---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Service on behalf of an organization, you are agreeing to these Terms for that organization and represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  - text: You affirm that you and any and all users on your account are either 18 years of age or older, and are fully able and competent to enter into and abide by the terms
    type: individual
  minimum_age:
    text: You affirm that you and any and all users on your account are either 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: HIPAA personal health information
    text: use the Service to store personal health information that is regulated by The HIPAA Privacy Rule unless you've also entered into a Business Associate Agreement with Files.com
  - summary: EEA personal information
    text: use the Service to transmit or store personal information about individuals residing in the European Economic Area unless you have signed a data processing agreement with Files.com
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
name: Files.com
provenance_date: '2026-11-09'
provider_name: Files.com
provider_slug: files
slug: files-eligibility
source_date: '2026-11-09'
source_filename: files-eligibility.yml
source_heading: Eligibility
source_page: https://www.files.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Files.com\naid: files\nurl: https://www.files.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Service on behalf of an organization, you are agreeing to these Terms\n    for that organization and represent and warrant that you have the authority to bind that organization to these\n    Terms.\n- type: individual\n  text: You affirm that you and any and all users on your account are either 18 years of age or older, and are fully\n    able and competent to enter into and abide by the terms\n\
  restricted_uses:\n- summary: HIPAA personal health information\n  text: use the Service to store personal health information that is regulated by The HIPAA Privacy Rule unless\n    you've also entered into a Business Associate Agreement with Files.com\n- summary: EEA personal information\n  text: use the Service to transmit or store personal information about individuals residing in the European Economic\n    Area unless you have signed a data processing agreement with Files.com\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You affirm that you and any and all users on your account are either 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/files/eligibility/files-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Files.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- File Transfer
- Cloud Storage
- Automation
- Security
---
