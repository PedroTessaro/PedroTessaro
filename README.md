<picture>
  <source media="(prefers-color-scheme: light)" srcset="https://pedrotessaro.vercel.app/terminal.svg?theme=light">
  <img alt="Terminal showing: Pedro Tessaro, Backend Engineer. Go, Java, C/C++, PostgreSQL, Docker." src="https://pedrotessaro.vercel.app/terminal.svg">
</picture>

That terminal isn't a GIF. It's a Go service that renders the SVG on every
request, and the command it types actually answers:

```console
$ curl -s https://pedrotessaro.vercel.app/whoami
```

Code and the writeup on why animating a README is harder than it looks:
[portfolio-backend](https://github.com/PedroTessaro/portfolio-backend).

### What I work on

Backend, mostly Go these days, and the layers underneath it. A lot of what I've
built is about making those layers visible: assemblers, interpreters, a text
editor from raw-mode input up.

- [portfolio-backend](https://github.com/PedroTessaro/portfolio-backend) — the service above. Go, SMIL, Redis, Vercel
- [RSSAggregator](https://github.com/PedroTessaro/RSSAggregator) — feed aggregator in Go, concurrent fetching and a REST API
- [AssemblerImplementation](https://github.com/PedroTessaro/AssemblerImplementation) — two-pass assembler in Java, symbol table and relocation
- [ReversePolishNotationInterpreter](https://github.com/PedroTessaro/ReversePolishNotationInterpreter) — stack-based expression interpreter
- [parallel_programming_studies](https://github.com/PedroTessaro/parallel_programming_studies) — threads and synchronization in C
- [TextEditor](https://github.com/PedroTessaro/TextEditor) — terminal editor in C++

Currently going deeper into Go and distributed systems.

### Elsewhere

CS student and piano teacher. Before backend took over I wrote a fair number of
Swift apps at the Apple Developer Academy | Mackenzie — still in
[my repositories](https://github.com/PedroTessaro?tab=repositories), just not
what I'm building now.

[LinkedIn](https://www.linkedin.com/in/pedrotessaro/) · ptssar22@gmail.com
