---
api_specs:
- filename: tensordock-instances-api-openapi.yml
  format: yaml
  label: TensorDock Instances API
  slug: tensordock-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-instances-api-openapi.yml
- filename: tensordock-secrets-api-openapi.yml
  format: yaml
  label: TensorDock Secrets API
  slug: tensordock-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-secrets-api-openapi.yml
- filename: tensordock-authorization-api-openapi.yml
  format: yaml
  label: TensorDock Authorization API
  slug: tensordock-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-authorization-api-openapi.yml
- filename: tensordock-billing-api-openapi.yml
  format: yaml
  label: TensorDock Billing API
  slug: tensordock-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-billing-api-openapi.yml
- filename: tensordock-containers-api-openapi.yml
  format: yaml
  label: TensorDock Containers API
  slug: tensordock-containers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-containers-api-openapi.yml
- filename: tensordock-hostnodes-api-openapi.yml
  format: yaml
  label: TensorDock Hostnodes API
  slug: tensordock-hostnodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-hostnodes-api-openapi.yml
- filename: tensordock-instant-vms-api-openapi.yml
  format: yaml
  label: TensorDock Instant VMs API
  slug: tensordock-instant-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-instant-vms-api-openapi.yml
- filename: tensordock-spot-api-openapi.yml
  format: yaml
  label: TensorDock Spot API
  slug: tensordock-spot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-spot-api-openapi.yml
- filename: tensordock-virtual-machines-api-openapi.yml
  format: yaml
  label: TensorDock Virtual Machines API
  slug: tensordock-virtual-machines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensordock/openapi/tensordock-virtual-machines-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right to limit the locations from which Offers may be placed, including as required to comply with applicable laws and regulations.
  entity_types:
  - text: You must be 18 years of age or older to use the Platform
    type: individual
  - text: If you use the Platform on behalf of a company or other entity then "you" includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Platform
    value: '18'
  restricted_uses:
  - summary: Not for resale
    text: By placing an Offer, you represent that you are procuring the Compute Services on your own behalf and not for resale or use by another entity.
  - source: https://docs.tensordock.com/legal-information/acceptable-use-policy-aup
    summary: Spam and inauthentic activity
    text: 'We do not allow data or activity on TensorDock that is: automated excessive bulk activity and coordinated inauthentic activity, such as spamming (unsolicited advertising)'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to verify information that you have provided to create an Account before we allow you to submit Offers.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TensorDock
provenance_date: '2026-11-10'
provider_name: TensorDock
provider_slug: tensordock
slug: tensordock-eligibility
source_date: '2026-11-10'
source_filename: tensordock-eligibility.yml
source_heading: Eligibility
source_page: https://docs.tensordock.com/legal-information/terms-of-service-tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TensorDock\naid: tensordock\nurl: https://docs.tensordock.com/legal-information/terms-of-service-tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://docs.tensordock.com/legal-information/acceptable-use-policy-aup\n  - https://docs.tensordock.com/legal-information/terms-of-service-tos\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right to limit the locations from which Offers may be placed, including as required to comply\n    with applicable laws and regulations.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older to use the Platform\n- type: business\n  text:\
  \ If you use the Platform on behalf of a company or other entity then \"you\" includes you and that entity,\n    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Not for resale\n  text: By placing an Offer, you represent that you are procuring the Compute Services on your own behalf and not\n    for resale or use by another entity.\n- summary: Spam and inauthentic activity\n  text: 'We do not allow data or activity on TensorDock that is: automated excessive bulk activity and coordinated\n    inauthentic activity, such as spamming (unsolicited advertising)'\n  source: https://docs.tensordock.com/legal-information/acceptable-use-policy-aup\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to verify information that you have provided to create an Account before we allow you\n    to submit Offers.\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to\
  \ use the Platform\n"
source_yaml_url: https://artifacts.apis.io/tensordock/eligibility/tensordock-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from TensorDock's own page on 2026-11-10.
synthetic: false
tags:
- GPU
- Cloud
- Marketplace
- Compute
- Virtual Machines
- Artificial Intelligence
- Machine Learning
- Bare Metal
- Spot Instances
- Containers
---
