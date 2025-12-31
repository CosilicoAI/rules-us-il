# rules-us-il

Illinois rules in Akoma Ntoso XML format for the Cosilico ecosystem.

## Structure

```
rules-us-il/
├── statutes/           # Illinois Compiled Statutes (ILCS)
│   ├── 35-ILCS/        # Revenue (income tax, property tax)
│   └── 305-ILCS/       # Public Aid (SNAP, TANF, Medicaid)
└── regulations/        # Illinois Administrative Code (IAC)
    └── 86-IAC/         # Department of Revenue regulations
```

## Sources

### Statutes
- **Illinois Compiled Statutes (ILCS)**: https://www.ilga.gov/legislation/ilcs/ilcs.asp
  - 35 ILCS: Revenue
  - 305 ILCS: Public Aid

### Regulations
- **Illinois Administrative Code**: https://www.ilga.gov/commission/jcar/admincode/titles.html
  - Title 86: Revenue
  - Title 89: Social Services

## Akoma Ntoso Format

Documents are encoded in Akoma Ntoso XML, an OASIS standard for legislative documents. Each file contains:
- Hierarchical structure (chapters, articles, sections)
- Cross-references to other provisions
- Temporal versioning metadata
- Official citation identifiers

## Related Repositories

- [arch](https://github.com/CosilicoAI/arch) - Source document archive
- [rac](https://github.com/CosilicoAI/rac) - Rules as Code DSL
- [rac-us](https://github.com/CosilicoAI/rac-us) - US federal rules

## License

Source materials are public domain government documents. XML encoding licensed under Apache 2.0.
