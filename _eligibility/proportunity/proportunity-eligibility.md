---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site is directed to people residing in the United Kingdom. We do not represent that content available on or through our site is appropriate for use or available in other locations.
  entity_types:
  - text: Whether you are a consumer or a business user
    type: individual
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site'
    type: business
  minimum_age:
    text: Minors or people below 18 years old are not allowed to use this website.
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: we only provide our site for domestic and private use. You agree not to use our site for any commercial or business purposes
  - summary: No advertising or marketing
    text: using this website to engage in any advertising or marketing.
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
name: Proportunity
provenance_date: '2026-11-10'
provider_name: Proportunity
provider_slug: proportunity
slug: proportunity-eligibility
source_date: '2026-11-10'
source_filename: proportunity-eligibility.yml
source_heading: Eligibility
source_page: https://www.proportunity.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Proportunity\naid: proportunity\nurl: https://www.proportunity.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site is directed to people residing in the United Kingdom. We do not represent that content available\n    on or through our site is appropriate for use or available in other locations.\nentity_types:\n- type: individual\n  text: Whether you are a consumer or a business user\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site'\n\
  restricted_uses:\n- summary: Domestic and private use only\n  text: we only provide our site for domestic and private use. You agree not to use our site for any commercial\n    or business purposes\n- summary: No advertising or marketing\n  text: using this website to engage in any advertising or marketing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Minors or people below 18 years old are not allowed to use this website.\n"
source_yaml_url: https://artifacts.apis.io/proportunity/eligibility/proportunity-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Proportunity's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- PropTech
- Mortgage
- Real Estate
- Lending
- Homeownership
- Machine Learning
- United Kingdom
---
