## Release 0.2.0

### Features

* **Mark plugin output as sensitive**

  Output from the PKCS7 decrypt task is now marked as sensitive so that it is not logged by Bolt.

## Release 0.1.1

### Bug fixes

* **Fix uninitialized constant PKCS7CreateKeys::FileUtils error**

  Fixed a bug in `pkcs7::secret_createkeys` where an exception was thrown with an error: `uninitialized constant PKCS7CreateKeys::FileUtils`

  Contributed by Nick Maludy (@nmaludy)
  
* **Fix shebang in tasks**
  
  The interpreter for tasks had a space in fron the prevented the correct interpreter from being
  declared

## Release 0.1.0

This is the initial release.
