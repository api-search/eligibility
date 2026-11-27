---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States. Access to the Service from countries or territories or by individuals where such access is illegal is prohibited.
  entity_types:
  - text: 'By agreeing to these Terms, you represent and warrant to us that: (a) either (i) you are at least 18 years old; or (ii) you are at least 13 years old and have obtained your parent''s or legal guardian''s permission'
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have the authority to bind you to these Terms
    type: business
  minimum_age:
    text: (ii) you are at least 13 years old and have obtained your parent's or legal guardian's permission to use the Service
    value: '13'
  restricted_uses:
  - summary: Sanctioned or restricted parties
    text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated by the U.S. Government as a "terrorist supporting" country; and (b) you are not listed on any U.S. Government list of prohibited or restricted parties.
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
name: Campuswire
provenance_date: '2026-11-09'
provider_name: Campuswire
provider_slug: campuswire
slug: campuswire-eligibility
source_date: '2026-11-09'
source_filename: campuswire-eligibility.yml
source_heading: Eligibility
source_page: https://campuswire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Campuswire\naid: campuswire\nurl: https://campuswire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States. Access to the Service from countries\n    or territories or by individuals where such access is illegal is prohibited.\nentity_types:\n- type: individual\n  text: 'By agreeing to these Terms, you represent and warrant to us that: (a) either (i) you are at least 18 years\n    old; or (ii)\
  \ you are at least 13 years old and have obtained your parent''s or legal guardian''s permission'\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have the authority to bind you to these Terms\nrestricted_uses:\n- summary: Sanctioned or restricted parties\n  text: you are not located in a country that is subject to a U.S. Government embargo or that has been designated\n    by the U.S. Government as a \"terrorist supporting\" country; and (b) you are not listed on any U.S. Government\n    list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: (ii) you are at least 13 years old and have obtained your parent's or legal guardian's permission to use\n    the Service\n"
source_yaml_url: https://artifacts.apis.io/campuswire/eligibility/campuswire-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Campuswire's own page on 2026-11-09.
synthetic: false
tags:
- Education
- Collaboration
- Platform
- LMS
- Communications
---
