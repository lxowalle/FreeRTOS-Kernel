noinst_LIBRARIES    = libfreertos.a

libfreertos_a_SOURCES   = tasks.c
libfreertos_a_SOURCES   += list.c
libfreertos_a_SOURCES   += queue.c
libfreertos_a_SOURCES   += timers.c
libfreertos_a_SOURCES   += croutine.c
libfreertos_a_SOURCES   += event_groups.c
libfreertos_a_SOURCES   += stream_buffer.c
libfreertos_a_SOURCES   += portable/Common/mpu_wrappers.c
libfreertos_a_SOURCES   += portable/MemMang/heap_4.c

libfreertos_a_CPPFLAGS  = -Iinclude

noinst_HEADERS          = include/task.h
noinst_HEADERS          += include/atomic.h
noinst_HEADERS          += include/croutine.h
noinst_HEADERS          += include/deprecated_definitions.h
noinst_HEADERS          += include/event_groups.h
noinst_HEADERS          += include/FreeRTOS.h
noinst_HEADERS          += include/list.h
noinst_HEADERS          += include/message_buffer.h
noinst_HEADERS          += include/mpu_prototypes.h
noinst_HEADERS          += include/mpu_wrappers.h
noinst_HEADERS          += include/portable.h
noinst_HEADERS          += include/projdefs.h
noinst_HEADERS          += include/queue.h
noinst_HEADERS          += include/semphr.h
noinst_HEADERS          += include/stack_macros.h
noinst_HEADERS          += include/StackMacros.h
noinst_HEADERS          += include/stream_buffer.h
noinst_HEADERS          += include/timers.h
noinst_HEADERS          += FreeRTOSConfig.h

# posix gcc
libfreertos_a_CPPFLAGS  += -Iportable/ThirdParty/GCC/Posix
libfreertos_a_CPPFLAGS  += -Iportable/ThirdParty/GCC/Posix/utils
libfreertos_a_SOURCES   += portable/ThirdParty/GCC/Posix/port.c
libfreertos_a_SOURCES   += portable/ThirdParty/GCC/Posix/utils/wait_for_event.c
noinst_HEADERS          += portable/ThirdParty/GCC/Posix/portmacro.h
noinst_HEADERS          += portable/ThirdParty/GCC/Posix/utils/wait_for_event.h
