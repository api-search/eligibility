---
api_specs:
- filename: perfect-corp-s2s-api-openapi.yml
  format: yaml
  label: Perfect Corp S2s API
  slug: perfect-corp-s2s-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/perfect-corp/openapi/perfect-corp-s2s-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government as sanctioned or embargoed countries
  entity_types:
  - text: If you use the Platform on behalf of an entity, organization or company, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Platform and an authorized representative of your organization.
    value: '18'
  restricted_uses:
  - summary: Biometric/facial data consent
    text: you shall be responsible for collecting consents from any person in the photo to agree Perfect to process the photo for them.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may require you to provide information that may be used to confirm your identity and help ensure the security of your account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Perfect Corp
provenance_date: '2026-11-10'
provider_name: Perfect Corp
provider_slug: perfect-corp
slug: perfect-corp-eligibility
source_date: '2026-11-10'
source_filename: perfect-corp-eligibility.yml
source_heading: Eligibility
source_page: https://www.perfectcorp.com/business/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Perfect Corp\naid: perfect-corp\nurl: https://www.perfectcorp.com/business/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government as sanctioned or embargoed countries\nentity_types:\n- type: business\n  text: If you use the Platform on behalf of an entity, organization or company, you represent and warrant that\n    you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Biometric/facial data consent\n  text: you shall be responsible for collecting consents from any person in the\
  \ photo to agree Perfect to process\n    the photo for them.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may require you to provide information that may be used to confirm your identity and help ensure the\n    security of your account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Platform and an authorized representative of your organization.\n"
source_yaml_url: https://artifacts.apis.io/perfect-corp/eligibility/perfect-corp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Perfect Corp's own page on 2026-11-10.
synthetic: false
tags:
- Beauty
- Skincare
- Cosmetics
- Fashion
- Apparel
- Jewelry
- Watches
- Hair
- Virtual Try-On
- Image Editing
- Generative AI
- Computer Vision
- Augmented Reality
- Visual Commerce
- Artificial Intelligence
- Machine Learning
- Video Generation
- skin-analysis
- MCP
- Agents
- Photo Editing
- Beauty Tech
- Retail
- ar-try-on
- A2A
---
