## Jedi ##

Jedi is a new template language (maybe do more such as url routing in the future)
inspired by Jade / Coffeekup and many others. It's still in alpha phase and very
unstable.

Jedi 0.9.8 is available now.

### Install ###

```npm install jedi -g```

### Usage ###

```jedi2php example.jedi```

```jedi2php -w example.jedi```

### Template Syntax ###

See examples/

### Known major bugs and limitations for 1.0 milestone

1. subtemplate fragments (which combine the power of Jade's mixin and block feature) is not implemented yet

2. @title = "Hello {username}" is not implemented yet

3. string concat and some other expression operators is not implemented

4. only one attribute is allowed in the same line of element

### IDE/editor support ###

Planned:

1. Code Browser
2. PHPStorm
3. CodeMirror / ACE

### Copyright & License ###

   Copyright 2012 HE Shi-Jun

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
