CONTIKI_PROJECT = udp-client-atividade4_alterada
all: $(CONTIKI_PROJECT)


CFLAGS += -DPROJECT_CONF_H=\"project-conf.h\"
CONTIKI = ../..
CONTIKI_WITH_IPV6 = 1
CFLAGS += -DUIP_CONF_ND6_SEND_NS=1
CFLAGS += -g
DEBUG = 1
APPS += powertrace
PROJECT_SOURCEFILES += protocol.c cetic-6lbr-client.c 

include $(CONTIKI)/Makefile.include
