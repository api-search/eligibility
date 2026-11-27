---
api_specs:
- filename: overview
  format: yaml
  label: Tracxn API
  slug: tracxn-api
  spec_type: Postman
  url: https://www.postman.com/tracxnapi/tracxn-api/overview
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the Platform on behalf of a company, organization, or any other legal entity (an "Organization"), you confirm that you are authorized to accept and bind the Organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Securities trading
    text: the Platform is strictly not to be used for buying or selling securities
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
name: Tracxn
provenance_date: '2026-11-10'
provider_name: Tracxn
provider_slug: tracxn
slug: tracxn-eligibility
source_date: '2026-11-10'
source_filename: tracxn-eligibility.yml
source_heading: Eligibility
source_page: https://tracxn.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tracxn\naid: tracxn\nurl: https://tracxn.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the Platform on behalf of a company, organization, or any other legal entity\n    (an \"Organization\"), you confirm that you are authorized to accept and bind the Organization to these Terms.\nrestricted_uses:\n- summary: Securities trading\n  text: the Platform is strictly not to be used for buying or selling securities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tracxn/eligibility/tracxn-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tracxn's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cloud Saas
- Market Intelligence
- Private Markets
- Venture Capital
- Startups
- Company Data
- Investor
- Funding
---
