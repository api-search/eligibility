---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of your company or another legal entity, you represent that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: You must be 13 years or older to use the Services.
    value: '13'
  restricted_uses:
  - summary: Unlawful hosting of personal or protected data
    text: You shall be solely and exclusively responsible for the lawfulness of hosting such Classified Data, Personal Data, or protected information for your chosen audience.
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
name: Ellipsis Drive
provenance_date: '2026-11-09'
provider_name: Ellipsis Drive
provider_slug: ellipsis-drive
slug: ellipsis-drive-eligibility
source_date: '2026-11-09'
source_filename: ellipsis-drive-eligibility.yml
source_heading: Eligibility
source_page: https://ellipsis-drive.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ellipsis Drive\naid: ellipsis-drive\nurl: https://ellipsis-drive.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of your company or another legal entity, you represent\n    that you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Unlawful hosting of personal or protected data\n  text: You shall be solely and exclusively responsible for the lawfulness of hosting such Classified Data, Personal\n    Data, or protected information for your chosen\
  \ audience.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 years or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/ellipsis-drive/eligibility/ellipsis-drive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ellipsis Drive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geospatial
- Spatial Data
- GIS
- Mapping
- Data Management
- Raster
- Vectors
- OGC
- Cloud Storage
- Remote Sensing
---
