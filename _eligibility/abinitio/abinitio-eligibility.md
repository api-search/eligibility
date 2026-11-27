---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions law compliance
    text: Sie verpflichten sich, bei der Nutzung der Website und sämtlicher über die Website erhaltener Informationen alle geltenden nationalen und internationalen Gesetze und Verordnungen (einschließlich Gesetzen zum Export oder Reexport technischer Daten) einzuhalten.
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
name: Ab Initio
provenance_date: '2026-11-09'
provider_name: Ab Initio
provider_slug: abinitio
slug: abinitio-eligibility
source_date: '2026-11-09'
source_filename: abinitio-eligibility.yml
source_heading: Eligibility
source_page: https://www.abinitio.com/de/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ab Initio\naid: abinitio\nurl: https://www.abinitio.com/de/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions law compliance\n  text: Sie verpflichten sich, bei der Nutzung der Website und sämtlicher über die Website erhaltener Informationen\n    alle geltenden nationalen und internationalen Gesetze und Verordnungen (einschließlich Gesetzen zum Export oder\n    Reexport technischer Daten) einzuhalten.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/abinitio/eligibility/abinitio-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Ab Initio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Platform
- Enterprise Software
- Integration
- Analytics
---
