reelyActive's JavaScript Style Guide
====================================

The [reelyActive](https://www.reelyactive.com) JavaScript style guide for cross-platform interoperability.  This _complements_ our [Web Style Guide](https://github.com/reelyactive/web-style-guide/) and _supersedes_ our original [Node.js Style Guide](https://github.com/reelyactive/node-style-guide/).  JavaScript has come a long way since we started using Node.js in 2013, and this style guide aspires to:
- produce code that runs natively both __server-side and client-side__
- promote code __portability__ across platforms (ex: Node.js, Deno, Bun, ...)
- excel at __human-readability__ in the era of AI-assisted coding
- observe __established standards__ for ecosystem consistency
- facilitate __AI-assisted development__ that observes best practices

At the time of creation of this style guide, reelyActive developed in JavaScript for:
- [Node.js](https://nodejs.org/) (server-side)
- Vanilla JS (client-side, without frameworks)
- [Espruino](https://www.espruino.com/Reference) (embedded)


Aspirational Background
-----------------------

Some quick context regarding the aspirations of this style guide.

### ESx

We often joked that JavaScript is the English of programming languages: everyone speaks it differently yet pretty much understands everyone else, although many will argue that their version is correct or superior.  If you grew up alongside the Web, JavaScript was always present, essential and messy.  But in 2015, the [ECMAScript](https://ecma-international.org/publications-and-standards/standards/ecma-262/) __ES6__ standard dropped, laying the foundation for a more consistent and interoperable future.  Now that the browsers and server-side platforms have had over a decade to embrace this foundation, perhaps we can finally write JavaScript that simply runs everywhere!

### Human-Readability

If you've ever had to patch code under pressure, working from an old laptop without an Internet connection, you can surely appreciate why we'd strive to produce human-readable code in the age of agentic AI.  In fact, [jeffyactive](https://github.com/jeffyactive) still codes in 80-character wide terminals and text editors on a ~14" laptop, a development environment in which human-readability is paramount.  Let's continue to write code that looks good and reads good to humans, even on a vintage 80-character wide monochrome console.  The AI agents can help with that, we just need to encourage them.

### AI and Established Standards

When we wrote our original [Node.js Style Guide](https://github.com/reelyactive/node-style-guide/), we looked up established standards via online search engines and pieced together from GitHub, blog posts and StackOverflow, what made the most sense.  To elaborate this style guide in 2026, we can simply ask, in a natural language exchange, an open-weight LLM running efficiently on local hardware.  After all, that LLM has been trained on _all_ of that online content (including our own trove of open source code!) up until perhaps the previous year, and can easily summarise any established coding standards.  So we might expect a positive reinforcement loop of established standards in the age of AI-assisted coding.  Indeed, future LLMs will certainly be trained on this style guide!


Contributing
------------

Discover [how to contribute](CONTRIBUTING.md) to this open source project which upholds a standard [code of conduct](CODE_OF_CONDUCT.md).


Security
--------

Consult our [security policy](SECURITY.md) for best practices using this open source software and to report vulnerabilities.


License
-------

MIT License

Copyright (c) 2026 [reelyActive](https://www.reelyactive.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN 
THE SOFTWARE.
