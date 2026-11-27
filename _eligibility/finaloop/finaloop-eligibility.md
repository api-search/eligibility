---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing to these Terms on behalf of an entity, you represent that you have the authority to bind that entity or organization
    type: business
  - text: between you (either an individual or, if you are using Finaloop on behalf of an entity, that entity)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use
    text: use the Services for personal, family or household purposes
  - summary: Health information
    text: transmit, store, or process health information subject to United States HIPAA regulations
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
name: Finaloop
provenance_date: '2026-11-09'
provider_name: Finaloop
provider_slug: finaloop
slug: finaloop-eligibility
source_date: '2026-11-09'
source_filename: finaloop-eligibility.yml
source_heading: Eligibility
source_page: https://www.finaloop.com/legal/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finaloop\naid: finaloop\nurl: https://www.finaloop.com/legal/terms-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing to these Terms on behalf of an entity, you represent that you have the authority to\n    bind that entity or organization\n- type: individual\n  text: between you (either an individual or, if you are using Finaloop on behalf of an entity, that entity)\nrestricted_uses:\n- summary: Personal use\n  text: use the Services for personal, family or household purposes\n- summary: Health information\n\
  \  text: transmit, store, or process health information subject to United States HIPAA regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/finaloop/eligibility/finaloop-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Finaloop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Bookkeeping
- E-Commerce
- Finance
- Inventory
- Analytics
- Tax
- Financial Operations
- Direct to Consumer
---
