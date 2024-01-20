## TypeScript definitions for Strudel

This repository includes a TypeScript definitions file that I wrote for
[Strudel](https://github.com/tidalcycles/strudel).

It is _not_ a precise set of types – that is the reason I haven't opened PRs to
get them into Strudel core or DefinitelyTyped. Even in its current form, it is
lacking in more ways than one (e.g. it is incomplete, and unmaintained).

Still, these type definitions were useful to me:

1. By adding this file to my project I get context sensitive help and
   autocomplete in VS Code.

2. And I don't have to cast as any or otherwise silence the TypeScript compiler
   when using Strudel.

So I'm putting these in a separate repository in case they're useful to someone
else in the same boat. Feel free to take them and amend them for your own needs.

### Using

Add this file to your project, anywhere where the TypeScript compiler can see it
(e.g. `src/strudel-types.d.ts`).
