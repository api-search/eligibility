---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The terms "you", "your", "User" or "customer" shall refer to any individual or entity who accepts these Terms of Use by using the Site or the Services found at the Site.
    type: individual
  - text: If you are agreeing to these Terms of Use on behalf of a corporate entity, you represent and warrant that you have the legal authority to bind such corporate entity to these Terms of Use
    type: business
  minimum_age:
    text: Account Holders must be 18 years or older
    value: '18'
  restricted_uses:
  - summary: Hazardous and prohibited waste
    text: Customer will not deliver for collection any dangerous materials including but not limited to the Prohibited Waste listed herein.
  - summary: Previously removed users
    text: You agree not to create an account or use our Services if you have been previously removed by the Company, or if you have been previously barred from the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An account is available only to users who have completed the information required by the Site's enrollment form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sourgum
provenance_date: '2026-11-10'
provider_name: Sourgum
provider_slug: sourgum
slug: sourgum-eligibility
source_date: '2026-11-10'
source_filename: sourgum-eligibility.yml
source_heading: Eligibility
source_page: https://www.sourgum.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sourgum\naid: sourgum\nurl: https://www.sourgum.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The terms \"you\", \"your\", \"User\" or \"customer\" shall refer to any individual or entity who accepts these\n    Terms of Use by using the Site or the Services found at the Site.\n- type: business\n  text: If you are agreeing to these Terms of Use on behalf of a corporate entity, you represent and warrant that\n    you have the legal authority to bind such corporate entity to these Terms of Use\nrestricted_uses:\n\
  - summary: Hazardous and prohibited waste\n  text: Customer will not deliver for collection any dangerous materials including but not limited to the Prohibited\n    Waste listed herein.\n- summary: Previously removed users\n  text: You agree not to create an account or use our Services if you have been previously removed by the Company,\n    or if you have been previously barred from the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An account is available only to users who have completed the information required by the Site's enrollment\n    form.\nminimum_age:\n  value: '18'\n  text: Account Holders must be 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/sourgum/eligibility/sourgum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Sourgum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Waste Management
- Recycling
- Technology
- Sustainability
---
