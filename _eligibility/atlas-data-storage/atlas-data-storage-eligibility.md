---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Site or on behalf of a company or other legal entity, you represent and warrant that you have authority to bind that entity, and “you” refers to that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our Site.
    value: '18'
  restricted_uses:
  - summary: No security violations or interference
    text: You will not violate or attempt to violate the security of the Site or AtlasBase’s systems or network security
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
name: Atlas Data Storage
provenance_date: '2026-11-09'
provider_name: Atlas Data Storage
provider_slug: atlas-data-storage
slug: atlas-data-storage-eligibility
source_date: '2026-11-09'
source_filename: atlas-data-storage-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlasbase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlas Data Storage\naid: atlas-data-storage\nurl: https://www.atlasbase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Site or on behalf of a company or other legal entity, you represent and warrant that\n    you have authority to bind that entity, and “you” refers to that entity.\nrestricted_uses:\n- summary: No security violations or interference\n  text: You will not violate or attempt to violate the security of the Site or AtlasBase’s systems or network security\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/atlas-data-storage/eligibility/atlas-data-storage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Atlas Data Storage's own page on 2026-11-09.
synthetic: false
tags:
- Cloud
- Storage
- Enterprise
- Data Management
---
