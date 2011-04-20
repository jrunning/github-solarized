I figured out GitHub's styles mostly by brute force, looking at source listings
and eyeballing the `class=` attributes. Here are the notes I took along the way
for each class. It's by no means complete and only represents what I observed in
the few files I checked.

* `bp`: Special variable e.g. `__FILE__` or `None`

* **Comments**
  * `c`:    HTML, CSS comment
  * `c1`:   Single-line comment  (`# ...` or `// ...`)
  * `cm`:   Multi-line comment (`/* ... */`)
  * `cp`:   Declaration e.g. `#include ...` or `<!DOCTYPE ...>`

* **Diffs**
  * `gd`:   Diff deletion
  * `gd.x`: Diff inline deletion
  * `gi`:   Diff insertion
  * `gi.x`: Diff inline insertion

* **Keywords**
  * `k`:    Keyword e.g. `this`, `else`, `do`, or CSS's `margin`, `bold`
  * `kd`:   Variable, function declaration
  * `kt`:	  Type e.g. `int`, `void`

* **Literals**
  * `m`:    Literal value e.g. `800px` in CSS
  * `mi`:   Integer value e.g. `55`, `8L`
  * `mf`:   Float value e.g. `1.5`

* **Identifiers/variable names**
  * `n`:	  Generic
  * `na`:	  HTML attribute name e.g. `href=`
  * `nb`:   Declarations and special words, e.g.  `document` in JavaScript, `require` in Ruby, `NULL` in C
  * `nc`:   CSS class rule, Ruby class declaration
  * `nf`:   CSS id rule, C function declaration
  * `no`:   Ruby constant
  * `nn`:   Python module name e.g. "utils" in `import utils`
  * `nt`:   HTML tag, Haml tag, CSS tag rule
  * `nv`:   Bash variable name
  * `nx`:   JavaScript variable name or function call

* `o`:      Operators and symbols, e.g. `:`, `=`, `+`, `=>`, `::`

* `p`:      Brackets and grouping symbols, e.g. `{}`, `[]`, `()`, `,` in JavaScript, `/` in Haml (e.g. `%br/`)
* `px`:	    Property in JavaScript, e.g. "log" in `console.log`

* **Strings**
  * `s`:    Quoted HTML attribute value
  * `s1`:	  Single-quoted string
  * `s2`:   Double-quoted string
  * `ss`:	  Ruby symbol (`:through`)
  * `se`:	  `\` in Bash (line continuation)
  * `si`:   String interpolation
  * `sr`:   Regular expression

* **Variables**
  * `vc`:   Class variable
  * `vg`:   Global variable
  * `vi`:   Instance variable
