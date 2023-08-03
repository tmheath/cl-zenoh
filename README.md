# cl-zinoh
Interface into the Zinoh network protocol from Common Lisp using the Zenoh C bindings Rust project.


Unless this grows beyond myself, it's really just meant as a practical toy...
I decided to use Zenoh at work, started using Rust rather than dealing with
the C++ build system. I had the brilliant idea to create a small dsl for
repeating and chaining operations until success, with guarding or failing
or back tracking built in. Ended up banging my head against the wall. I
ended up succeeding but it took way too long. Figure this should be simpler.
Hoping other people end up using this... atypical espeacially considering a
track record of starting and deleting and making private and deleting accounts.
:)



NOTE
----

While browsing this earlier I didn't see a section on compiling for windows,
probably missed it but I saw it included in the cmake.
