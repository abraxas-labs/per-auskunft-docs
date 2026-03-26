# PER Personenregister - Quality Reports

The product [SonarQube](https://www.sonarqube.org/) is used for static code analysis.

The quality profiles used for this are stored in the [sonar-quality-profiles](./sonar-quality-profiles/) directory.

## Quality Report

| Metric | API Gateway | Auskunft WebApp | Personenregister |
|---|---|---|---|
| Type | Backend | Frontend | Backend |
| Version | v2.81.4 | v1.13.0 | v3.11.0 |
| Used Quality Profiles | Personenregister v1.1 way (java)<br>Abraxas v1.2 way (xml) | Abraxas v1.1 way (css)<br>Abraxas v1.5 way (js)<br>Abraxas v1.6 way (ts)<br>Abraxas v1.2 way (web) | Personenregister v1.1 way (java)<br>Abraxas v1.2 way (xml) |
| Quality Gate | Passed | Passed | Passed |
| Vulnerabilities | 0 | 0 | 0 |
| Bugs | 0 | 0 | 4 |
| Code Smells | 48 | 27 | 314 |
| Accepted Issues | 0 | 0 | 131 |
| Security Hotspots | 2 | 0 | 0 |
| Coverage | 0.0% | 0.0% | 0.0% |
| Duplicated Lines | 66 | 83 | 1751 |
| Lines to Cover | 1837 | 960 | 30384 |
| Lines of Code (ncloc) | 5068 | 6592 | 72820 |
| Maintainability Rating | A | A | A |
| Reliability Rating | A | A | C |
| Security Rating | A | A | A |