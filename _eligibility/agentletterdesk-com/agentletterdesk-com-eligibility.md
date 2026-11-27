---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - AT
    - DE
    text: 'Market and language: United States, English; Europe. Letters to the United States must not contain health data or other sensitive data, or full bank or card account numbers.'
  entity_types:
  - text: You must be 18 or older and accept these terms.
    type: individual
  - text: 'Sara Meindl is a small business (Kleinunternehmerin, § 6 (1) 27 Austrian VAT Act): no VAT is charged.'
    type: business
  minimum_age:
    text: You must be 18 or older and accept these terms.
    value: '18'
  restricted_uses:
  - summary: Notices needing handwritten signature
    text: we do not prepare such letters, for example a notice that ends an employment in Germany or the lease of a home in Germany or Austria.
  - summary: Sensitive data about others
    text: Do not put health data or other sensitive data (religion, ethnic origin, sexual orientation, union membership, political views, genetic or biometric data) about another person, or offences they committed or are suspected of, in a letter.
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
name: Agent Letter Desk
provenance_date: '2026-11-09'
provider_name: Agent Letter Desk
provider_slug: agentletterdesk-com
slug: agentletterdesk-com-eligibility
source_date: '2026-11-09'
source_filename: agentletterdesk-com-eligibility.yml
source_heading: Eligibility
source_page: https://agentletterdesk.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Letter Desk\naid: agentletterdesk-com\nurl: https://agentletterdesk.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - AT\n  - DE\n  excluded: []\n  text: 'Market and language: United States, English; Europe. Letters to the United States must not contain health\n    data or other sensitive data, or full bank or card account numbers.'\nentity_types:\n- type: individual\n  text: You must be 18 or older and accept these terms.\n- type: business\n  text: 'Sara Meindl is a small business (Kleinunternehmerin, § 6 (1) 27 Austrian VAT Act): no VAT is charged.'\nrestricted_uses:\n- summary:\
  \ Notices needing handwritten signature\n  text: we do not prepare such letters, for example a notice that ends an employment in Germany or the lease of\n    a home in Germany or Austria.\n- summary: Sensitive data about others\n  text: Do not put health data or other sensitive data (religion, ethnic origin, sexual orientation, union membership,\n    political views, genetic or biometric data) about another person, or offences they committed or are suspected\n    of, in a letter.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older and accept these terms.\n"
source_yaml_url: https://artifacts.apis.io/agentletterdesk-com/eligibility/agentletterdesk-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Agent Letter Desk's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Mail
- Certified Mail
- LetterService
- Automation
- Company
---
