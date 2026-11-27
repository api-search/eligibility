---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract
    value: legal age
  restricted_uses:
  - summary: Unlawful, harmful or abusive use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
  - summary: Violating laws
    text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Services, you may be required to sign up for an account. You must provide accurate and complete information for your account and keep all such account information updated.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BetterBugs
provenance_date: '2026-11-09'
provider_name: BetterBugs
provider_slug: betterbugs
slug: betterbugs-eligibility
source_date: '2026-11-09'
source_filename: betterbugs-eligibility.yml
source_heading: Eligibility
source_page: https://www.betterbugs.io/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetterBugs\naid: betterbugs\nurl: https://www.betterbugs.io/terms-and-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\nrestricted_uses:\n- summary: Unlawful, harmful or abusive use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\n- summary: Violating laws\n\
  \  text: violates any law or regulation, including, without limitation, any applicable export control laws, privacy\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Services, you may be required to sign up for an account. You must provide accurate and complete\n    information for your account and keep all such account information updated.\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/betterbugs/eligibility/betterbugs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from BetterBugs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Bug Tracking
- Software-as-a-Service
- Collaboration
- Software Quality
---
