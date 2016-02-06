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

### Scope 

The express project is composed of a collection of separate modules and 
documentation currently spread out over multiple GitHub organizations. This top 
level project would consist initially of the following components:

* strongloop
  * strongloop/express 
* jshttp
  * jshttp/accepts
  * jshttp/basic-auth
  * jshttp/compressible
  * jshttp/content-disposition
  * jshttp/content-type
  * jshttp/cookie
  * jshttp/compressible
  * jshttp/etag
  * jshttp/forwarded
  * jshttp/fresh
  * jshttp/http-errors
  * jshttp/media-typer
  * jshttp/methods
  * jshttp/mime-db
  * jshttp/mime-types
  * jshttp/negotiator
  * jshttp/on-finished
  * jshttp/on-headers
  * jshttp/proxy-addr
  * jshttp/range-parser
  * jshttp/statuses
  * jshttp/type-is
  * jshttp/vary
* expressjs
  * expressjs/basic-auth-connect
  * expressjs/body-parser
  * expressjs/compression
  * expressjs/timeout
  * expressjs/cookie-parser
  * expressjs/cookie-session
  * expressjs/csrf-tokens
  * expressjs/csurf
  * expressjs/errorhandler
  * expressjs/express-generator
  * expressjs/express-session
  * expressjs/keygrip
  * expressjs/method-override
  * expressjs/morgan
  * expressjs/response-time
  * expressjs/serve-favicon
  * expresjs/serve-index
  * expressjs/serve-static
  * expressjs/vhost
* pillarjs
  * pillarjs/cookies
  * pillarjs/csrf
  * pillarjs/extend-proto
  * pillarjs/finalhandler
  * pillarjs/parseurl
  * pillarjs/path-to-regexp
  * pillarjs/resolve-path
  * pilljarjs/router
  * pillarjs/send
* stream-utils
  * stream-utils/destroy
  * stream-utils/pause
  * stream-utils/unpipe
* other
  * component/escape-html
  * dougwilson/depd
  * visionmedia/bytes.js
  * crypto-utils/random-bytes
  * crypto-utils/uid-safe

In addition, strongloop will contribute the basic express API documentation 
included in the strongloop/expressjs.com to the strongloop/express repository.

### Formation of an Express TC

The current GitHub organization owners for each of the pillarjs, expressjs, 
and jshttp GitHub organizations will be invited to form the TC of the Express 
Top Level project. It is not expected that every existing owner will wish to 
participate. Two months after the initial invitation, any owner that is not 
actively participating would be automatically removed from the TC.

Anyone currently having Collaborator permissions to any of the above listed 
repositories will continue to have those permissions. Onboarding of new
Collaborators would follow a process decided by the Express TC but it is 
expected to be similar, if not identical, to the process used by Node.js core.

The Express TC's purpose is the support, maintenance and further development of 
the Express top level project under the Node.js Foundation.

The TC's responsibilities include:

* Management of the full set of GitHub repositories listed above
* Technical direction of the overall Express project
* Express Project governance and process
* Contribution policy
* GitHub repository hosting
* Conduct guidelines
* Maintaining the list of additional Collaborators

### Contribution and Governance Process

The contribution and governance policies would be bootstrapped using the basic 
document templates provided by the Node.js TSC, and fine tuned / customized by 
the Express TC once formed. It is expected that the contribution policy would 
be very similar to that used by Node.js core. 

The Node.js Code of Conduct, Moderation Policy and TSC Escalation policies 
would apply. 

The Node.js TSC will select one or more mentors to assist the Express TC in 
it's formation and throughout the Top Level Project incubation process.

### Intellectual Property and Other Assets

TBD

[Top Level Project of the Node.js Foundation]: https://github.com/nodejs/TSC/blob/master/Project-Lifecycle.md#top-level-project-and-working-group-requirements
[Developer's Certificate of Origin]: https://github.com/nodejs/node/blob/master/CONTRIBUTING.md#developers-certificate-of-origin-10
