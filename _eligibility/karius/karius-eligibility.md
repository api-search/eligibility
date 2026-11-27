---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to this Website from jurisdictions where the contents of this Website are illegal or penalized is prohibited.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Assistant not for diagnosis or treatment
    text: It is not intended for diagnosis, treatment, or patient-specific recommendations.
  - summary: No personal data uploads to Assistant
    text: Upload personal data to Karius Assistant, including but not limited to identifiable patient data.
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
name: Karius
provenance_date: '2026-11-09'
provider_name: Karius
provider_slug: karius
slug: karius-eligibility
source_date: '2026-11-09'
source_filename: karius-eligibility.yml
source_heading: Eligibility
source_page: https://kariusdx.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Karius\naid: karius\nurl: https://kariusdx.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to this Website from jurisdictions where the contents of this Website are illegal or penalized is\n    prohibited.\nentity_types: []\nrestricted_uses:\n- summary: Assistant not for diagnosis or treatment\n  text: It is not intended for diagnosis, treatment, or patient-specific recommendations.\n- summary: No personal data uploads to Assistant\n  text: Upload personal data to Karius Assistant, including but not limited to identifiable patient data.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/karius/eligibility/karius-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from Karius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Diagnostics
- Genomics
- Infectious Disease
- Healthcare
- Metagenomics
- Laboratory
- Precision Medicine
---
