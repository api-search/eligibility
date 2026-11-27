---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may not use or engage with the Platform if you are under thirteen (13) years of age. If you use or engage with the Platform and are between the ages of thirteen (13) and eighteen (18) years of age, you must have your parent’s or legal guardian’s permission to do so.
    value: '13'
  restricted_uses:
  - summary: Prohibited content
    text: You acknowledge and agree to not send any prohibited content over the Platform.
  - summary: Protected health information
    text: Any content that implicates and/or references personal health information that is protected by the Health Insurance Portability and Accountability Act
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
name: SpotHopper
provenance_date: '2026-11-10'
provider_name: SpotHopper
provider_slug: spothopper
slug: spothopper-eligibility
source_date: '2026-11-10'
source_filename: spothopper-eligibility.yml
source_heading: Eligibility
source_page: https://www.spothopperapp.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SpotHopper\naid: spothopper\nurl: https://www.spothopperapp.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content\n  text: You acknowledge and agree to not send any prohibited content over the Platform.\n- summary: Protected health information\n  text: Any content that implicates and/or references personal health information that is protected by the Health\n    Insurance Portability and Accountability Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: You may not use or engage with the Platform if you are under thirteen (13) years of age. If you use or engage\n    with the Platform and are between the ages of thirteen (13) and eighteen (18) years of age, you must have your\n    parent’s or legal guardian’s permission to do so.\n"
source_yaml_url: https://artifacts.apis.io/spothopper/eligibility/spothopper-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SpotHopper's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant
- Hospitality
- Marketing
- Websites
- SEO
- Reviews
- Social Media
- Email Marketing
- SMS
- Small Business
---
