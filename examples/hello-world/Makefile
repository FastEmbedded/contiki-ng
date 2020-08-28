CONTIKI_PROJECT = hello-world
all: $(CONTIKI_PROJECT)

TARGET = simplelink
BOARD = launchpad/cc1352r1
SMALL = 0
V = 1

CONTIKI = ../..

include $(CONTIKI)/Makefile.dir-variables
#MODULES += $(CONTIKI_NG_SERVICES_DIR)/shell
MODULES += os/services/rpl-border-router

include $(CONTIKI)/Makefile.include
