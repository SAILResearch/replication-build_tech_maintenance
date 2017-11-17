# Replication Package for "A Large-Scale Empirical Study of the Relationship Between Build Technology and Build Maintenance"

Shane McIntosh, Meiyappan Nagappan, Bram Adams, Audris Mockus, and Ahmed E. Hassan  
[Empirical Software Engineering Journal, vol. 20, issue 6, 2015](http://dx.doi.org/10.1007/s10664-014-9324-x)

Abstract: Build systems specify how source code is translated into deliverables. They require continual maintenance as the system they build evolves. This build maintenance can become so burdensome that projects switch build technologies, rewriting potentially thousands of lines of build code. We aim to understand the relationship between build technology and build maintenance by analyzing version histories in a corpus of 843,976 repositories spread across four software forges, three software ecosystems, and four large-scale projects. We study low-level, abstraction-based, and framework-driven build technologies, as well as tools that automatically manage external dependencies. We find that modern, framework-driven technologies are associated with more churn and a tighter coupling with source code than low-level and abstraction-based ones. Technology migrations tend to reduce source-build coupling and shift build maintenance work to a build-focused team. Our findings raise important questions for research and practice (e.g., why are modern build technologies associated with more maintenance?) and provide an approach that we expect to help answer them.

## Bibtex

```bibtex
@article{Mcintosh:2015:LES:2837368.2837384,
 author = {Mcintosh, Shane and Nagappan, Meiyappan and Adams, Bram and Mockus, Audris and Hassan, Ahmed E.},
 title = {A Large-Scale Empirical Study of the Relationship Between Build Technology and Build Maintenance},
 journal = {Empirical Softw. Engg.},
 issue_date = {December  2015},
 volume = {20},
 number = {6},
 month = dec,
 year = {2015},
 issn = {1382-3256},
 pages = {1587--1633},
 numpages = {47},
 url = {http://dx.doi.org/10.1007/s10664-014-9324-x},
 doi = {10.1007/s10664-014-9324-x},
 acmid = {2837384},
 publisher = {Kluwer Academic Publishers},
 address = {Hingham, MA, USA},
 keywords = {Build systems, Large-scale analysis, Open source, Software maintenance},
}
```

## Data and Scripts

- Data extraction
  - [File extension pattern matching tool](https://github.com/SAILResearch/replication-build_tech_maintenance/releases/latest)
  - [Data extraction scripts](https://github.com/smcintosh/WoC_classifier)
- Unfiltered figures
  - [Build commit proportion](figures/forges_monthly_rates.pdf)
  - [Build change size](figures/forges_monthly_sizes.pdf)
  - [Build churn rate](figures/forges_monthly_churn.pdf)
  - [Source-build coupling](figures/forges_monthly_coupling.pdf)
  - [Build authorship](figures/forges_monthly_authors.pdf)
