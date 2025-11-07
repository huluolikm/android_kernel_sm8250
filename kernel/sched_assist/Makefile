
ccflags-y += -I$(srctree)/include/linux/sched_assist
ccflags-y += -I$(srctree)/kernel/sched_assist
obj-y += sched_assist_common.o
obj-y += sched_assist_mutex.o
obj-y += sched_assist_rwsem.o
obj-y += sched_assist_futex.o
obj-y += sched_assist_workqueue.o

ifeq ($(VERSION).$(PATCHLEVEL), 5.4)
obj-y += sched_assist_slide.o
endif
