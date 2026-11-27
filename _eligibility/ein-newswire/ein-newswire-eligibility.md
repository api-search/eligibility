---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services and the information provided by Our Services or on Our websites are not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: If You are using Our Services on behalf of a business, You warrant that You have authorization to use Our Services by such business
    type: business
  - text: If You are employed by, consult for, or are part of an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: The Services are intended for users who are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated uses (e.g., HIPAA, GLBA)
    text: If Your use or interactions might be subject to such laws, You may not use Our Services or access Our web sites.
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
name: EIN Newswire
provenance_date: '2026-11-09'
provider_name: EIN Newswire
provider_slug: ein-newswire
slug: ein-newswire-eligibility
source_date: '2026-11-09'
source_filename: ein-newswire-eligibility.yml
source_heading: Eligibility
source_page: https://www.einpresswire.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EIN Newswire\naid: ein-newswire\nurl: https://www.einpresswire.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Our Services and the information provided by Our Services or on Our websites are not intended for distribution\n    to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary\n    to law or regulation\nentity_types:\n- type: business\n  text: If You are using Our Services on behalf of a business, You warrant that You have authorization to use Our\n    Services by such business\n- type:\
  \ government\n  text: If You are employed by, consult for, or are part of an agency, department, or other entity of the United\n    States Government\nrestricted_uses:\n- summary: Industry-regulated uses (e.g., HIPAA, GLBA)\n  text: If Your use or interactions might be subject to such laws, You may not use Our Services or access Our web\n    sites.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/ein-newswire/eligibility/ein-newswire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from EIN Newswire's own page on 2026-11-09.
synthetic: false
tags:
- Media
- News Distribution
- Press Releases
- Public Relations
- Newswire
- Content Syndication
- RSS
- Marketing
---
