---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least 18 years old and have the legal authority to enter into these Terms on behalf of yourself or the entity you represent.
    type: individual
  - text: If you accept these Terms on behalf of a company or other entity, you represent that you are authorized to bind that entity.
    type: business
  minimum_age:
    text: You represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use the Services for unlawful, fraudulent, defamatory, infringing, or harmful purposes
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
name: BuiltToWinWeb
provenance_date: '2026-11-09'
provider_name: BuiltToWinWeb
provider_slug: built2winweb-com
slug: built2winweb-com-eligibility
source_date: '2026-11-09'
source_filename: built2winweb-com-eligibility.yml
source_heading: Eligibility
source_page: https://built2winweb.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuiltToWinWeb\naid: built2winweb-com\nurl: https://built2winweb.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years old and have the legal authority to enter into these Terms\n    on behalf of yourself or the entity you represent.\n- type: business\n  text: If you accept these Terms on behalf of a company or other entity, you represent that you are authorized\n    to bind that entity.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use the Services for unlawful, fraudulent,\
  \ defamatory, infringing, or harmful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/built2winweb-com/eligibility/built2winweb-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from BuiltToWinWeb's own page on 2026-11-09.
synthetic: false
tags:
- Web Development
- AI Tools
- Small Business
- SEO
- PHP
---
