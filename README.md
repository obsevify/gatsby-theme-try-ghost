# gatsby-ghost-casper
Casper v3 theme generated by Gatsby and served from Ghost headless CMS

## Project goals
- Ghost should serve as headless CMS
- Gatsby should do all frontend processing
- Generated static sites should come as close to the standard Ghost with Casper v3 theme as possible
- Casper v3 features like *Infinite Scroll*, *Sticky Nav Title* and *Gallery Card* should be supported
- Prioritize AMP pages (+ other SEO-related stuff)

## Not supported
- No additions that go beyond the Ghost default Casper v3 theme
- Dynamic functions, that are not easily replicated on a *static site* will be omitted (e.g. no members areas/functions)
- Features that need solutions in upstream repositories, will have to wait until those solutions are available

## Initial Approach
- Use gatsby-starter-ghost as a starting point
- Resemble the Casper v3 handlebars template structure in JSX  (so it is easy to compare both frontends)
- Use exactly the same css stylefiles as Casper v3

## Quality assurance
- qualitative tests
- possibly unit tests at a later time

## Playground

- https://github.com/styxlab/gatsby-starter-ghost
- branch casper-v3
- Casper and Ghost are included with the git *subtree method*

## Todos
- [x] Inital Development in Playground: *in progress*
- [ ] Public default Ghost Installation (serving as headless CMS)
- [ ] Move project over to this repo after basic strategy/concepts are clearly defined
