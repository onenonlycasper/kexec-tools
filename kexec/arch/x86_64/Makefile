#
# kexec x86_64 (linux booting linux)
#
x86_64_KEXEC_SRCS =  kexec/arch/i386/kexec-elf-x86.c
x86_64_KEXEC_SRCS += kexec/arch/i386/kexec-bzImage.c
x86_64_KEXEC_SRCS += kexec/arch/i386/kexec-multiboot-x86.c
x86_64_KEXEC_SRCS += kexec/arch/i386/kexec-beoboot-x86.c
x86_64_KEXEC_SRCS += kexec/arch/i386/kexec-nbi.c
x86_64_KEXEC_SRCS += kexec/arch/i386/x86-linux-setup.c
x86_64_KEXEC_SRCS += kexec/arch/i386/kexec-x86-common.c
x86_64_KEXEC_SRCS += kexec/arch/x86_64/crashdump-x86_64.c
x86_64_KEXEC_SRCS += kexec/arch/x86_64/kexec-x86_64.c
x86_64_KEXEC_SRCS += kexec/arch/x86_64/kexec-elf-x86_64.c
x86_64_KEXEC_SRCS += kexec/arch/x86_64/kexec-elf-rel-x86_64.c

x86_64_ARCH_INIT = kexec/arch/x86_64/arch_init.c

dist += kexec/arch/x86_64/Makefile $(x86_64_KEXEC_SRCS) $(x86_64_ARCH_INIT) \
	kexec/arch/x86_64/kexec-x86_64.h kexec/arch/x86_64/crashdump-x86_64.h \
	kexec/arch/x86_64/include/arch/options.h
