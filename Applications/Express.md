## Express

The express project is applying to become an incubating
[Top Level Project of the Node.js Foundation][].

### About Express, User base, Community and Ecosystem

Express is one of the most popular web server frameworks available for Node.js.
For many Node.js developers, express is their primary interface with Node.js
on the server.

Express has consistently been among the top packages installed via npm, with
nearly 4.5 million downloads in just the past month.

It is important to recognize that Express is not the only web framework in the
Node.js ecosystem and that by incubating Express, neither the Node.js
Foundation or Node.js core would be "picking a winner" or endorsing Express
over any other overlapping or similar project.

### Formation of an Express WG

The express project consists of a single top level core repository
(strongloop/express) that has dependencies on a large number of smaller
independent components that are currently spread out across multiple
independent GitHub repositories. This proposal moves only the
strongloop/express GitHub repository under the Node.js GitHub organization
(nodejs/express).

If the proposal for incubating express as a top level project is accepted, a
call for participation would be put out to existing Node.js GitHub organization
members and an "Express WG" (nodejs/express team in the github organization)
with commit rights to the nodejs/express repository would be created. This WG
would also initially include existing contributors to the strongloop/express
github repository who are not currently members of the Node.js GitHub
organization.

A secondary nodejs/express-release team would be created consisting of the
subset of collaborators directly involved in the release process. These would
be identified out of the members of the main Express WG (following the
precedence of the nodejs/build team).

While under incubation, there would be no formal "Express TC". If and when a
decision is made to charter the express project as a full top level project,
and if a core group of technical contributors has emerged out of the base of
collaborators, a formal TC can be established as part of the express TLP
charter. Initially, however, the bias is towards growing the base of
contributors as opposed to establishing or imposing a governing body.

Essentially, the "TC" will be whoever steps up to do the necessary work.

### Contribution and Governance Process

The contribution process would be the same lazy consensus model used by Node.js
core.

The Express WG would be chartered as a Top Level WG of the Node.js TSC and
would fall under the TSC's policies.

### Organizational Tools

* Current source code management: [GitHub](https://github.com/strongloop/express)
* Issue tracking: [GitHub](https://github.com/stringloop/express/issues)
* Releases: [GitHub](https://github.com/strongloop/express/releases) and [NPM](https://npmjs.org/package/express)

### Intellectual Property and Other Assets

TBD

### Important Documents

* Code of Conduct: the existing Node.js Code of Conduct would apply.
* DCO: the existing Node.js DCO would apply.
* [License](https://github.com/strongloop/express/blob/master/LICENSE)

[Top Level Project of the Node.js Foundation]: https://github.com/nodejs/TSC/blob/master/Project-Lifecycle.md#top-level-project-and-working-group-requirements
