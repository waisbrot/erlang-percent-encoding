Please see this Google Groups message for some context:

    http://groups.google.com/group/erlang-programming/msg/5f69c5a153f40eb7


My aim was/is to develop a correct implementation of both definitions/uses
of percent encoding, i.e., RFC 1738 and RFC 3986.

Speed/performance is not a major concern, and this is definitely not intended
as a "performance shoot out". The point of the percent_bench module was to
demonstrate how ridiculously slow the oauth_uri implementation was compared
to the other implementions (disclaimer: I wrote it).

If you can provide test cases for either encoding which the percent module
does not pass then please send a patch (or fork and fix).
