# LinkAPI
LinkAPI is a userscript designed to recognise API mentions in Stack Overflow posts and link them to their official API documentations.

## User guide
1. Install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en) Chrome extension
2. Click the extension in the toolbar and select `Add a new script...` from the popup
3. Copy the content in `LinkAPI.js` and paste into the script editor
4. Click the save button or press `Ctrl + S` to load the script
5. Browse any Stack Overflow page or [sample page](http://stackoverflow.com/questions/35782929/pandas-groupby-memory-deallocation) and see the magic happens! (Currently only support posts with Python, Pandas, Matplotlib or Numpy tags)

## License
The MIT License (MIT)

Copyright (c) 2016 Foo Chee Yong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.