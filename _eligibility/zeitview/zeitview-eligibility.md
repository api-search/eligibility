---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you must not be in violation of any embargoes, export controls, or other laws of the United States or other countries having jurisdiction over these Terms
  entity_types:
  - text: You must, if signing up on behalf of a person other than a natural person, be authorized by that person to bind it to these Terms
    type: business
  - text: You must be the minimum age required to enter into a contract in the area in which you reside, and, in any event, must not be less than 18 years of age.
    type: individual
  minimum_age:
    text: must not be less than 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful or objectionable content
    text: Post or send anything violent, threatening, pornographic, racist, hateful, or otherwise objectionable according to the opinion of Zeitview.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide us with personal information, payment information, and other information that we deem necessary to include you in our marketplace and provide you with our Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zeitview
provenance_date: '2026-11-10'
provider_name: Zeitview
provider_slug: zeitview
slug: zeitview-eligibility
source_date: '2026-11-10'
source_filename: zeitview-eligibility.yml
source_heading: Eligibility
source_page: https://www.zeitview.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zeitview\naid: zeitview\nurl: https://www.zeitview.com/termsofuse\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you must not be in violation of any embargoes, export controls, or other laws of the United States or other\n    countries having jurisdiction over these Terms\nentity_types:\n- type: business\n  text: You must, if signing up on behalf of a person other than a natural person, be authorized by that person\n    to bind it to these Terms\n- type: individual\n  text: You must be the minimum age required to enter into a contract in the area in which you reside, and, in any\n\
  \    event, must not be less than 18 years of age.\nrestricted_uses:\n- summary: Unlawful or objectionable content\n  text: Post or send anything violent, threatening, pornographic, racist, hateful, or otherwise objectionable according\n    to the opinion of Zeitview.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide us with personal information, payment information, and other information that we deem necessary\n    to include you in our marketplace and provide you with our Service.\nminimum_age:\n  value: '18'\n  text: must not be less than 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/zeitview/eligibility/zeitview-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Zeitview's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Drones
- Aerial Imagery
- Inspection
- Asset Intelligence
- Computer Vision
- Renewable Energy
- Geospatial
---
