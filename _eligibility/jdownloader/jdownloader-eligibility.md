---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: AppWork concludes agreements with both consumers and companies. A consumer is a natural person who concludes transactions for a purpose that is not part of their commercial or independent professional activities.
    type: individual
  - text: A company is in contrast a natural or legal person or a legally responsible business partnership that deals with the conclusion of transactions while undertaking their commercial or independent professional activities.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Customer is required to register on AppWork's website in order to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: JDownloader
provenance_date: '2026-11-09'
provider_name: JDownloader
provider_slug: jdownloader
slug: jdownloader-eligibility
source_date: '2026-11-09'
source_filename: jdownloader-eligibility.yml
source_heading: Eligibility
source_page: https://my.jdownloader.org/legal/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JDownloader\naid: jdownloader\nurl: https://my.jdownloader.org/legal/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: AppWork concludes agreements with both consumers and companies. A consumer is a natural person who concludes\n    transactions for a purpose that is not part of their commercial or independent professional activities.\n- type: business\n  text: A company is in contrast a natural or legal person or a legally responsible business partnership that deals\n    with the conclusion of transactions while undertaking\
  \ their commercial or independent professional activities.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Customer is required to register on AppWork's website in order to use the Service.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jdownloader/eligibility/jdownloader-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from JDownloader's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Download-Manager
- File Transfer
- Java
- Freemium
---
