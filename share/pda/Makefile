BINARY=operator_test
TARGET=binary # binary, static, objects

SOURCES= \
operator_test.c

#-------------------------------------------------------

hook:
	$(MAKE) INCLUDEFILE=`pda-config --build` all 

clean:
	$(MAKE) INCLUDEFILE=`pda-config --build` cleaner 

include $(INCLUDEFILE)

all: $(TARGET)

#-------------------------------------------------------
# you can include your own rules here!
#-------------------------------------------------------

