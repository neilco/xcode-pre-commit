# xcode-pre-commit
**A git pre-commit for Xcode projects**

## What does it do?

This is a shell script that, when execute, will create in your git repository a pre-commit hook that will auto-increment the Build version string in your Xcode project whenever you commit your changes.

The hook uses a `<major>.<minor>.<revision>` versioning schema and it is the `<revision>` part that is incremented. This reflects the total number of commits made in the repository. 

## Usage

Execute `git init-pre-commit` in your local repo directory. The hook will be created in the `.git/hooks` directory. 

Now whenever you commit your changes, you will see an additional line in the output:

`Bumped build number to ...`

### Contact

[Neil Cowburn](http://github.com/neilco)  
[@neilco](https://twitter.com/neilco)

## License

[MIT license](http://neil.mit-license.org)

Copyright (c) 2013 Neil Cowburn (http://github.com/neilco/)

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
