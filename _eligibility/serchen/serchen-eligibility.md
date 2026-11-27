---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you access the Site on behalf of an organisation, that organisation also accepts these Terms.
    type: business
  - text: you will use the Site for business and professional purposes only
    type: business
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and parties
    text: You may not access or use the Site if you are located in, ordinarily resident in, or a national of any country subject to comprehensive UK, EU, or US sanctions
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
name: Serchen
provenance_date: '2026-11-10'
provider_name: Serchen
provider_slug: serchen
slug: serchen-eligibility
source_date: '2026-11-10'
source_filename: serchen-eligibility.yml
source_heading: Eligibility
source_page: https://www.serchen.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Serchen\naid: serchen\nurl: https://www.serchen.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you access the Site on behalf of an organisation, that organisation also accepts these Terms.\n- type: business\n  text: you will use the Site for business and professional purposes only\nrestricted_uses:\n- summary: Sanctioned jurisdictions and parties\n  text: You may not access or use the Site if you are located in, ordinarily resident in, or a national of any country\n    subject to comprehensive UK, EU, or US sanctions\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/serchen/eligibility/serchen-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Serchen's own page on 2026-11-10.
synthetic: false
tags:
- Cloud Services
- Directory
- Software-as-a-Service
- Software Marketplace
- Reviews
- Business Software
- Vendor Discovery
- Comparison
- Lead Generation
---
