# dataStone Inc.

PostgreSQL extension specialists solving production database challenges through evolution, not revolution.

We build custom extensions that bridge legacy systems with modern PostgreSQL infrastructure, enabling gradual modernization without disruptive "big bang" migrations. Our clients include enterprise system integrators and mainframe modernization specialists working with organizations transitioning from mainframe databases.

## Extensions

### Foundation Tools
**pg-helloworld** - Verify your environment is correctly configured for building PostgreSQL extensions. Tests compilation, installation, and runtime loading.

### Performance Optimizations
**pg-num2int-direct-comp** - Eliminate performance-destroying casts when comparing numeric types (decimal, numeric, float) with integer columns. Essential for schema mismatches in joins and lookups where index scans become table scans.

### Data Type Enhancements  
**pg-text-insens** - Blank-insensitive text comparison for scenarios requiring flexible string matching without normalization overhead.

## Mainframe Integration
Extensions for connecting PostgreSQL to legacy mainframe systems - DB2 z/OS, IMS, and related technologies. Enables Foreign Data Wrapper (FDW) access patterns for gradual data migration.

*Repositories publishing soon*

## Migration Utilities
Tools for schema translation, data validation, and test data generation during database modernization projects.

*Repositories publishing soon*

## Contributing

We welcome feedback and issue reports:
- Bug reports with reproduction steps
- Feature requests with use case descriptions
- Performance observations from your environment
- Documentation improvements

We handle code development internally to maintain quality standards and architectural consistency. If you have implementation ideas, open an issue to discuss - we may incorporate the approach in future releases.

## Resources
- Technical Blog - Implementation guides and PostgreSQL internals
- [Website](https://datastone.ca) - Consulting services and case studies

## About
dataStone specializes in PostgreSQL C/C++ extension development for complex integration and performance challenges. We contribute open-source solutions for common problems and provide consulting for specialized requirements.

For extension support or custom development inquiries: dave.sharpe@datastone.ca
