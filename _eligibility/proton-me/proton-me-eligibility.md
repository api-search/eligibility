---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are provided exclusively to individuals who are at least 13 years of age, and even then, only to minors who have obtained parental or legal guardian consent to open and maintain an Account.
    type: individual
  - text: Certain Proton subscription plans are intended for companies, businesses, and organizations.
    type: business
  minimum_age:
    text: The Services are provided exclusively to individuals who are at least 13 years of age, and even then, only to minors who have obtained parental or legal guardian consent to open and maintain an Account.
    value: '13'
  restricted_uses:
  - summary: Illegal content and abuse
    text: Accessing/sharing/downloading/uploading illegal content, including but not limited to Child Sexual Abuse Material (CSAM) or content related to CSAM;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: For business plans, Proton may request additional information or documentation, such as a VAT or GST number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Proton Drive
provenance_date: '2026-11-10'
provider_name: Proton Drive
provider_slug: proton-me
slug: proton-me-eligibility
source_date: '2026-11-10'
source_filename: proton-me-eligibility.yml
source_heading: Eligibility
source_page: https://proton.me/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Proton Drive\naid: proton-me\nurl: https://proton.me/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are provided exclusively to individuals who are at least 13 years of age, and even then, only\n    to minors who have obtained parental or legal guardian consent to open and maintain an Account.\n- type: business\n  text: Certain Proton subscription plans are intended for companies, businesses, and organizations.\nrestricted_uses:\n- summary: Illegal content and abuse\n  text: Accessing/sharing/downloading/uploading\
  \ illegal content, including but not limited to Child Sexual Abuse\n    Material (CSAM) or content related to CSAM;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: For business plans, Proton may request additional information or documentation, such as a VAT or GST number.\nminimum_age:\n  value: '13'\n  text: The Services are provided exclusively to individuals who are at least 13 years of age, and even then, only\n    to minors who have obtained parental or legal guardian consent to open and maintain an Account.\n"
source_yaml_url: https://artifacts.apis.io/proton-me/eligibility/proton-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Proton Drive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Storage
- Privacy
- Encryption
- File Sharing
- Secure Collaboration
---
