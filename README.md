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
  all the needed html, css, and javascript. Does not use
  any external libraries, etc.

* Private - available to as many people as possible while
  gathering as little information about you as possible. It is
  served as a static CDN object, there is no web server per se.
  When it runs it doesn't touch any other servers.
  In fact you can download and run it locally. (**)

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

Comments and suggestions welcome.

(*) At least any that we could find

(**) Even on your phone - and yes, even on your iPhone: go to
https://magnusson-institute.github.io/passphrase.us/ and "share" it to
a "web archive" and store it in your local (Files) storage. Then
various apps can open this locally (needs to be able to run
Javascript), such as GoodReader (no affiliation).
