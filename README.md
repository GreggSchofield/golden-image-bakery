[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-white.svg)](https://sonarcloud.io/summary/new_code?id=GreggSchofield_golden-image-bakery)

[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=GreggSchofield_golden-image-bakery&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=GreggSchofield_golden-image-bakery)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=GreggSchofield_golden-image-bakery&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=GreggSchofield_golden-image-bakery)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=GreggSchofield_golden-image-bakery&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=GreggSchofield_golden-image-bakery)

# golden-image-bakery
An artefact bakery capable of building and configuring machine and container images 
targeting multiple public cloud IaaS compute options and platforms

## Static analysis

All infrastructure as code (IaC) written in Terraform within this repository is
scanned with [SonarCloud](https://www.sonarsource.com/products/sonarcloud/) to
ensure a high standard of maintainability and security among other non-functional
requirements.

## Security

### Vulnerability reporting

Private vulnerability reporting is enabled on this repository. If you discover a
security vulnerability within this repository, please report this following the [GitHub
documentation](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability).

### Dependency scanning

This project has [Dependabot](https://github.com/dependabot) enabled and scans for 
outdated Terraform providers daily at 09:00 UTC. Findings and a remediating pull-request
are opened against the dependabot branch of this repository.