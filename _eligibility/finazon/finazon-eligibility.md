---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are operated from the United States, and international users of the Services agree to be subject to applicable laws in the United States
  entity_types:
  - text: You must be at least 18 years old or the age of legal majority in your jurisdiction of residence, to download, register with and/or use the Services.
    type: individual
  - text: If you enter these Terms on behalf of a company or another legal entity, you represent that you have the authority to bind such entity and its affiliates to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old or the age of legal majority in your jurisdiction of residence, to download, register with and/or use the Services.
    value: '18'
  restricted_uses:
  - summary: Non-Professional personal use for Market Data
    text: In line with the Agreement's terms, we offer you Market Data based on your representation and personal account type that you are a Non-Professional
  - summary: No business or commercial use of Market Data
    text: Using Market Data for any business or commercial intent is inconsistent with Non-Professional status, even if done for a non-securities industry organization.
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
name: Finazon
provenance_date: '2026-11-09'
provider_name: Finazon
provider_slug: finazon
slug: finazon-eligibility
source_date: '2026-11-09'
source_filename: finazon-eligibility.yml
source_heading: Eligibility
source_page: https://finazon.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finazon\naid: finazon\nurl: https://finazon.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are operated from the United States, and international users of the Services agree to be subject\n    to applicable laws in the United States\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of legal majority in your jurisdiction of residence, to download,\n    register with and/or use the Services.\n- type: business\n  text: If you enter these Terms on behalf of a company or another legal entity, you represent that you have the\n\
  \    authority to bind such entity and its affiliates to these Terms\nrestricted_uses:\n- summary: Non-Professional personal use for Market Data\n  text: In line with the Agreement's terms, we offer you Market Data based on your representation and personal account\n    type that you are a Non-Professional\n- summary: No business or commercial use of Market Data\n  text: Using Market Data for any business or commercial intent is inconsistent with Non-Professional status, even\n    if done for a non-securities industry organization.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of legal majority in your jurisdiction of residence, to download,\n    register with and/or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/finazon/eligibility/finazon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Finazon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Marketplace
- Datasets
---
