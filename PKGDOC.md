# Documentation available in the software package

_Note_: this should be considered WIP as this document was semi-automatically produced and has missing items, such as, for
instance, the man(1) page for the `whence` command.

## Commands

-   **UNIX command interpreter** \
    [sh(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh.1),
    and [ksh93 memorandum](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh.memo)

-   **Builtins (or related)** \
    [enum(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/bltins/enum.c),
    [env(1)](https://github.com/ksh-community/ksh/blob/master/docs/ksh/scripts/env.txt),
    [builtins(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/data/builtins.c),
    [test(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/data/testops.c)

-   **AST build system** \
    [crossexec(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/crossexec.sh),
    [ditto(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/ditto.sh),
    [execrate(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/execrate.sh),
    [filter(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/filter.sh),
    [hurl(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/hurl.sh),
    [iffe(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/iffe.sh),
    [mamake(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/mamake.c),
    [mamprobe(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/mamprobe.sh)
    (and [here](https://github.com/ksh-community/ksh/blob/master/bin/mamprobe)),
    [mktest(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/mktest.sh),
    [package(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/package.sh)
    (and [here](https://github.com/ksh-community/ksh/blob/master/bin/package)),
    [ratz(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/ratz.c),
    [regress(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/regress.sh),
    [release(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/release.c),
    [rt(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/rt.sh),
    [shtests(1)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/tests/shtests)

## Libraries

-   **libast** \
    [LIBAST(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/LIBAST.3),
    [aso(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/aso.3),
    [ast(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/ast.3),
    [astsa(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/astsa.3),
    [cdt(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/cdt.3),
    [chr(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/chr.3),
    [compat(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/compat.3),
    [error(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/error.3),
    [find(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/find.3),
    [fmt(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/fmt.3),
    [fmtls(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/fmtls.3),
    [fs3d(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/fs3d.3),
    [ftwalk(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/ftwalk.3),
    [getcwd(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/getcwd.3),
    [hash(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/hash.3),
    [iblocks(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/iblocks.3),
    [int(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/int.3),
    [ip6(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/ip6.3),
    [magic(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/magic.3),
    [mem(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/mem.3),
    [mime(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/mime.3),
    [modecanon(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/modecanon.3),
    [optget(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/optget.3),
    [path(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/path.3),
    [preroot(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/preroot.3),
    [proc(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/proc.3),
    [re(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/re.3),
    [regex(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/regex.3),
    [setenviron(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/setenviron.3),
    [sfdisc(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/sfdisc.3),
    [sfio(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/sfio.3),
    [sig(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/sig.3),
    [spawnveg(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/spawnveg.3),
    [stak(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/stak.3),
    [stk(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/stk.3),
    [strcopy(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strcopy.3),
    [strdup(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strdup.3),
    [strelapsed(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strelapsed.3),
    [strerror(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strerror.3),
    [stresc(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/stresc.3),
    [streval(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/streval.3),
    [strgid(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strgid.3),
    [strmatch(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strmatch.3),
    [stropt(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/stropt.3),
    [strperm(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strperm.3),
    [strsignal(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strsignal.3),
    [strsort(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strsort.3),
    [strtape(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strtape.3),
    [strton(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/strton.3),
    [struid(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/struid.3),
    [swap(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/swap.3),
    [tab(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/tab.3),
    [tm(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/tm.3),
    [tmx(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/tmx.3),
    [tok(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/tok.3),
    [touch(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/touch.3),
    [tv(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/tv.3),
    [vecargs(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/vecargs.3),
    [vmalloc(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/vmalloc.3)

-   **libcmd** \
    [basename(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/basename.c),
    [cat(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cat.c),
    [chgrp(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/chgrp.c),
    [chmod(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/chmod.c),
    [cksum(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cksum.c),
    [cmp(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cmp.c),
    [comm(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/comm.c),
    [cp(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cp.c),
    [cut(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cut.c),
    [date(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/date.c),
    [dirname(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/dirname.c),
    [expr(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/expr.c),
    [fds(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/fds.c),
    [fmt(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/fmt.c),
    [fold(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/fold.c),
    [getconf(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/getconf.c),
    [head(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/head.c),
    [id(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/id.c),
    [join(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/join.c),
    [logname(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/logname.c),
    [mkdir(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/mkdir.c),
    [mkfifo(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/mkfifo.c),
    [mktemp(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/mktemp.c),
    [paste(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/paste.c),
    [pathchk(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/pathchk.c),
    [pids(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/pids.c),
    [rev(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/rev.c),
    [rm(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/rm.c),
    [rmdir(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/rmdir.c),
    [stty(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/stty.c),
    [sync(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/sync.c),
    [tail(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/tail.c),
    [tee(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/tee.c),
    [tty(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/tty.c),
    [uname(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/uname.c),
    [uniq(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/uniq.c),
    [vmstate(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/vmstate.c),
    [wc(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/wc.c)

-   **libcoshell** \
    [coshell(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcoshell/coshell.3)

-   **libshell** \
    [shell(3)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/shell.3)

-   **libnval** \
    [nval(3)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/nval.3)

## Unclassified

[mkservice](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/bltins/mkservice.c),
[regress](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/bltins/regress.c),
[bash](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh/bash.c),
[shcomp](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh/shcomp.c),
[nvtype](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh/nvtype.c)

See also HTML files:
[index (outer)](https://github.com/ksh-community/ksh/blob/master/docs/index.html),
[index (inner)](https://github.com/ksh-community/ksh/blob/master/docs/ksh/index.html),
[builtins](https://github.com/ksh-community/ksh/blob/master/docs/ksh/builtins.html),
[examples](https://github.com/ksh-community/ksh/blob/master/docs/ksh/examples.html),
[features](https://github.com/ksh-community/ksh/blob/master/docs/ksh/features.html),
[faq](https://github.com/ksh-community/ksh/blob/master/docs/ksh/faq.html),
[ksh](https://github.com/ksh-community/ksh/blob/master/docs/ksh/ksh.html)
