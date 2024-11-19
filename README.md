# Universal Data Quality Score 
## UDQSS

> *"Have a bias toward action—let’s see something happen now. 
You can break that big plan into small steps and take the first step right away."
~ Indira Gandhi*

<img width="1553" alt="UDQSS" src="https://github.com/user-attachments/assets/4738cfb2-a00d-40c1-80d4-80b505f3161c">



## Overview

UDQSS is an open-source standard for evaluating and scoring data quality across different domains. It provides a comprehensive framework to assess, measure, and benchmark the quality of datasets using standardized criteria.

## Purpose

- Establish a universal standard for data quality assessment
- Enable consistent quality benchmarking across datasets
- Provide tools and templates for easy quality evaluation
- Support customization for domain-specific requirements
- Foster transparency in data quality metrics

## Repository Structure

```
udqss/
├── docs/                    # Documentation
│   ├── parameters.md       # Quality parameters
│   ├── scoring-guide.md    # Scoring methodology
│   └── customization.md    # Customization guide
├── templates/              # Ready-to-use templates
│   ├── udqss-questionnaire.pdf
│   └── udqss-template.xlsx
├── examples/               # Implementation examples
│   ├── healthcare-data/
│   ├── financial-data/
│   └── more-domains/
└── .github/               # Project management
```

## Getting Started

1. Review the [parameters documentation](docs/parameters.md) to understand quality metrics
2. Choose either the PDF questionnaire or Excel template from the `templates/` directory
3. Follow the [scoring guide](docs/scoring-guide.md) to evaluate your dataset
4. Check example implementations in the `examples/` directory for reference

## Scoring System

UDQSS evaluates datasets across multiple dimensions including:

- Data Completeness
- Data Accuracy
- Data Consistency
- Data Timeliness
- Data Validity
- Documentation Quality
- Format Compliance

Each dimension is scored on a standardized scale, with detailed scoring criteria available in the scoring guide.

## Templates

- **PDF Questionnaire**: Print-friendly assessment form for manual evaluations
- **Excel Template**: An automated scoring calculator with built-in formulas
- **Example Datasets**: Sample evaluations across different domains

## Customization

UDQSS can be adapted for specific domains while maintaining compatibility with the core standard. See [customization.md](docs/customization.md) for guidelines.

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Key areas for contribution:
- Additional domain-specific examples
- Template improvements
- Documentation enhancements
- Scoring methodology refinements

## License

This project is licensed under the [LICENSE] - see the LICENSE file for details.

## Community

- [Report Issues](/.github/ISSUE_TEMPLATE.md)
- [Submit Feature Requests](/.github/ISSUE_TEMPLATE.md)

## Documentation

Complete documentation is available in the `docs/` directory:
- [Quality Parameters](docs/parameters.md)
- [Scoring Methodology](docs/scoring-guide.md)
- [Customization Guide](docs/customization.md)

## Acknowledgments

UDQSS is a community-driven project aimed at improving data quality standards across industries. Originally initiated by [Opendatabay](https://opendatabay.com) as part of their mission to advance data quality standards, the project has grown into a collaborative, open-source effort.

We extend our gratitude to all contributors who continue to support and enhance this framework, ensuring its transparency, accessibility, and universal applicability.

---

For more information, visit [udqss.org](https://udqss.org) (Coming soon)
