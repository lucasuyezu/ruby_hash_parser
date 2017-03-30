= blah

home  :: https://github.com/bibstha/ruby_hash_parser
code  :: https://github.com/bibstha/ruby_hash_parser
bugs  :: https://github.com/bibstha/ruby_hash_parser
... etc ...

== DESCRIPTION:

Parses a hash string of the format `'{ :a => "something" }'` into an actual ruby hash object `{ a: "something" }`.
This is useful when you by mistake serialize hashes and save it in database column or a text file and you want to
convert them back to hashes without the security issues of executing `eval(hash_string)`.

== FEATURES/PROBLEMS:

* Any potential security issues?

== INSTALL:

* Add to Gemfile: `gem 'hash_parser'`

== LICENSE:

(The MIT License)

Copyright (c) 2017 FIX

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.