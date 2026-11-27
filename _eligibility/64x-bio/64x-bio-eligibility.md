---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States. Access to the Site from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: you are at least 18 years old
    type: individual
  - text: If you are accessing the Site on behalf of an entity, organization, or company, then (y) “you” will refer to that entity, organization, or company
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Research use only, not for medical use or use in humans
    text: All products and solutions described on the Site are intended for research use only, not intended for any medical use or use in humans.
  - summary: Illegal purposes
    text: use the Site for any illegal purpose or in violation of any local, state, national, or international law
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
name: 64x Bio
provenance_date: '2026-11-09'
provider_name: 64x Bio
provider_slug: 64x-bio
slug: 64x-bio-eligibility
source_date: '2026-11-09'
source_filename: 64x-bio-eligibility.yml
source_heading: Eligibility
source_page: https://64xbio.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 64x Bio\naid: 64x-bio\nurl: https://64xbio.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States. Access to the Site from countries or territories\n    or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: you are at least 18 years old\n- type: business\n  text: If you are accessing the Site on behalf of an entity, organization, or company,\
  \ then (y) “you” will refer\n    to that entity, organization, or company\nrestricted_uses:\n- summary: Research use only, not for medical use or use in humans\n  text: All products and solutions described on the Site are intended for research use only, not intended for any\n    medical use or use in humans.\n- summary: Illegal purposes\n  text: use the Site for any illegal purpose or in violation of any local, state, national, or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/64x-bio/eligibility/64x-bio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from 64x Bio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biotechnology
- Synthetic Biology
- Gene Therapy
- Cell and Gene Therapy
- Biomanufacturing
- Cell Line Engineering
- Life Sciences
---
