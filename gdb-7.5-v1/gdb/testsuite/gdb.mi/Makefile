
srcdir = .

PROGS = basics c_variable cpp_variable var-cmd dw2-ref-missing-frame	\
	gdb669-pthreads gdb701 gdb792 mi-async mi-basics mi-break	\
	mi-cli mi-console mi-disassemble mi-eval mi-file		\
	mi-file-transfer mi-non-stop mi-non-stop-exit			\
	mi-ns-stale-regcache mi-nsintrall mi-nsmoribund mi-nsthrexec	\
	mi-pending mi-pthreads mi-read-memory mi-regs mi-return		\
	mi-reverse mi-simplerun mi-stack mi-stepi mi-syn-frame		\
	mi-var-block mi-var-child mi-var-cmd mi-var-cp mi-var-display	\
	mi-var-invalidate mi-var-invalidate_bis mi-watch		\
	mi2-amd64-entry-value mi2-basics				\
	mi2-break mi2-cli mi2-disassemble mi2-eval mi2-file		\
	mi2-pthreads mi2-regs mi2-return mi2-simplerun mi2-stepi	\
	mi2-var-block mi2-var-child mi2-var-cmd mi2-var-display		\
	mi2-watch until

MISCELLANEOUS = mi-pendshr.sl

all info install-info dvi install uninstall installcheck check:
	@echo "Nothing to be done for $@..."

clean mostlyclean:
	-rm -f *.ci *.o $(OBJS) $(PROGS) *~ core
	-rm -f *.dwo *.dwp
	-rm -f $(MISCELLANEOUS)

distclean maintainer-clean realclean: clean
	-rm -f Makefile config.status config.log gdb.log gdb.sum
