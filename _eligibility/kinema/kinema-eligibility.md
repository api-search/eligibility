---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you will be using the Services on behalf of an entity (such as on behalf of your employer), you agree to these Terms on behalf of that entity and its affiliates
    type: business
  minimum_age:
    text: You must be at least 18 years of age, or the legal age of majority where you reside, to use the Services. If you are 13 or older, you may only use the Services under the supervisions of a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Organizers must hold required licensure
    text: You and your affiliates will obtain, prior to the start of ticket sales and/or TVOD usage, all applicable licenses, permits, and authorizations
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
name: Kinema
provenance_date: '2026-11-09'
provider_name: Kinema
provider_slug: kinema
slug: kinema-eligibility
source_date: '2026-11-09'
source_filename: kinema-eligibility.yml
source_heading: Eligibility
source_page: https://kinema.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kinema\naid: kinema\nurl: https://kinema.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you will be using the Services on behalf of an entity (such as on behalf of your employer), you agree\n    to these Terms on behalf of that entity and its affiliates\nrestricted_uses:\n- summary: Organizers must hold required licensure\n  text: You and your affiliates will obtain, prior to the start of ticket sales and/or TVOD usage, all applicable\n    licenses, permits, and authorizations\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the legal age of majority where you reside, to use the Services.\n    If you are 13 or older, you may only use the Services under the supervisions of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/kinema/eligibility/kinema-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kinema's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Film Distribution
- Streaming
- Cinema
- Event
- Entertainment
- Media
- Independent Film
---
