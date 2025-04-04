# README

**Repository:** `fueski-yaml-config`  
**Description:** `A tool for translating YAML files to standard Apache Fuseki config files. Consists of a YAML parser and RDF generator.`
<!-- SPDX-License-Identifier: OGL-UK-3.0 -->

## Overview
This repository contributes to the development of **secure, scalable, and interoperable data-sharing infrastructure**. It supports NDTP’s mission to enable **trusted, federated, and decentralised** data-sharing across organisations.

This repository is one of several open-source components that underpin NDTP’s **Integration Architecture (IA)**—a framework designed to allow organisations to manage and exchange data securely while maintaining control over their own information. The IA is actively deployed and tested across multiple sectors, ensuring its adaptability and alignment with real-world needs.

For a complete overview of the Integration Architecture (IA) project, please see the [Integration Architecture Documentation](https://github.com/National-Digital-Twin/integration-architecture-documentation).

## Prerequisites
Before using this repository, ensure you have the following dependencies installed:
- **Required Tooling:**
    - Java 21
    - Maven
    - Github PAT token set to allow retrieval of maven packages from Github Packages
    - Docker
- **Pipeline Requirements:** N/A
- **Supported Kubernetes Versions:** N/A
- **System Requirements:** N/A

The tests in the repository depend on [confluentinc/cp-kafka:7.3.3](https://hub.docker.com/r/confluentinc/cp-kafka/tags?name=7.3.3) Docker image.

## Quick Start
Follow these steps to get started quickly with this repository. For detailed installation, configuration, and deployment, refer to the relevant MD files.

### 1. Download and Build
```sh
git clone https://github.com/National-Digital-Twin/fuseki-yaml-config.git
cd fuseki-yaml-config
mvn compile
```

### 2. Full Installation
Refer to [INSTALLATION.md](INSTALLATION.md) for detailed installation steps, including required dependencies and setup configurations.

### 3. Uninstallation
For steps to remove this repository and its dependencies, see [UNINSTALL.md](UNINSTALL.md).

## Features
- **Key functionality**
    - A library project for translating YAML files to standard Apache Fuseki config files.
- **Key integrations**
    - N/A.
- **Scalability & performance**
    - N/A.
- **Modularity**
    - N/A.

## Documentation
Refer to [Documentation](documentation.md).

## Public Funding Acknowledgment
This repository has been developed with public funding as part of the National Digital Twin Programme (NDTP), a UK Government initiative. NDTP, alongside its partners, has invested in this work to advance open, secure, and reusable digital twin technologies for any organisation, whether from the public or private sector, irrespective of size.

## License
This repository contains both source code and documentation, which are covered by different licenses:
- **Code:** Originally developed by Telicent UK Ltd, now maintained by National Digital Twin Programme. Licensed under the [Apache License 2.0](LICENSE.md).
- **Documentation:** Licensed under the [Open Government Licence (OGL) v3.0](OGL_LICENSE.md).

By contributing to this repository, you agree that your contributions will be licensed under these terms.

See [LICENSE.md](LICENSE.md), [OGL_LICENSE.md](OGL_LICENSE.md), and [NOTICE.md](NOTICE.md) for details.

## Security and Responsible Disclosure
We take security seriously. If you believe you have found a security vulnerability in this repository, please follow our responsible disclosure process outlined in [SECURITY.md](SECURITY.md).

## Contributing
We welcome contributions that align with the Programme’s objectives. Please read our [Contributing](CONTRIBUTING.md) guidelines before submitting pull requests.

## Acknowledgements
This repository has benefited from collaboration with various organisations. For a list of acknowledgments, see [ACKNOWLEDGEMENTS.md](ACKNOWLEDGEMENTS.md).

## Support and Contact
For questions or support, check our Issues or contact the NDTP team on ndtp@businessandtrade.gov.uk.

**Maintained by the National Digital Twin Programme (NDTP).**

---
© Crown Copyright 2025. This work has been developed by the National Digital Twin Programme and is legally attributed to the Department for Business and Trade (UK) as the
governing entity.

Licensed under the Open Government Licence v3.0.