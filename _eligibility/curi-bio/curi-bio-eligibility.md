---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 [eighteen] years of age to use this website.
    type: individual
  minimum_age:
    text: You must be at least 18 [eighteen] years of age to use this website.
    value: '18'
  restricted_uses:
  - summary: unsolicited commercial communications
    text: You must not use this website or any part of it to transmit or send unsolicited commercial communications.
  - summary: marketing without consent
    text: You must not use this website for any purposes related to marketing without the express written consent of www.curibio.com.
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
name: Curi Bio
provenance_date: '2026-11-09'
provider_name: Curi Bio
provider_slug: curi-bio
slug: curi-bio-eligibility
source_date: '2026-11-09'
source_filename: curi-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.curibio.com/terms-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curi Bio\naid: curi-bio\nurl: https://www.curibio.com/terms-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 [eighteen] years of age to use this website.\nrestricted_uses:\n- summary: unsolicited commercial communications\n  text: You must not use this website or any part of it to transmit or send unsolicited commercial communications.\n- summary: marketing without consent\n  text: You must not use this website for any purposes related to marketing without the express written consent\n    of www.curibio.com.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 [eighteen] years of age to use this website.\n"
source_yaml_url: https://artifacts.apis.io/curi-bio/eligibility/curi-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Curi Bio's own page on 2026-11-09.
synthetic: false
tags:
- Biotechnology
- Drug Discovery
- Human Cell Models
- Platform
- Seattle
---
