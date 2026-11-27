---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not domiciled or reside in a country that belongs to E.U. or U.S. embargoed countries.
  entity_types:
  - text: BETWEEN YOU (EITHER AN INDIVIDUAL OR, IF THE ACCOUNT IS USED BY OR FOR AN ENTITY, AN ENTITY
    type: individual
  - text: IF THE ACCOUNT IS USED BY OR FOR AN ENTITY, AN ENTITY
    type: business
  minimum_age:
    text: You are not a minor in the jurisdiction in which you reside.
    value: not stated
  restricted_uses:
  - summary: Export-controlled or sanctioned parties
    text: You are not a person or a company, and you are not acting on behalf of a person or a company to which provision of the Account or the Websites or shipment of AdGuard products is prohibited by the export control laws
  - summary: High-risk environments
    text: THE ACCOUNT SERVICE IS NOT DESIGNED, INTENDED OR LICENSED FOR USE IN HAZARDOUS OR HIGH-RISK ENVIRONMENTS OR USE CASES REQUIRING FAIL-SAFE CONTROLS
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Account, you are required to register, using your email address and a password. A valid email address must be provided at registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AdGuard Home
provenance_date: '2026-11-09'
provider_name: AdGuard Home
provider_slug: adguard
slug: adguard-eligibility
source_date: '2026-11-09'
source_filename: adguard-eligibility.yml
source_heading: Eligibility
source_page: https://adguard.com/en/terms-and-conditions.html?_plc=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdGuard Home\naid: adguard\nurl: https://adguard.com/en/terms-and-conditions.html?_plc=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not domiciled or reside in a country that belongs to E.U. or U.S. embargoed countries.\nentity_types:\n- type: individual\n  text: BETWEEN YOU (EITHER AN INDIVIDUAL OR, IF THE ACCOUNT IS USED BY OR FOR AN ENTITY, AN ENTITY\n- type: business\n  text: IF THE ACCOUNT IS USED BY OR FOR AN ENTITY, AN ENTITY\nrestricted_uses:\n- summary: Export-controlled or sanctioned parties\n  text: You are not a person or a company, and you are not acting\
  \ on behalf of a person or a company to which provision\n    of the Account or the Websites or shipment of AdGuard products is prohibited by the export control laws\n- summary: High-risk environments\n  text: THE ACCOUNT SERVICE IS NOT DESIGNED, INTENDED OR LICENSED FOR USE IN HAZARDOUS OR HIGH-RISK ENVIRONMENTS\n    OR USE CASES REQUIRING FAIL-SAFE CONTROLS\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Account, you are required to register, using your email address and a password. A valid email\n    address must be provided at registration.\nminimum_age:\n  value: not stated\n  text: You are not a minor in the jurisdiction in which you reside.\n"
source_yaml_url: https://artifacts.apis.io/adguard/eligibility/adguard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from AdGuard Home's own page on 2026-11-09.
synthetic: false
tags:
- Ad Blocking
- Privacy
- DNS Filtering
- Network Security
- Open Source
---
