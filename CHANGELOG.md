
Change Log
==========================

1.1.0
--------------------------

### Changes

- Change to return just empty NSData instead nil if given data is empty
- Log error message if compression/decompression is failed.
    - [Note] This is a temporaly improvement.
      I'll migrate functions to throw NSError when Swift 2.0 becomes stable.
