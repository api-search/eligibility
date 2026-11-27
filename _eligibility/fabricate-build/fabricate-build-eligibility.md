---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are between 13 and 17 years old, you may only use the Service with the consent of a parent or legal guardian
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Phishing and credential harvesting
    text: Build or host phishing pages, including copies of another brand's sign-in page
  - summary: Cryptocurrency mining
    text: Mine cryptocurrency, or run workloads unrelated to building and running your app, in Fabricate 's build and preview environments
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
name: Fabricate
provenance_date: '2026-11-09'
provider_name: Fabricate
provider_slug: fabricate-build
slug: fabricate-build-eligibility
source_date: '2026-11-09'
source_filename: fabricate-build-eligibility.yml
source_heading: Eligibility
source_page: https://fabricate.build/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fabricate\naid: fabricate-build\nurl: https://fabricate.build/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are between 13 and 17 years old, you may only\n    use the Service with the consent of a parent or legal guardian\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Phishing and credential harvesting\n  text: Build\
  \ or host phishing pages, including copies of another brand's sign-in page\n- summary: Cryptocurrency mining\n  text: Mine cryptocurrency, or run workloads unrelated to building and running your app, in Fabricate 's build\n    and preview environments\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/fabricate-build/eligibility/fabricate-build-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Fabricate's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- No-Code
- App Builder
- Cloudflare
- Web Development
---
