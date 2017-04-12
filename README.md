# nodejs
Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine

![node0](https://cloud.githubusercontent.com/assets/23619819/24941063/7ed985be-1f15-11e7-99c5-f5e4b2d0d444.PNG)
![node1](https://cloud.githubusercontent.com/assets/23619819/24941064/81ec8896-1f15-11e7-9c3b-cefb92247c10.PNG)

## WHAT IS NODE?
#### NODE IS JAVASCRIPT ON THE SERVER
First, a quick note: The terms “Node.js” and “Node” are used
interchangeably. The official description according to the nodejs.
org website is:
“Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine”
Translation: Node runs on Google’s open source JavaScript engine
called V8, which is written in C++ and is used in Google’s Chrome
browser. It’s fast!
“Node.js uses an event-driven, non-blocking I/O model that makes it
lightweight and efficient.”
Translation: Node.js pairs JavaScript’s naturally event-driven,
asynchronous coding style with non-blocking I/O libraries for
performing server tasks such as working with file systems and
databases. This pairing makes it easy to write fast, efficient, and
non-blocking applications that would be difficult and complex to
author in traditionally synchronous languages.
“Node.js' package ecosystem, npm, is the largest ecosystem of open source
libraries in the world.”
Translation: npm (name always lower-case) is the tool used to
install and manage dependencies in the Node world as well as the
main repository where public Node.js packages are registered. In
addition to Node.js libraries, npm also lists more and more frontend
packages, but that’s a different topic!

### HOW DOES NODE WORK?
### SYNCHRONOUS VS. ASYNCHRONOUS PROGRAMMING
C and Java traditionally use synchronous I/O, which means that
when a program starts an I/O operation, the rest of the program
stops until that operation is completed. You can get around this
by writing multi-threaded programs, but for some developers,
writing these types of applications in a distributed networking
environment can be daunting. Of course there is also the issue
of the number of threads a system can actually spawn, and
writing “thread-safe” code adds significant complexity to any
codebase. Node, by contrast, is single-threaded, but provides for
asynchronous and non-blocking code by default
### WHAT IS NODE GOOD FOR?
#### WEB APPLICATIONS
Many modern web applications are SPAs (single page applications)
that put most rendering and UI concerns in the client code, calling the
server only to request or update data.
#### REASONS WHY:
• Single page applications most frequently request and send
data (e.g. JSON) rather than rendered pages (HTML), thus
payloads are smaller but more frequent. Node’s asynchronous
model excels at handling these high-frequency, smallpayload
requests.
• Node’s rich ecosystem of npm modules allows you to build
web applications front to back with the relative ease of a
scripting language that is already ubiquitously understood on
the front end.
• Single Page Applications must be written in (or compiled to)
JavaScript. A Node backend means the whole stack is in
one language.
#### EXAMPLES OF FRAMEWORKS FOR NODE:
• LoopBack
• Express
• Sails.js
• Hapi
• Meteor
• MEAN.js
#### API SERVERS AND MOBILE BACKENDS
An I/O library at its heart, Node.js is a popular choice for APIs and
mobile backends. Node’s ease of use has been applied toward the
classic enterprise application use case to be able to gather and
normalize existing data and services.
#### REASONS WHY:
• As the shift toward hybrid mobile applications becomes more
dominant in the enterprise, client JavaScript code can be
leveraged on the server.
• Node’s rich ecosystem has almost every underlying driver or
connector to enterprise data sources such as RDBMS, Files,
NoSQL, etc. that would be of interest to mobile clients.
• JSON, the de-facto standard format for API data interchange, is
a representation of native JavaScript objects, so of course Node
handles it easily. If you need to support another format (for
example, XML), there’s probably a module for it.
#### EXAMPLES OF MOBILE BACKENDS BUILT WITH NODE:
• LoopBack (Open-source framework)
• FeedHenry (Proprietary)
• Appcelerator Cloud Services (Proprietary)
• Restify (Open-source framework)
#### IoT SERVERS
As more objects in the workplace, the home, and beyond get
connected into the “Internet of Things,” Node.js is emerging as the
server technology of choice for many IoT platforms.
#### REASONS WHY:
• Sensors reporting temperature, vehicle speed, etc. can
generate lots of data points, each one as small as a single
number. Node.js is built to efficiently handle this sort of “many
requests, small payloads” use-case.
• Node.js’ popularity as a platform for building APIs means that its
strengths and weaknesses here are well explored, and there are
many mature solutions that fit the IoT problem.
#### EXAMPLES OF OPEN SOURCE IOT SERVERS BUILT IN NODE:
• Zetta
• mqtt-connection
• adafruit-io
• phant
### HOW CAN I MAKE NODE USEFUL?
#### WHAT IS NPM?
Node Package Manager (“npm”) is the command-line package manager
for Node that manages dependencies for your application. npmjs.com
is the public repository where you can obtain and publish modules.
HOW DOES NPM WORK?
For your Node application to be useful, it needs things like libraries,
web and testing frameworks, data-connectivity, parsers and other
functionality. You enable this functionality by installing specific
modules via npm. npm comes bundled with Node.js (since v0.6.3) so
you can start using it right away!
You can install any package with this command:
$ npm install <name of module>
Some popular and most used modules include:
#### express
A fast, unopinionated, minimalist web framework for Node. Express
aims to provide small, robust tooling for HTTP servers, making it a
great solution for single page applications, web sites, hybrids, or public
HTTP APIs.
#### lodash
A “toolbelt” utility library with methods for performing lots of
common JavaScript tasks. It can be used stand-alone, in conjunction
with other small libraries, or in the context of a larger framework.
#### async
A utility module that provides straightforward, powerful functions
for working with asynchronous JavaScript. Although originally
designed for use with Node, it can also be used directly in the
browser. Async provides around 20 functions that include the usual
'functional' suspects (map, reduce, filter, each…) in addition to your
async function.
![node2](https://cloud.githubusercontent.com/assets/23619819/24941065/81f0f0de-1f15-11e7-8065-f495c8571b0d.PNG)
