---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    value: legal age
  restricted_uses:
  - summary: Non-commercial use only
    text: You will only use the Services for your own internal, personal, non-commercial use
  - summary: No crawling or scraping
    text: “crawls,” “scrapes,” or “spiders” any page, data, or portion of or relating to the Services or Content (through use of manual or automated means)
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
name: Trial Library
provenance_date: '2026-11-10'
provider_name: Trial Library
provider_slug: trial-library
slug: trial-library-eligibility
source_date: '2026-11-10'
source_filename: trial-library-eligibility.yml
source_heading: Eligibility
source_page: https://www.triallibrary.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trial Library\naid: trial-library\nurl: https://www.triallibrary.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You will only use the Services for your\
  \ own internal, personal, non-commercial use\n- summary: No crawling or scraping\n  text: “crawls,” “scrapes,” or “spiders” any page, data, or portion of or relating to the Services or Content (through\n    use of manual or automated means)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/trial-library/eligibility/trial-library-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Trial Library's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Clinical Trials
- Oncology
- Healthcare
- Patient Access
- Artificial Intelligence
---
