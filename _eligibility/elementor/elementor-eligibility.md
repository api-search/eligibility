---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not located in, or a national or resident of any of the countries or entities referred to in any country or entity that is subject to a U.S. Government embargo.
  entity_types:
  - text: The Services are intended for use by users of at least eighteen (18) years old.
    type: individual
  - text: If you are a corporation (or using the account on behalf of a corporation), then you can allow access to your corporate account for one authorized employee on your behalf.
    type: business
  minimum_age:
    text: If you register for our services, you hereby declare that you are eighteen (18) years old or older
    value: '18'
  restricted_uses:
  - summary: No HIPAA-regulated health information
    text: It is strictly forbbiden to upload, or allow anyone else to upload, any patient, medical, or other protected sensitive health information regulated by the Health Insurance Portability and Accountability Act (HIPAA) to our Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When registering for the Services, we may authenticate your identity through different third-party services and may require additional identification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Elementor
provenance_date: '2026-11-09'
provider_name: Elementor
provider_slug: elementor
slug: elementor-eligibility
source_date: '2026-11-09'
source_filename: elementor-eligibility.yml
source_heading: Eligibility
source_page: https://elementor.com/terms/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Elementor\naid: elementor\nurl: https://elementor.com/terms/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not located in, or a national or resident of any of the countries or entities referred to in any\n    country or entity that is subject to a U.S. Government embargo.\nentity_types:\n- type: individual\n  text: The Services are intended for use by users of at least eighteen (18) years old.\n- type: business\n  text: If you are a corporation (or using the account on behalf of a corporation), then you can allow access to\n    your corporate account for one authorized\
  \ employee on your behalf.\nrestricted_uses:\n- summary: No HIPAA-regulated health information\n  text: It is strictly forbbiden to upload, or allow anyone else to upload, any patient, medical, or other protected\n    sensitive health information regulated by the Health Insurance Portability and Accountability Act (HIPAA) to\n    our Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When registering for the Services, we may authenticate your identity through different third-party services\n    and may require additional identification.\nminimum_age:\n  value: '18'\n  text: If you register for our services, you hereby declare that you are eighteen (18) years old or older\n"
source_yaml_url: https://artifacts.apis.io/elementor/eligibility/elementor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Elementor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Website Builder
- WordPress
- Page Builder
- No-Code
- Web Design
- CMS
- Developer Tools
- Widgets
- Extensibility
---
