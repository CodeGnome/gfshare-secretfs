# What is this repository?
This is a mirror of the *secretfs* codebase written by [Daniel
Silverstone][2] and copyright 2011. The license appears to be a
permissive, attribution-only but I'm unable to identity the actual
license in use.

# Sources
The sources for this mirror are:

1. <http://www.digital-scurf.org/software/secretfs>
1. <https://git.gitano.org.uk/libgfshare.git/>

# Authenticity
I have no availability to authenticate the sources, other than a brief
Twitter exchange I had with Daniel back in September of 2015. It's
reproduced below.

![Caption: Twitter exchange from 2015.][1]

Please note that the mirrored code is not signed, and is not actively
maintained. With that in mind, the authenticity of the source is stale
at best.

# Security
I lack the C and cryptographic expertise to vet the source code myself.
It may work; it may not. It may be safe; it may not. My goal was simply
to preserve the only FUSE-based secret-sharing file system I know of for
automatic management of OpenPGP keys, but the project has not seen any
attention for a long time, and is in need of experienced security
programmers to validate the implementation, audit the security of the
code, and fix any outstanding bugs (if any).

# Getting Involved
To avoid remaining a legacy  project, this repository needs a number of
things. Please consider contributing as you're able.

1. Code auditing.
1. Security auditing.
1. Validation of the cryptographic implementation.
1. Improved documentation on how to *use* the software, ideally in the
   wiki.
1. A statement of support from the original author.
1. A formal port to GPL3 by the original author.

# Final Thoughts
I consider myself a steward for this project, rather than the author's
successor. I would very much like to see this project brought up to
date, or forked into a more modern implementation should that be
necessary. The issue that this code addresses is too important to
languish, and I sincerely hope that the right sort of people will choose
to get involved.

[1]: https://github.com/CodeGnome/gfshare-secretfs/blob/master/images/twitter_exchange.png
[2]: https://twitter.com/dsilverstone
