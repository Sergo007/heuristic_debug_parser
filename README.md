This crate makes a best-effort attempt to parse the output of Rust `Debug` into a structure. My motivation is to facilitate neater output in test pretty response, but there are probably other places where it is useful, e.g. to convert debug output into json to send to some logfile.

Fork from
- [debug_parser](https://github.com/richard-uk1/debug_parser)
- [darrentsung_debug_parser](https://github.com/DarrenTsung/debug_parser)

Which differentes
- Actual libs
- add support rust key words in struct fields
