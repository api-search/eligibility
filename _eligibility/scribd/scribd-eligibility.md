---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services may not be appropriate or available for use in some jurisdictions outside of the United States. We may limit availability of the Services ... to any person, geographic area, or jurisdiction we choose
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Prohibited content uploads
    text: Is illegal, unlawful, defamatory, libelous, tortious, fraudulent, misleading, or inaccurate
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
name: Scribd
provenance_date: '2026-11-10'
provider_name: Scribd
provider_slug: scribd
slug: scribd-eligibility
source_date: '2026-11-10'
source_filename: scribd-eligibility.yml
source_heading: Eligibility
source_page: https://support.scribd.com/hc/en-us/articles/210129326-Global-Terms-of-Use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Scribd\naid: scribd\nurl: https://support.scribd.com/hc/en-us/articles/210129326-Global-Terms-of-Use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services may not be appropriate or available for use in some jurisdictions outside of the United States.\n    We may limit availability of the Services ... to any person, geographic area, or jurisdiction we choose\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content uploads\n  text: Is illegal, unlawful, defamatory, libelous, tortious, fraudulent, misleading, or inaccurate\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/scribd/eligibility/scribd-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Scribd's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Documents
- Ebooks
- Audiobooks
- Publishing
- Content
- Subscription
- Media
- Reading
---
