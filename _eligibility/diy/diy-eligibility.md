---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: DIY makes no representation that the Content is appropriate or available for use in locations outside of the United States, and accessing the Service is prohibited from territories where such Content is illegal.
  entity_types:
  - text: if you are an individual, you are of legal age to agree to these terms and conditions or you have your parents' permission to do so
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, THEN YOU REPRESENT AND WARRANT THAT YOU ARE AUTHORIZED TO BIND SUCH ENTITY TO THE TERMS OF THIS AGREEMENT.
    type: business
  minimum_age:
    text: Only those 18 and older can make purchases from DIY
    value: '18'
  restricted_uses:
  - summary: Commercial use without permission
    text: you can't use it commercially without getting permission from us first.
  - summary: Unlawful, abusive or deceptive content
    text: is unlawful, threatening, abusive, harassing, defamatory, libelous, deceptive, fraudulent, invasive of another's privacy, tortious, obscene, offensive, or profane
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: DIY cannot guarantee the authenticity of any data which users may provide about themselves.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DIY
provenance_date: '2026-11-09'
provider_name: DIY
provider_slug: diy
slug: diy-eligibility
source_date: '2026-11-09'
source_filename: diy-eligibility.yml
source_heading: Eligibility
source_page: https://www.diy.org/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DIY\naid: diy\nurl: https://www.diy.org/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: DIY makes no representation that the Content is appropriate or available for use in locations outside of\n    the United States, and accessing the Service is prohibited from territories where such Content is illegal.\nentity_types:\n- type: individual\n  text: if you are an individual, you are of legal age to agree to these terms and conditions or you have your parents'\n    permission to do so\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF AN ENTITY, THEN\
  \ YOU REPRESENT AND WARRANT THAT YOU\n    ARE AUTHORIZED TO BIND SUCH ENTITY TO THE TERMS OF THIS AGREEMENT.\nrestricted_uses:\n- summary: Commercial use without permission\n  text: you can't use it commercially without getting permission from us first.\n- summary: Unlawful, abusive or deceptive content\n  text: is unlawful, threatening, abusive, harassing, defamatory, libelous, deceptive, fraudulent, invasive of another's\n    privacy, tortious, obscene, offensive, or profane\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: DIY cannot guarantee the authenticity of any data which users may provide about themselves.\nminimum_age:\n  value: '18'\n  text: Only those 18 and older can make purchases from DIY\n"
source_yaml_url: https://artifacts.apis.io/diy/eligibility/diy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from DIY's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- EdTech
- Kids
- Coding
- Games
- Artificial Intelligence
- Education
- Creativity
- Learning
---
