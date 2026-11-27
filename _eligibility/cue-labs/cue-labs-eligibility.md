---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If the User is acting on behalf of a company, organization or any other legal entity (e.g. his employer) ( Organization ), the User confirms that: (a) they have full legal authority to bind the Organization to the Agreement'
    type: business
  minimum_age:
    text: they are at least 18 years old or the legal representor(s) have confirmed that they can enter into the Agreement with Company
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: The Customer must only use the Registry in a manner that is compatible with applicable laws and regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Registry can be accessed after authenticating via GitHub. The Customer may be obliged to complete an authentication process before using the Registry.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CUE Labs
provenance_date: '2026-11-09'
provider_name: CUE Labs
provider_slug: cue-labs
slug: cue-labs-eligibility
source_date: '2026-11-09'
source_filename: cue-labs-eligibility.yml
source_heading: Eligibility
source_page: https://cue.dev/terms-of-service/central-registry/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CUE Labs\naid: cue-labs\nurl: https://cue.dev/terms-of-service/central-registry/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If the User is acting on behalf of a company, organization or any other legal entity (e.g. his employer)\n    ( Organization ), the User confirms that: (a) they have full legal authority to bind the Organization to the\n    Agreement'\nrestricted_uses:\n- summary: Lawful use only\n  text: The Customer must only use the Registry in a manner that is compatible with applicable laws and regulations.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Registry can be accessed after authenticating via GitHub. The Customer may be obliged to complete an\n    authentication process before using the Registry.\nminimum_age:\n  value: '18'\n  text: they are at least 18 years old or the legal representor(s) have confirmed that they can enter into the Agreement\n    with Company\n"
source_yaml_url: https://artifacts.apis.io/cue-labs/eligibility/cue-labs-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from CUE Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Configuration
- Automation
- DevOps
- Infrastructure
---
