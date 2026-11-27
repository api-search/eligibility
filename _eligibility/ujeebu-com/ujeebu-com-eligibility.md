---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual person who is accessing the Website, using the API, or otherwise accessing or using our Services
    type: individual
  - text: If you are registering an account with us, or using the Services on behalf of an employer or entity, you agree that you are authorized to bind such entity to these Terms of Use.
    type: business
  minimum_age:
    text: By accessing or using the Services you represent and warrant that you are 18 years old or older, or if you are under 18, but no younger than 13 years, that you have a parent's or guardian's permission to access or use our Services.
    value: '13'
  restricted_uses:
  - summary: Illegal activity
    text: is illegal or promotes any illegal activities
  - summary: Interfering with services
    text: You may not interfere with or disrupt the integrity or performance of our Services
  - summary: Reverse engineering
    text: you may not modify, translate, adapt, merge, disassemble, decompile, reverse compile or reverse engineer, or otherwise interfere with or damage any part of the Ujeebu platform
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By registering, you agree that all Registration Data you provide to us is true and accurate and that you will maintain and update this information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ujeebu-com
provenance_date: '2026-11-10'
provider_name: ujeebu-com
provider_slug: ujeebu-com
slug: ujeebu-com-eligibility
source_date: '2026-11-10'
source_filename: ujeebu-com-eligibility.yml
source_heading: Eligibility
source_page: https://ujeebu.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ujeebu-com\naid: ujeebu-com\nurl: https://ujeebu.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual person who is accessing the Website, using the API, or otherwise accessing or using our Services\n- type: business\n  text: If you are registering an account with us, or using the Services on behalf of an employer or entity, you\n    agree that you are authorized to bind such entity to these Terms of Use.\nrestricted_uses:\n- summary: Illegal activity\n  text: is illegal or promotes any illegal activities\n- summary:\
  \ Interfering with services\n  text: You may not interfere with or disrupt the integrity or performance of our Services\n- summary: Reverse engineering\n  text: you may not modify, translate, adapt, merge, disassemble, decompile, reverse compile or reverse engineer,\n    or otherwise interfere with or damage any part of the Ujeebu platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By registering, you agree that all Registration Data you provide to us is true and accurate and that you\n    will maintain and update this information\nminimum_age:\n  value: '13'\n  text: By accessing or using the Services you represent and warrant that you are 18 years old or older, or if you\n    are under 18, but no younger than 13 years, that you have a parent's or guardian's permission to access or use\n    our Services.\n"
source_yaml_url: https://artifacts.apis.io/ujeebu-com/eligibility/ujeebu-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from ujeebu-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- Software-as-a-Service
- Automation
---
