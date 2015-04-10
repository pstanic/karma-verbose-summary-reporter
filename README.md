Karma (very) Verbose Summary Reporter
=============================

To install, just get the tarball from GitHub via NPM:

```
npm install --save-dev 'karma-verbose-summary-reporter'
```

This reporter is based on [karma-verbose-reporter](https://github.com/usrz/javascript-karma-verbose-reporter "Karma Verbose reporter").

Reports only detailed summary after the execution; can be combined with other reporters that report during test execution.

```
Suites and tests results:

 - decode :
   * should exist : 4 ok
   * should fail decoding garbage : 4 ok
   * should fail decoding null data : 4 ok
   * should fail decoding with unknown algorithm : 4 ok
   * should handle nested promises : 4 ok
   - BASE64 :
     * decode : 4 ok
   - HEX :
     * decode lower case : 4 ok
     * decode upper case : 4 ok
   - UTF8 :
     * decode : 4 ok
 - defer :
   * should defer a static value : 4 ok
   * should exist : 4 ok
   * should reject a thrown error : 4 ok
   * should reject a thrown string : 4 ok
   * should reject a wrapped rejected promise : 4 ok
   * should resolve a deferred function : 4 ok
   * should resolve a wrapped resolved promise : 4 ok
 - encode :
   * should exist : 4 ok
   * should fail encoding garbage : 4 ok
   * should fail encoding null data : 4 ok
   * should fail encoding with unknown algorithm : 4 ok
   * should handle nested promises : 4 ok
   - BASE64 :
     * encode : 4 ok
   - HEX :
     * encode : 4 ok
   - UTF8 :
     * encode Uint8Array : 4 ok
     * encode plain array : 4 ok
     * encode string (pass-through) : 4 ok
 - hash :
   * should exist : 4 ok
   - SHA-1 :
     * should hash 10k of binary data : 4 ok
     * should hash a well-known string : 4 ok
     * should hash empty data : 4 ok
   - SHA-224 :
     * should hash 10k of binary data : 4 ok
     * should hash a well-known string : 4 ok
     * should hash empty data : 4 ok
   - SHA-256 :
     * should hash 10k of binary data : 4 ok
     * should hash a well-known string : 4 ok
     * should hash empty data : 4 ok
   - SHA-384 :
     * should hash 10k of binary data : 4 ok
     * should hash a well-known string : 4 ok
     * should hash empty data : 4 ok
   - SHA-512 :
     * should hash 10k of binary data : 4 ok
     * should hash a well-known string : 4 ok
     * should hash empty data : 4 ok
 - subtle :
   * should digest : 2 ok, 2 skipped
   * should exist : 4 ok

Browser results:

 - Safari 8.0.0 (Mac OS X 10.10): 44 tests
   - 44 ok
 - Chrome 39.0.2171 (Mac OS X 10.10.0): 44 tests
   - 44 ok
 - PhantomJS 1.9.7 (Mac OS X): 44 tests
   - 43 ok, 1 skipped
 - Firefox 33.0.0 (Mac OS X 10.10): 44 tests
   - 43 ok, 1 skipped
```
