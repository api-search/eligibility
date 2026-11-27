---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use Encore for a company, studio, or other organization, you represent that you have authority to accept these Terms for that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Solely automated significant decisions
    text: Use the service to make solely automated decisions that create legal or similarly significant effects for a person.
  - summary: Highly sensitive data
    text: Do not place highly sensitive data—such as government identifiers, financial-account credentials, health records, or children’s data—into a project unless Encore has expressly agreed in writing to support that use and you have a lawful basis to do so.
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
name: encorehq-co
provenance_date: '2026-11-09'
provider_name: encorehq-co
provider_slug: encorehq-co
slug: encorehq-co-eligibility
source_date: '2026-11-09'
source_filename: encorehq-co-eligibility.yml
source_heading: Eligibility
source_page: https://encorehq.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: encorehq-co\naid: encorehq-co\nurl: https://encorehq.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use Encore for a company, studio, or other organization, you represent that you have authority to\n    accept these Terms for that organization.\nrestricted_uses:\n- summary: Solely automated significant decisions\n  text: Use the service to make solely automated decisions that create legal or similarly significant effects for\n    a person.\n- summary: Highly sensitive data\n  text: Do not place highly sensitive data—such\
  \ as government identifiers, financial-account credentials, health\n    records, or children’s data—into a project unless Encore has expressly agreed in writing to support that use\n    and you have a lawful basis to do so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/encorehq-co/eligibility/encorehq-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from encorehq-co's own page on 2026-11-09.
synthetic: false
tags:
- Collaboration
- Feedback
- Design
- Product
- Software-as-a-Service
---
