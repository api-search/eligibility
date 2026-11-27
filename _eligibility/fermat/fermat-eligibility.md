---
api_specs:
- filename: fermat-pixel-asyncapi.yml
  format: yaml
  label: FERMAT Pixel v2
  slug: fermat-pixel-v2
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/fermat/asyncapi/fermat-pixel-asyncapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  minimum_age:
    text: This Website is offered and available to users who are 16 years of age or older and reside in the United States or any of its territories or possessions.
    value: '16'
  restricted_uses:
  - summary: Commercial purposes
    text: You must not access or use for any commercial purposes any part of the Website or any services or materials available through the Website.
  - summary: Lawful use only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Fermat
provenance_date: '2026-11-09'
provider_name: Fermat
provider_slug: fermat
slug: fermat-eligibility
source_date: '2026-11-09'
source_filename: fermat-eligibility.yml
source_heading: Eligibility
source_page: https://www.fermatcommerce.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fermat\naid: fermat\nurl: https://www.fermatcommerce.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Commercial purposes\n  text: You must not access or use for any commercial purposes any part of the Website or any services or materials\n    available through the Website.\n- summary: Lawful use only\n  text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: This Website is offered and available to users who are 16 years of age or older and reside in the United\n    States or any of its territories or possessions.\n"
source_yaml_url: https://artifacts.apis.io/fermat/eligibility/fermat-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fermat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Personalization
- Analytics
- Conversion Rate Optimization
- Artificial Intelligence
- Merchandising
- MCP
- Agentic Commerce
- Session Replay
- Experimentation
- Attribution
---
