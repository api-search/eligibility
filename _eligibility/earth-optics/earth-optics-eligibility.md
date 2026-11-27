---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: By using the EarthOptics Product, you represent and warrant that you are not located in any such country or on any such list
  entity_types:
  - text: a legal agreement between (i) you (either an individual or a single legal entity)
    type: individual
  minimum_age:
    text: you represent and warrant (a) that you are at least 18 years of age or the age of majority where you reside
    value: '18'
  restricted_uses:
  - summary: No export to embargoed countries or listed parties
    text: EarthOptics Products may not be exported or re-exported (a) into any U.S. embargoed countries or (b) to anyone on the U.S. Treasury Department's list of Specially Designated Nationals
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Your Order will become effective only if we accept the Order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EarthOptics
provenance_date: '2026-11-09'
provider_name: EarthOptics
provider_slug: earth-optics
slug: earth-optics-eligibility
source_date: '2026-11-09'
source_filename: earth-optics-eligibility.yml
source_heading: Eligibility
source_page: https://earthoptics.com/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EarthOptics\naid: earth-optics\nurl: https://earthoptics.com/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: By using the EarthOptics Product, you represent and warrant that you are not located in any such country\n    or on any such list\nentity_types:\n- type: individual\n  text: a legal agreement between (i) you (either an individual or a single legal entity)\nrestricted_uses:\n- summary: No export to embargoed countries or listed parties\n  text: EarthOptics Products may not be exported or re-exported (a) into any U.S. embargoed countries or (b) to\n    anyone on the U.S.\
  \ Treasury Department's list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Your Order will become effective only if we accept the Order.\nminimum_age:\n  value: '18'\n  text: you represent and warrant (a) that you are at least 18 years of age or the age of majority where you reside\n"
source_yaml_url: https://artifacts.apis.io/earth-optics/eligibility/earth-optics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from EarthOptics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Soil
- Soil Data
- Precision Agriculture
- Soil Carbon
- Carbon
- Sustainability
- Agronomy
- Geospatial
- Remote Sensing
- Soil Health
- Carbon Credits
---
