Exploring data with Noise
=========================

This repository contains all the dependencies and sample data to follow along
the blog post [Exploring data with Noise].


Data
----

The sample data [circl-cve.json] is a subset of the [JSON dump of the CVE
database provided by CIRCL] checked out on 2017-12-07. It was created via

    wget https://cve.circl.lu/static/circl-cve-search-expanded.json.gz
    unzip -c circl-cve-search-expanded.json.gz|head -1000 > circl-cve.json


License
-------

The sample data [circl-cve.json] is from [CIRCL Computer Incident Response
Center Luxembourg] licensed under an [international CC-BY 4.0].

[Exploring data with Noise]: http://vmx.cx/
[circl-cve.json]: circl-cve.json
[CIRCL Computer Incident Response Center Luxembourg]: https://www.circl.lu/
[JSON dump of the CVE database provided by CIRCL]: https://www.circl.lu/opendata/
[international CC-BY 4.0]: https://creativecommons.org/licenses/by/4.0/
