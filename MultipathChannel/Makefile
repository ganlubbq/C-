#
# Generated by the Apple Project Builder.
#
# NOTE: Do NOT change this file -- Project Builder maintains it.
#
# Put all of your customizations in files called Makefile.preamble
# and Makefile.postamble (both optional), and Makefile will include them.
#

NAME = MultipathChannel

PROJECTVERSION = 2.8
PROJECT_TYPE = Framework

HFILES = cost207_channels.h environment_types.h GSMFading.h\
         GSMTapFading.h

OTHERLINKED = GSMFading.cc GSMTapFading.cc

OTHERSRCS = Makefile.preamble Makefile Makefile.postamble m.template\
            h.template

OTHERLINKEDOFILES = GSMFading.o GSMTapFading.o

MAKEFILEDIR = $(MAKEFILEPATH)/pb_makefiles
CURRENTLY_ACTIVE_VERSION = YES
DEPLOY_WITH_VERSION_NAME = A
CODE_GEN_STYLE = DYNAMIC
MAKEFILE = framework.make
NEXTSTEP_INSTALLDIR = /Library/Frameworks
WINDOWS_INSTALLDIR = $(FRAME_PATH)
PDO_UNIX_INSTALLDIR = /Library/Frameworks
LIBS = 
DEBUG_LIBS = $(LIBS)
PROF_LIBS = $(LIBS)


FRAMEWORK_PATHS = -F$(FRAME_PATH)
WINDOWS_PB_CFLAGS = -O1
FRAMEWORKS = -framework Buffers -framework C_Libraries\
             -framework Filters -framework Generators -framework GNU\
             -framework Polynomials -framework RandomDist
PUBLIC_HEADERS = GSMFading.h cost207_channels.h environment_types.h



NEXTSTEP_OBJCPLUS_COMPILER = /usr/bin/cc
WINDOWS_OBJCPLUS_COMPILER = $(DEVDIR)/gcc
PDO_UNIX_OBJCPLUS_COMPILER = $(NEXTDEV_BIN)/gcc
NEXTSTEP_JAVA_COMPILER = /usr/bin/javac
WINDOWS_JAVA_COMPILER = $(JDKBINDIR)/javac.exe
PDO_UNIX_JAVA_COMPILER = $(JDKBINDIR)/javac

include $(MAKEFILEDIR)/platform.make

-include Makefile.preamble

include $(MAKEFILEDIR)/$(MAKEFILE)

-include Makefile.postamble

-include Makefile.dependencies
