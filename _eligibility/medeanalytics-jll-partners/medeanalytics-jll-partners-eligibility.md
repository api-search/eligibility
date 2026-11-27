---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you, as an individual, are acting for or on behalf of a company, organization, or other entity, such as your employer, then by accessing or using the Site
    type: individual
  - text: you represent that you are fully authorized to access or use the Site
    type: business
  minimum_age:
    text: Minors are not eligible to use the Site.
    value: null
  restricted_uses:
  - summary: Client Services limited to current clients
    text: Any attempt by others to access this portion of the Site is prohibited.
  - summary: Export law compliance
    text: You may not access, download, use or export the Site, or the content, software, products or services provided on the Site in violation of U.S. export laws or regulations
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
name: MedeAnalytics (JLL Partners)
provenance_date: '2026-11-10'
provider_name: MedeAnalytics (JLL Partners)
provider_slug: medeanalytics-jll-partners
slug: medeanalytics-jll-partners-eligibility
source_date: '2026-11-10'
source_filename: medeanalytics-jll-partners-eligibility.yml
source_heading: Eligibility
source_page: https://medeanalytics.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MedeAnalytics (JLL Partners)\naid: medeanalytics-jll-partners\nurl: https://medeanalytics.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you, as an individual, are acting for or on behalf of a company, organization, or other entity, such\n    as your employer, then by accessing or using the Site\n- type: business\n  text: you represent that you are fully authorized to access or use the Site\nrestricted_uses:\n- summary: Client Services limited to current clients\n  text: Any attempt by others to access this portion of\
  \ the Site is prohibited.\n- summary: Export law compliance\n  text: You may not access, download, use or export the Site, or the content, software, products or services provided\n    on the Site in violation of U.S. export laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Minors are not eligible to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/medeanalytics-jll-partners/eligibility/medeanalytics-jll-partners-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from MedeAnalytics (JLL Partners)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Analytics
- Health Insurance
- Payers
- Data Analytics
- Population Health
- Value-Based Care
---
