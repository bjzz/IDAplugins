PROC=st9
DESCRIPTION=ST9 Family:st9
ADDITIONAL_GOALS=config

!include ..\module.mak

config: $(C)st9.cfg
$(C)st9.cfg: st9.cfg
	$(CP) $? $@


# MAKEDEP dependency list ------------------
$(F)ana$(O)     : $(I)area.hpp $(I)auto.hpp $(I)bytes.hpp $(I)diskio.hpp    \
	          $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp $(I)ida.hpp        \
	          $(I)idp.hpp $(I)kernwin.hpp $(I)lines.hpp $(I)llong.hpp   \
	          $(I)loader.hpp $(I)nalt.hpp $(I)name.hpp $(I)netnode.hpp  \
	          $(I)offset.hpp $(I)pro.h $(I)queue.hpp $(I)segment.hpp    \
	          $(I)srarea.hpp $(I)struct.hpp $(I)ua.hpp $(I)xref.hpp     \
	          ../idaidp.hpp ana.cpp ins.hpp st9.hpp
$(F)emu$(O)     : $(I)area.hpp $(I)auto.hpp $(I)bytes.hpp $(I)diskio.hpp    \
	          $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp $(I)ida.hpp        \
	          $(I)idp.hpp $(I)kernwin.hpp $(I)lines.hpp $(I)llong.hpp   \
	          $(I)loader.hpp $(I)nalt.hpp $(I)name.hpp $(I)netnode.hpp  \
	          $(I)offset.hpp $(I)pro.h $(I)queue.hpp $(I)segment.hpp    \
	          $(I)srarea.hpp $(I)struct.hpp $(I)ua.hpp $(I)xref.hpp     \
	          ../idaidp.hpp emu.cpp ins.hpp st9.hpp
$(F)ins$(O)     : $(I)area.hpp $(I)auto.hpp $(I)bytes.hpp $(I)diskio.hpp    \
	          $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp $(I)ida.hpp        \
	          $(I)idp.hpp $(I)kernwin.hpp $(I)lines.hpp $(I)llong.hpp   \
	          $(I)loader.hpp $(I)nalt.hpp $(I)name.hpp $(I)netnode.hpp  \
	          $(I)offset.hpp $(I)pro.h $(I)queue.hpp $(I)segment.hpp    \
	          $(I)srarea.hpp $(I)struct.hpp $(I)ua.hpp $(I)xref.hpp     \
	          ../idaidp.hpp ins.cpp ins.hpp st9.hpp
$(F)out$(O)     : $(I)area.hpp $(I)auto.hpp $(I)bytes.hpp $(I)diskio.hpp    \
	          $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp $(I)ida.hpp        \
	          $(I)idp.hpp $(I)kernwin.hpp $(I)lines.hpp $(I)llong.hpp   \
	          $(I)loader.hpp $(I)nalt.hpp $(I)name.hpp $(I)netnode.hpp  \
	          $(I)offset.hpp $(I)pro.h $(I)queue.hpp $(I)segment.hpp    \
	          $(I)srarea.hpp $(I)struct.hpp $(I)ua.hpp $(I)xref.hpp     \
	          ../idaidp.hpp ins.hpp out.cpp st9.hpp
$(F)reg$(O)     : $(I)area.hpp $(I)auto.hpp $(I)bytes.hpp $(I)diskio.hpp    \
	          $(I)entry.hpp $(I)fpro.h $(I)frame.hpp $(I)funcs.hpp      \
	          $(I)ida.hpp $(I)idp.hpp $(I)kernwin.hpp $(I)lines.hpp     \
	          $(I)llong.hpp $(I)loader.hpp $(I)nalt.hpp $(I)name.hpp    \
	          $(I)netnode.hpp $(I)offset.hpp $(I)pro.h $(I)queue.hpp    \
	          $(I)segment.hpp $(I)srarea.hpp $(I)struct.hpp $(I)ua.hpp  \
	          $(I)xref.hpp ../idaidp.hpp ../iocommon.cpp ins.hpp        \
	          reg.cpp st9.hpp
