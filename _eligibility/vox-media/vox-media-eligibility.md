---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  minimum_age:
    text: You must be thirteen (13) years of age or older to participate in any activities or services offered on our Sites
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: 'you agree not to use the Services to: (a) violate any local, state, national, or international law or regulation'
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
name: Vox Media
provenance_date: '2026-11-10'
provider_name: Vox Media
provider_slug: vox-media
slug: vox-media-eligibility
source_date: '2026-11-10'
source_filename: vox-media-eligibility.yml
source_heading: Eligibility
source_page: https://www.voxmedia.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vox Media\naid: vox-media\nurl: https://www.voxmedia.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: 'you agree not to use the Services to: (a) violate any local, state, national, or international law or regulation'\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be thirteen (13) years of age or older to participate in any activities or services offered on\n    our Sites\n"
source_yaml_url: https://artifacts.apis.io/vox-media/eligibility/vox-media-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Vox Media's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Media
- Publishing
- News
- Comments
- Community
- Moderation
- GraphQL
---
