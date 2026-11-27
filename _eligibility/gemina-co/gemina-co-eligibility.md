---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: Be at least 18 years of age or the age of legal majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Illegal or harmful content
    text: Upload, transmit, or process any Content that is illegal, harmful, threatening, abusive, defamatory, or otherwise objectionable
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
name: gemina-co
provenance_date: '2026-11-09'
provider_name: gemina-co
provider_slug: gemina-co
slug: gemina-co-eligibility
source_date: '2026-11-09'
source_filename: gemina-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.gemina.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: gemina-co\naid: gemina-co\nurl: https://www.gemina.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent and warrant that you have the\n    authority to bind that organization to these Terms.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Upload, transmit, or process any Content that is illegal, harmful, threatening, abusive, defamatory, or\n    otherwise objectionable\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age or the age of legal majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/gemina-co/eligibility/gemina-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from gemina-co's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Document AI
- Extraction
- Search
- Analytics
- Chat
---
