# MurmurHash3.js
**A javascript implementation of [MurmurHash3](http://code.google.com/p/smhasher/source/browse/trunk/MurmurHash3.cpp?spec=svn145&r=144)'s x86 hashing algorithms.**

## Usage
```javascript
// Return a hash as a 32bit unsigned int:
murmurHash3.hash32("I will not buy this record, it is scratched.") // 2832214938

// Return a hash as a 128bit unsigned hex:
murmurHash3.hash128("I will not buy this tobacconist's, it is scratched.") // "ef3f78669b5b7ba200f3f98e889adeaf"

// Specify a seed (defaults to 0):
murmurHash3.hash32("My hovercraft is full of eels.", 25) // 2520298415

// Rebind murmurHash3:
somethingCompletelyDifferent = murmurHash3.noConflict()
```

## License

Copyright © 2012 Karan Lyons

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.