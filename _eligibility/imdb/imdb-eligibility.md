---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a U.S. Government end user, we are licensing the IMDb Software to you as a
    type: government
  minimum_age:
    text: IMDb Services are not intended for use by individuals under 18.
    value: '18'
  restricted_uses:
  - summary: User content not generative AI
    text: is not created by generative AI
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
name: IMDb
provenance_date: '2026-11-09'
provider_name: IMDb
provider_slug: imdb
slug: imdb-eligibility
source_date: '2026-11-09'
source_filename: imdb-eligibility.yml
source_heading: Eligibility
source_page: https://www.imdb.com/conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IMDb\naid: imdb\nurl: https://www.imdb.com/conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If you are a U.S. Government end user, we are licensing the IMDb Software to you as a\nrestricted_uses:\n- summary: User content not generative AI\n  text: is not created by generative AI\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: IMDb Services are not intended for use by individuals under 18.\n"
source_yaml_url: https://artifacts.apis.io/imdb/eligibility/imdb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from IMDb's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Entertainment
- Data
- Movies
- Metadata
---
