---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website and its contents (the "Content") are designed to comply with United States laws and regulations and are intended for use by United States residents only.
  entity_types:
  - text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with the Company
    type: individual
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract with the Company
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: These Terms of Use permit you to use the Website for your personal, non-commercial use only.
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
name: XDemics
provenance_date: '2026-11-10'
provider_name: XDemics
provider_slug: xdemics
slug: xdemics-eligibility
source_date: '2026-11-10'
source_filename: xdemics-eligibility.yml
source_heading: Eligibility
source_page: https://www.xdemics.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XDemics\naid: xdemics\nurl: https://www.xdemics.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website and its contents (the \"Content\") are designed to comply with United States laws and regulations\n    and are intended for use by United States residents only.\nentity_types:\n- type: individual\n  text: By using this Website, you represent and warrant that you are of legal age to form a binding contract with\n    the Company\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: These Terms of Use permit you to use the Website for your\
  \ personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age to form a binding contract with the Company\n"
source_yaml_url: https://artifacts.apis.io/xdemics/eligibility/xdemics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from XDemics's own page on 2026-11-10.
synthetic: false
tags:
- Biotechnology
- Life Sciences
- Cell Culture
- Bioprocessing
- Cell and Gene Therapy
- Laboratory Equipment
- Manufacturing
- Hardware
- Company
---
