## riotjs-brunch

Please see the original project for updates. This fork just changes the
dependencies to pull the newest version of Riot.js 3.

Adds [Riot](https://muut.com/riotjs/) support to [brunch](http://brunch.io).

## Usage
Install the plugin via npm with `npm install --save riot-brunch`.

Or, do manual install:

* Add `"riot-brunch": "x.y.z"` to `package.json` of your brunch app.
  Pick a plugin version that corresponds to your minor (y) brunch version.
* If you want to use git version of plugin, add
`"riot-brunch": "git+https://github.com/yavorsky/riot-brunch.git"`.


## Configuration


```
  plugins:
    on: ["riot"]
    riot:
      extension: 'tag'   # pattern overrides extension
      pattern: /\.tag$/  # default
      template: 'jade'
      type: 'coffeescript'
```

## License

The MIT License (MIT)

Copyright (c) 2015 Artem Yavorsky

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
