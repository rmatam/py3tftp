# CHANGELOG

### 0.0.6 (October x, 2016)

- Removes type hints.
- Restructures project into more layers (ie. special packet objects, pulls out file IO from protocols), big API changes.
- Adds a suite of unit tests.
- Adds Travis-CI configuration files.

### 0.0.5 (March 21st, 2016)

- Fixes off by one server response to RRQs that are the multiple of the file's size.
- Adds type hints.
- Makes 'long description' rst.
- Adds test.sh to make running tests easier.

### 0.0.4 (March x, 2016)

- Adds CHANGELOG.md
- Fixes blksize errors.
- Adds tests for blksize and timeout options.
- Improves tftp option handling.


### 0.0.3 (March 1st, 2016)

- Restructuring for easier reuse.
- Fixed leftover file descriptor issue.

###0.0.2 (February 25th, 2016)

- Adds rfc2347 support.
- Adds rfc2348 (blksize) support.
- Adds part of rfc2349 support (timeout, no tsize).
- Adds final setup.py stuff.
