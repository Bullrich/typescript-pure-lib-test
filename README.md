## Typescript Pure Lib Test

The objective of this project is to make `lib-b` import `lib-a` as a Typescript pure project (this means no `js` files) and to compile them *only* when `lib-b` is compiling its source code.

To make it clear, `lib-a` should always have only typescript files. It should never be built because all of the projects that are gonna use it are already gonna be Typescript projects, and its intentional to evade that compilation.
