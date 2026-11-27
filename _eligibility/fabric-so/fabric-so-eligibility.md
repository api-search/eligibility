---
api_specs:
- filename: fabric-so-openapi-generated.yml
  format: yaml
  label: Fabric API
  slug: fabric-so-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fabric-so/openapi/_ae-authored/fabric-so-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The license excludes (i) jurisdictions that are embargoed or designated as supporting terrorist activities by the United States Government and (ii) jurisdictions whose laws do not permit engaging in business with Fabric or use of the Services
  entity_types:
  - text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to these Terms.
    type: business
  - text: If you are a U.S. government or other U.S. governmental entity (or your use of the Services is for the U.S. government or another U.S. governmental entity), the following terms apply
    type: government
  minimum_age:
    text: You may use the Services only if you are at least 16 years of age.
    value: '16'
  restricted_uses:
  - summary: Recording without consent
    text: Use the Services to record others without obtaining all legally required consents
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
name: Fabric
provenance_date: '2026-11-09'
provider_name: Fabric
provider_slug: fabric-so
slug: fabric-so-eligibility
source_date: '2026-11-09'
source_filename: fabric-so-eligibility.yml
source_heading: Eligibility
source_page: https://fabric.so/info/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fabric\naid: fabric-so\nurl: https://fabric.so/info/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The license excludes (i) jurisdictions that are embargoed or designated as supporting terrorist activities\n    by the United States Government and (ii) jurisdictions whose laws do not permit engaging in business with Fabric\n    or use of the Services\nentity_types:\n- type: business\n  text: If you are accessing and using the Services on behalf of a company (such as your employer) or other legal\n    entity, you represent and warrant that you have the authority\
  \ to bind that company or other legal entity to\n    these Terms.\n- type: government\n  text: If you are a U.S. government or other U.S. governmental entity (or your use of the Services is for the U.S.\n    government or another U.S. governmental entity), the following terms apply\nrestricted_uses:\n- summary: Recording without consent\n  text: Use the Services to record others without obtaining all legally required consents\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use the Services only if you are at least 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/fabric-so/eligibility/fabric-so-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Fabric's own page on 2026-11-09.
synthetic: false
tags:
- AI Workspace
- File Storage
- Integration
---
