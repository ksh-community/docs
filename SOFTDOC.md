# Documentation available in the software package

_Note_: This is a first attempt at identifying all sources of documentation in the software package. Categorisation is currently
by markup language; this is not practical. Subsequent updates will allow to classify by domain such as _built-ins_, _build
system_, …

## UNIX man(1) pages

### Commands

-   [src/cmd/ksh93/sh.1](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh.1)

### Library functions

#### libast

-   [LIBAST(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/man/LIBAST.3),
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

#### libcoshell

-   [coshell(3)](https://github.com/ksh-community/ksh/blob/master/src/lib/libcoshell/coshell.3)

### libshell

-   [shell(3)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/shell.3)

#### libnval

-   [nval(3)](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/nval.3)

## AST `getopts(1)` markup

Below are files with embedded `getopts(1)` markup enabling the dynamic generation of man(1) pages, on-demand.


-   [bin/mamprobe](https://github.com/ksh-community/ksh/blob/master/bin/mamprobe)
-   [bin/package](https://github.com/ksh-community/ksh/blob/master/bin/package)
-   [docs/ksh/scripts/env.txt](https://github.com/ksh-community/ksh/blob/master/docs/ksh/scripts/env.txt)
-   [lib/package/ast-ksh.README](https://github.com/ksh-community/ksh/blob/master/lib/package/ast-ksh.README)

-   [src/cmd/INIT/mamprobe.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/mamprobe.sh)
-   [src/cmd/INIT/filter.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/filter.sh)
-   [src/cmd/INIT/hurl.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/hurl.sh)
-   [src/cmd/INIT/ratz.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/ratz.c)
-   [src/cmd/INIT/regress.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/regress.sh)
-   [src/cmd/INIT/mktest.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/mktest.sh)
-   [src/cmd/INIT/iffe.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/iffe.sh)
-   [src/cmd/INIT/execrate.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/execrate.sh)
-   [src/cmd/INIT/crossexec.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/crossexec.sh)
-   [src/cmd/INIT/package.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/package.sh)
-   [src/cmd/INIT/ditto.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/ditto.sh)
-   [src/cmd/INIT/rt.sh](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/rt.sh)
-   [src/cmd/INIT/release.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/release.c)
-   [src/cmd/INIT/mamake.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/INIT/mamake.c)

-   [src/cmd/ksh93/tests/shtests](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/tests/shtests)
-   [src/cmd/ksh93/bltins/mkservice.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/bltins/mkservice.c)
-   [src/cmd/ksh93/bltins/enum.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/bltins/enum.c)
-   [src/cmd/ksh93/bltins/regress.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/bltins/regress.c)
-   [src/cmd/ksh93/sh/bash.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh/bash.c)
-   [src/cmd/ksh93/sh/shcomp.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh/shcomp.c)
-   [src/cmd/ksh93/sh/nvtype.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/sh/nvtype.c)
-   [src/cmd/ksh93/data/builtins.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/data/builtins.c)
-   [src/cmd/ksh93/data/testops.c](https://github.com/ksh-community/ksh/blob/master/src/cmd/ksh93/data/testops.c)
-   [src/lib/libcmd/cp.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cp.c)
-   [src/lib/libcmd/vmstate.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/vmstate.c)
-   [src/lib/libcmd/tail.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/tail.c)
-   [src/lib/libcmd/cksum.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cksum.c)
-   [src/lib/libcmd/join.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/join.c)
-   [src/lib/libcmd/fds.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/fds.c)
-   [src/lib/libcmd/uniq.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/uniq.c)
-   [src/lib/libcmd/mkfifo.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/mkfifo.c)
-   [src/lib/libcmd/stty.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/stty.c)
-   [src/lib/libcmd/tee.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/tee.c)
-   [src/lib/libcmd/fold.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/fold.c)
-   [src/lib/libcmd/paste.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/paste.c)
-   [src/lib/libcmd/rm.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/rm.c)
-   [src/lib/libcmd/cat.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cat.c)
-   [src/lib/libcmd/wc.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/wc.c)
-   [src/lib/libcmd/getconf.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/getconf.c)
-   [src/lib/libcmd/pathchk.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/pathchk.c)
-   [src/lib/libcmd/dirname.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/dirname.c)
-   [src/lib/libcmd/basename.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/basename.c)
-   [src/lib/libcmd/mkdir.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/mkdir.c)
-   [src/lib/libcmd/pids.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/pids.c)
-   [src/lib/libcmd/head.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/head.c)
-   [src/lib/libcmd/sync.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/sync.c)
-   [src/lib/libcmd/chmod.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/chmod.c)
-   [src/lib/libcmd/uname.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/uname.c)
-   [src/lib/libcmd/tty.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/tty.c)
-   [src/lib/libcmd/mktemp.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/mktemp.c)
-   [src/lib/libcmd/cmp.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cmp.c)
-   [src/lib/libcmd/date.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/date.c)
-   [src/lib/libcmd/cut.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/cut.c)
-   [src/lib/libcmd/rmdir.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/rmdir.c)
-   [src/lib/libcmd/rev.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/rev.c)
-   [src/lib/libcmd/logname.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/logname.c)
-   [src/lib/libcmd/chgrp.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/chgrp.c)
-   [src/lib/libcmd/fmt.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/fmt.c)
-   [src/lib/libcmd/comm.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/comm.c)
-   [src/lib/libcmd/expr.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/expr.c)
-   [src/lib/libcmd/id.c](https://github.com/ksh-community/ksh/blob/master/src/lib/libcmd/id.c)

-   [ChangeLog](https://github.com/ksh-community/ksh/blob/master/src/lib/libast/RELEASE)

## HTML files

### ChangeLogs

-   [lib/package/INIT.html](https://github.com/ksh-community/ksh/blob/master/lib/package/INIT.html)
-   [lib/package/ast-ksh.html](https://github.com/ksh-community/ksh/blob/master/lib/package/ast-ksh.html)

### Other

-   [docs/index.html](https://github.com/ksh-community/ksh/blob/master/docs/index.html)
-   [docs/ksh/builtins.html](https://github.com/ksh-community/ksh/blob/master/docs/ksh/builtins.html)
-   [docs/ksh/index.html](https://github.com/ksh-community/ksh/blob/master/docs/ksh/index.html)
-   [docs/ksh/examples.html](https://github.com/ksh-community/ksh/blob/master/docs/ksh/examples.html)
-   [docs/ksh/features.html](https://github.com/ksh-community/ksh/blob/master/docs/ksh/features.html)
-   [docs/ksh/faq.html](https://github.com/ksh-community/ksh/blob/master/docs/ksh/faq.html)
-   [docs/ksh/ksh.html](https://github.com/ksh-community/ksh/blob/master/docs/ksh/ksh.html)
