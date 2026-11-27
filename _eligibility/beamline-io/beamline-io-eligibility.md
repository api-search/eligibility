---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Crypto checkout is for buyers outside the EU, EEA and UK; there, or when we can't tell your country, pay by card or PayPal.
  entity_types:
  - text: One purchase gives one person access to their Beamline account, the MCP server, installs, updates and the full library.
    type: individual
  - text: If you buy as a business, we are not liable for indirect or consequential losses, and our total liability is limited to what you paid.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No ML training datasets
    text: You may not use Beamline to build a dataset for training or fine-tuning a machine-learning model.
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
name: Beamline UI
provenance_date: '2026-11-09'
provider_name: Beamline UI
provider_slug: beamline-io
slug: beamline-io-eligibility
source_date: '2026-11-09'
source_filename: beamline-io-eligibility.yml
source_heading: Eligibility
source_page: https://beamline.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beamline UI\naid: beamline-io\nurl: https://beamline.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Crypto checkout is for buyers outside the EU, EEA and UK; there, or when we can't tell your country, pay\n    by card or PayPal.\nentity_types:\n- type: individual\n  text: One purchase gives one person access to their Beamline account, the MCP server, installs, updates and the\n    full library.\n- type: business\n  text: If you buy as a business, we are not liable for indirect or consequential losses, and our total liability\n    is limited to what you paid.\nrestricted_uses:\n\
  - summary: No ML training datasets\n  text: You may not use Beamline to build a dataset for training or fine-tuning a machine-learning model.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beamline-io/eligibility/beamline-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Beamline UI's own page on 2026-11-09.
synthetic: false
tags:
- UI
- React
- Components
- Software-as-a-Service
- Open Source
---
