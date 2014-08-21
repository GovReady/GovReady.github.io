---
layout:       mlisting
permalink:    /postgres/
---

# PostgreSQL

PostgreSQL, often shortened to "Postgres" and pronounced "POST-gress," is an open source relational database management system. It is considered the most advanced RDBMS available through an open source license.

Postgres is highly scalable in terms of both users and data storage & retrieval, accommodating unlimited total database sizes, tables of up to 32 TB, and fields up to 1 GB.

## Project status

PostgreSQL is actively developed by a large community of contributors. Its core is modified <a href="http://git.postgresql.org/gitweb/?p=postgresql.git">multiple times per day</a>. The community maintains a robust <a href="http://www.postgresql.org/support/security/">log</a> of security vulnerabilities.

## FISMA-Certified Configurations

FISMA Certified Configurations of NodeJS for federal government use are achieved via appropriate NIST 800-53 controls on facility, Linux or Windows, and PostgreSQL.

### Available FISMA-certified configurations of PostgreSQL

PostgreSQL is an extremely popular DBMS, and instances of it certainly abound across USG. Perhaps the most prominent is <a href="http://data.gov">data.gov</a>, a clearinghouse of public US Government data hosted by the Postgres-powered CKAN software.

<a href="http://web.nvd.nist.gov/view/vuln/search-results?query=postgresql&search_type=all&cves=on">Recent NVD notices</a>

## Procurement

PostgreSQL is open source software and can be <a href="http://www.postgresql.org/download/">downloaded</a> free of charge.

## Support

Several vendors provide professional support for enterprise installations of PostgreSQL. Federal customers should note that <a href="www.enterprisedb.com">EnterpriseDB</a>, a PostgreSQL support firm that produces a proprietary version of the software, is <a href="www.carahsoft.com/enterprisedb/">available via Carahsoft</a>. 

### PPAS

EnterpriseDB's product is called Postgres Plus Advanced Server (PPAS). It is maintained as a proprietary fork of the community-supported PostgreSQL project, and is kept up-to-date with changes to the PostgreSQL core. PPAS includes several enhancements, including one-click installation, tuning controls, scalability features, and Oracle compatibility, which allows a Postgres-powered server to run applications that normally require Oracle DBMS.

PPAS is freely downloadable for trial usage. Subscribers receive support via a web-based portal with a 24x7 one-hour SLA.

EnterpriseDB claims PPAS installations on DoD's NIPRNET, SIPRNET, and JWICS networks, and is developing a DISA STIG. Because it is maintained as a separate branch from PostgreSQL, security updates to PostgreSQL are not always applied to PPAS immediately. Depending on the severity and complexity of patches, this process can take hours or months.

