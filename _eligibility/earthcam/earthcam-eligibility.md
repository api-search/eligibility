---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: All Members of EarthCam must be at least 13 years of age to create an EarthCam account and to access and view EarthCam.
    value: '13'
  restricted_uses:
  - summary: Lawful use only
    text: Member shall use the site for lawful purposes only.
  - summary: No impersonation or harassment
    text: Impersonate any person or entity, including, but not limited to, an EarthCam official, forum leader, guide or host
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To become a member, member ("Member") must first agree to comply with the current Terms of Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EarthCam
provenance_date: '2026-11-09'
provider_name: EarthCam
provider_slug: earthcam
slug: earthcam-eligibility
source_date: '2026-11-09'
source_filename: earthcam-eligibility.yml
source_heading: Eligibility
source_page: https://www.earthcam.com/company/tos.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EarthCam\naid: earthcam\nurl: https://www.earthcam.com/company/tos.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: Member shall use the site for lawful purposes only.\n- summary: No impersonation or harassment\n  text: Impersonate any person or entity, including, but not limited to, an EarthCam official, forum leader, guide\n    or host\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To become a member, member (\"Member\") must first agree to comply with the current Terms\
  \ of Service.\nminimum_age:\n  value: '13'\n  text: All Members of EarthCam must be at least 13 years of age to create an EarthCam account and to access and\n    view EarthCam.\n"
source_yaml_url: https://artifacts.apis.io/earthcam/eligibility/earthcam-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from EarthCam's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Webcam
- Construction
- visual-data
- Artificial Intelligence
---
