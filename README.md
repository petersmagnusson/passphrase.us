# passphrase.us

(Yet Another) Random password/passphrase generator

You can run it off Github:

https://magnusson-institute.github.io/passphrase.us/

It should also be served (redirected) from here:

https://passphrase.us

(This will redirect to a _static_ copy on the MI CDN)


## Philosophy

We developed this to address some shortcomings in existing, free, online
password/passphrase tools (*)

* Simplicity - complex choices are not helpful for the general public.

* Truly free - no ads, promotions, hidden agendas.

* Single file - one static file encapsulating
  all the needed html, css, and javascript. Does not access
  any libraries, external servers, nothing. Can be
  (and is) served as a static object off a CDN.

* A source of entropy other than the browser - the
  Crypto.getRandomValues() in modern browsers should be cryptographically
  strong, but that's not something a user can easily verify.
  We add "physical" entropy from the user (finger or mouse movement).

* Simple characterization of how "secure" a password is,
  with user choices kept as simple as possible.

* Careful explanation of choices and design - we've tried to
  be detailed (in the source code).

The development is currently funded and hosted by the Magnusson
Institute, and distributed as open source under the MIT license.

(*) At least any that we could find
