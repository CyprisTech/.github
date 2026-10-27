## Cypris Tech

We build and run OpenStack clouds and the services on top of them. This organization publishes the tools we use, rebuilt as general-purpose open source projects: documented, tested on real clouds, and free of anything specific to our own infrastructure.

### Projects

| Project | What it does | Status |
|---|---|---|
| [terraform-openstack-tenant](https://github.com/CyprisTech/terraform-openstack-tenant) | OpenTofu and Terraform modules that describe an OpenStack tenant in one declarative model, without admin rights | [![release](https://img.shields.io/github/v/release/CyprisTech/terraform-openstack-tenant)](https://github.com/CyprisTech/terraform-openstack-tenant/releases) [![registry](https://img.shields.io/badge/registry-CyprisTech%2Ftenant%2Fopenstack-844fba)](https://registry.terraform.io/modules/CyprisTech/tenant/openstack/latest) |
| [openstack-multitenant-reference](https://github.com/CyprisTech/openstack-multitenant-reference) | A reference architecture for several tenants sharing one OpenStack cloud: shared network planes, a single SNI passthrough entry point, monitoring through floating IPs and DNS, and tenant isolation proven by an executable reachability matrix | [![release](https://img.shields.io/github/v/release/CyprisTech/openstack-multitenant-reference)](https://github.com/CyprisTech/openstack-multitenant-reference/releases) |

### How we work

- Every design decision is written down as an ADR in the repository.
- Every release is tested with mocked providers in CI and on a real OpenStack cloud before it is tagged; what the tests reveal is documented with the results.
- Architectures come with their trade-offs written down, and with tests that prove their claims, such as tenant isolation.
- Issues and pull requests are welcome; see each project's `CONTRIBUTING.md`.

Licensed under Apache-2.0 unless stated otherwise.
