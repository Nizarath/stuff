### Краткий старый текст про Gentoo Linux (на удаление?)

Gentoo is a great GNU/Linux distribution, which offers:
- compilation of packages on the user side with flags, written in configuration files. Thus
  user programs may become lighter and faster (or vice versa, with including of additional
  functionality). Sometimes they may become broken, though, but it is still a great place
  for experiments. Another point is that this ensures the absence of malicious software
  frequently embedded into binaries.
- full overseeing over all dependencies. In this point Gentoo differs from Slackware or
  LFS, which are also source-based systems. In other words, one obtains flexibility of
  compilation based on their own needs, and is not obliged to check every dependency for
  compiling.
- full automatization in other areas as well, for instance just with one command one can start
  an updating of thousands of packages installed.
- exceedingly large amount of packages (though mostly in source form only, except for some
  large packages like firefox web-browser). Gentoo does not perform such license policy, as
  Debian, allowing non-GPL packages (though this does not mean that some malware is leaked,
  still everything is in source form).
- though it is better revealed in LFS, Gentoo still provides a better level of
  understanding of all system components -- what they are and how they interact -- than
  almost every other distro. Almost all configuration formats are understandable and clean,
  being presented in plain text files.

As can be seen, this distro combines source-based nature with thorough automatization of
everything (compiling and dependency checking is performed by Python-written package
management system called Portage). User intrudes only for setting compilation and some
other flags in files mostly located in /etc/portage and for resolving some problems which
sometimes occur (like circular dependencies, when A depends on B, B depends on C, and C
again depends on A (very seldomly neighbour packages depend on each other)), and are mostly
caused by inconsistency of compilation flags having been set.

Still, it has some disadvantages in comparison with binary based (but not with other
source-based) distros -- long compilation time is the conspicuous one, though it depends on
hardware and settings as well. Though it can be dwindled to some extent with SMP systems.

Nevertheless, it is one of the most powerful, logical and flexible distros allowing to build almost 
anything from it, depending on one's skills and desires, and use what has been built easily
afterwards.

by Nizarath
