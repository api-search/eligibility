---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use CADProps for an organisation, you confirm that you may accept these terms for it.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use CADProps.
    value: '13'
  restricted_uses:
  - summary: Unlawful or infringing uploads
    text: Do not upload files that are unlawful, infringe someone else's rights, contain malware
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
name: CADProps
provenance_date: '2026-11-09'
provider_name: CADProps
provider_slug: cadprops-com
slug: cadprops-com-eligibility
source_date: '2026-11-09'
source_filename: cadprops-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.cadprops.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CADProps\naid: cadprops-com\nurl: https://www.cadprops.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use CADProps for an organisation, you confirm that you may accept these terms for it.\nrestricted_uses:\n- summary: Unlawful or infringing uploads\n  text: Do not upload files that are unlawful, infringe someone else's rights, contain malware\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use CADProps.\n"
source_yaml_url: https://artifacts.apis.io/cadprops-com/eligibility/cadprops-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from CADProps's own page on 2026-11-09.
synthetic: false
tags:
- CAD
- Viewer
- 3D
- Measurements
- Conversion
---
