# Summary

* [Introduction](README.md)
	* [lab1](lab/lab1/README.md)
		* [boot](lab/lab1/boot/README.md)
			* [bootasm](lab/lab1/boot/bootasm.md)
			* [bootmain](lab/lab1/boot/bootmain.md)
		* [kern](lab/lab1/kern/README.md)
			* [debug](lab/lab1/kern/debug/README.md)
				* [kmonitor](lab/lab1/kern/debug/kmonitor.md)
				* [panic](lab/lab1/kern/debug/panic.md)
			* [init](lab/lab1/kern/init/README.md)
				* [init](lab/lab1/kern/init/init.md)
			* [libs](lab/lab1/kern/libs/README.md)
				* [readline](lab/lab1/kern/libs/readline.md)
			* [mm](lab/lab1/kern/mm/README.md)
				* [pmm](lab/lab1/kern/mm/pmm.md)
			* [trap](lab/lab1/kern/trap/README.md)
				* [trap](lab/lab1/kern/trap/trap.md)
				* [trapentry](lab/lab1/kern/trap/trapentry.md)
				* [vectors](lab/lab1/kern/trap/vectors.md)
		* [libs](lab/lab1/libs/README.md)
		* [tools](lab/lab1/tools/README.md)
* [lab解析](labs/README.md)
	* [lab1](labs/lab1/README.md)
	    * [练习1](labs/lab1/practice1.md)
	    * [练习3](labs/lab1/practice3.md)
	* [lab2](labs/lab2/README.md)
	* [lab3](labs/lab3/README.md)
	* [lab4](labs/lab4/README.md)
	* [lab5](labs/lab5/README.md)
	* [lab6](labs/lab6/README.md)
	* [lab7](labs/lab7/README.md)
	* [lab8](labs/lab8/README.md)
* [uCore代码](ucore/README.md)
	* [boot](ucore/boot/README.md)
		* [asm.h](ucore/boot/asm_h.md)
		* [bootasm.S](ucore/boot/bootasm_S.md)
		* [bootmain.c](ucore/boot/bootmain_c.md)
		* [(lab1) bootasm.S](ucore/boot/bootasm_S_lab1.md)
	* [kern](ucore/kern/README.md)
		* [debug](ucore/kern/debug/README.md)
			* [assert.h](ucore/kern/debug/assert_h.md)
			* [kdebug.c](ucore/kern/debug/kdebug_c.md)
			* [kdebug.h](ucore/kern/debug/kdebug_h.md)
			* [kmonitor.c](ucore/kern/debug/kmonitor_c.md)
			* [kmonitor.h](ucore/kern/debug/kmonitor_h.md)
			* [panic.c](ucore/kern/debug/panic_c.md)
			* [stab.h](ucore/kern/debug/stab_h.md)
			* [(lab1) kdebug.c](ucore/kern/debug/kdebug_c_lab1.md)
		* [driver](ucore/kern/driver/README.md)
			* [clock.c](ucore/kern/driver/clock_c.md)
			* [clock.h](ucore/kern/driver/clock_h.md)
			* [console.c](ucore/kern/driver/console_c.md)
			* [console.h](ucore/kern/driver/console_h.md)
			* [ide.c](ucore/kern/driver/ide_c.md)
			* [ide.h](ucore/kern/driver/ide_h.md)
			* [intr.c](ucore/kern/driver/intr_c.md)
			* [intr.h](ucore/kern/driver/intr_h.md)
			* [kbdreg.h](ucore/kern/driver/kbdreg_h.md)
			* [picirq.c](ucore/kern/driver/picirq_c.md)
			* [picirq.h](ucore/kern/driver/picirq_h.md)
		* [fs](ucore/kern/fs/README.md)
			* [devs](ucore/kern/fs/devs/README.md)
				* [dev.c](ucore/kern/fs/devs/dev_c.md)
				* [dev_disk0.c](ucore/kern/fs/devs/dev_disk0_c.md)
				* [dev.h](ucore/kern/fs/devs/dev_h.md)
				* [dev_stdin.c](ucore/kern/fs/devs/dev_stdin_c.md)
				* [dev_stdout.c](ucore/kern/fs/devs/dev_stdout_c.md)
			* [sfs](ucore/kern/fs/sfs/README.md)
				* [bitmap.c](ucore/kern/fs/sfs/bitmap_c.md)
				* [bitmap.h](ucore/kern/fs/sfs/bitmap_h.md)
				* [sfs.c](ucore/kern/fs/sfs/sfs_c.md)
				* [sfs_fs.c](ucore/kern/fs/sfs/sfs_fs_c.md)
				* [sfs.h](ucore/kern/fs/sfs/sfs_h.md)
				* [sfs_inode.c](ucore/kern/fs/sfs/sfs_inode_c.md)
				* [sfs_io.c](ucore/kern/fs/sfs/sfs_io_c.md)
				* [sfs_lock.c](ucore/kern/fs/sfs/sfs_lock_c.md)
			* [swap](ucore/kern/fs/swap/README.md)
				* [swapfs.c](ucore/kern/fs/swap/swapfs_c.md)
				* [swapfs.h](ucore/kern/fs/swap/swapfs_h.md)
			* [vfs](ucore/kern/fs/vfs/README.md)
				* [inode.c](ucore/kern/fs/vfs/inode_c.md)
				* [inode.h](ucore/kern/fs/vfs/inode_h.md)
				* [README.md](ucore/kern/fs/vfs/README_md.md)
				* [vfs.c](ucore/kern/fs/vfs/vfs_c.md)
				* [vfsdev.c](ucore/kern/fs/vfs/vfsdev_c.md)
				* [vfsfile.c](ucore/kern/fs/vfs/vfsfile_c.md)
				* [vfs.h](ucore/kern/fs/vfs/vfs_h.md)
				* [vfslookup.c](ucore/kern/fs/vfs/vfslookup_c.md)
				* [vfspath.c](ucore/kern/fs/vfs/vfspath_c.md)
			* [file.c](ucore/kern/fs/file_c.md)
			* [file.h](ucore/kern/fs/file_h.md)
			* [fs.c](ucore/kern/fs/fs_c.md)
			* [fs.h](ucore/kern/fs/fs_h.md)
			* [iobuf.c](ucore/kern/fs/iobuf_c.md)
			* [iobuf.h](ucore/kern/fs/iobuf_h.md)
			* [sysfile.c](ucore/kern/fs/sysfile_c.md)
			* [sysfile.h](ucore/kern/fs/sysfile_h.md)
		* [init](ucore/kern/init/README.md)
			* [entry.S](ucore/kern/init/entry_S.md)
			* [init.c](ucore/kern/init/init_c.md)
			* [(lab1) init.c](ucore/kern/init/init_c_lab1.md)
		* [libs](ucore/kern/libs/README.md)
			* [readline.c](ucore/kern/libs/readline_c.md)
			* [stdio.c](ucore/kern/libs/stdio_c.md)
			* [string.c](ucore/kern/libs/string_c.md)
		* [mm](ucore/kern/mm/README.md)
			* [default_pmm.c](ucore/kern/mm/default_pmm_c.md)
			* [default_pmm.h](ucore/kern/mm/default_pmm_h.md)
			* [kmalloc.c](ucore/kern/mm/kmalloc_c.md)
			* [kmalloc.h](ucore/kern/mm/kmalloc_h.md)
			* [memlayout.h](ucore/kern/mm/memlayout_h.md)
			* [mmu.h](ucore/kern/mm/mmu_h.md)
			* [pmm.c](ucore/kern/mm/pmm_c.md)
			* [pmm.h](ucore/kern/mm/pmm_h.md)
			* [swap.c](ucore/kern/mm/swap_c.md)
			* [swap_fifo.c](ucore/kern/mm/swap_fifo_c.md)
			* [swap_fifo.h](ucore/kern/mm/swap_fifo_h.md)
			* [swap.h](ucore/kern/mm/swap_h.md)
			* [vmm.c](ucore/kern/mm/vmm_c.md)
			* [vmm.h](ucore/kern/mm/vmm_h.md)
			* [(lab2) pmm.c](ucore/kern/mm/pmm_c_lab2.md)
			* [(lab3) vmm.c](ucore/kern/mm/vmm_c_lab3.md)
		* [process](ucore/kern/process/README.md)
			* [entry.S](ucore/kern/process/entry_S.md)
			* [proc.c](ucore/kern/process/proc_c.md)
			* [proc.h](ucore/kern/process/proc_h.md)
			* [switch.S](ucore/kern/process/switch_S.md)
			* [(lab4) proc.c](ucore/kern/process/proc_c_lab4.md)
			* [(lab5) proc.c](ucore/kern/process/proc_c_lab5.md)
		* [schedule](ucore/kern/schedule/README.md)
			* [default_sched.c](ucore/kern/schedule/default_sched_c.md)
			* [default_sched.h](ucore/kern/schedule/default_sched_h.md)
			* [default_sched_stride.c](ucore/kern/schedule/default_sched_stride_c.md)
			* [sched.c](ucore/kern/schedule/sched_c.md)
			* [sched.h](ucore/kern/schedule/sched_h.md)
		* [sync](ucore/kern/sync/README.md)
			* [check_sync.c](ucore/kern/sync/check_sync_c.md)
			* [monitor.c](ucore/kern/sync/monitor_c.md)
			* [monitor.h](ucore/kern/sync/monitor_h.md)
			* [sem.c](ucore/kern/sync/sem_c.md)
			* [sem.h](ucore/kern/sync/sem_h.md)
			* [sync.h](ucore/kern/sync/sync_h.md)
			* [wait.c](ucore/kern/sync/wait_c.md)
			* [wait.h](ucore/kern/sync/wait_h.md)
		* [syscall](ucore/kern/syscall/README.md)
			* [syscall.c](ucore/kern/syscall/syscall_c.md)
			* [syscall.h](ucore/kern/syscall/syscall_h.md)
		* [trap](ucore/kern/trap/README.md)
			* [trap.c](ucore/kern/trap/trap_c.md)
			* [trapentry.S](ucore/kern/trap/trapentry_S.md)
			* [trap.h](ucore/kern/trap/trap_h.md)
			* [vectors.S](ucore/kern/trap/vectors_S.md)
			* [(lab1) trap.c](ucore/kern/trap/trap_c_lab1.md)
	* [libs](ucore/libs/README.md)
		* [atomic.h](ucore/libs/atomic_h.md)
		* [defs.h](ucore/libs/defs_h.md)
		* [dirent.h](ucore/libs/dirent_h.md)
		* [elf.h](ucore/libs/elf_h.md)
		* [error.h](ucore/libs/error_h.md)
		* [hash.c](ucore/libs/hash_c.md)
		* [list.h](ucore/libs/list_h.md)
		* [printfmt.c](ucore/libs/printfmt_c.md)
		* [rand.c](ucore/libs/rand_c.md)
		* [skew_heap.h](ucore/libs/skew_heap_h.md)
		* [stat.h](ucore/libs/stat_h.md)
		* [stdarg.h](ucore/libs/stdarg_h.md)
		* [stdio.h](ucore/libs/stdio_h.md)
		* [stdlib.h](ucore/libs/stdlib_h.md)
		* [string.c](ucore/libs/string_c.md)
		* [string.h](ucore/libs/string_h.md)
		* [unistd.h](ucore/libs/unistd_h.md)
		* [x86.h](ucore/libs/x86_h.md)
	* [tools](ucore/tools/README.md)
		* [boot.ld](ucore/tools/boot_ld.md)
		* [function.mk](ucore/tools/function_mk.md)
		* [gdbinit](ucore/tools/gdbinit.md)
		* [grade.sh](ucore/tools/grade_sh.md)
		* [kernel.ld](ucore/tools/kernel_ld.md)
		* [mksfs.c](ucore/tools/mksfs_c.md)
		* [sign.c](ucore/tools/sign_c.md)
		* [user.ld](ucore/tools/user_ld.md)
		* [vector.c](ucore/tools/vector_c.md)
	* [user](ucore/user/README.md)
		* [libs](ucore/user/libs/README.md)
			* [dir.c](ucore/user/libs/dir_c.md)
			* [dir.h](ucore/user/libs/dir_h.md)
			* [file.c](ucore/user/libs/file_c.md)
			* [file.h](ucore/user/libs/file_h.md)
			* [initcode.S](ucore/user/libs/initcode_S.md)
			* [lock.h](ucore/user/libs/lock_h.md)
			* [panic.c](ucore/user/libs/panic_c.md)
			* [stdio.c](ucore/user/libs/stdio_c.md)
			* [syscall.c](ucore/user/libs/syscall_c.md)
			* [syscall.h](ucore/user/libs/syscall_h.md)
			* [ulib.c](ucore/user/libs/ulib_c.md)
			* [ulib.h](ucore/user/libs/ulib_h.md)
			* [umain.c](ucore/user/libs/umain_c.md)
		* [badarg.c](ucore/user/badarg_c.md)
		* [badsegment.c](ucore/user/badsegment_c.md)
		* [divzero.c](ucore/user/divzero_c.md)
		* [exit.c](ucore/user/exit_c.md)
		* [faultread.c](ucore/user/faultread_c.md)
		* [faultreadkernel.c](ucore/user/faultreadkernel_c.md)
		* [forktest.c](ucore/user/forktest_c.md)
		* [forktree.c](ucore/user/forktree_c.md)
		* [hello.c](ucore/user/hello_c.md)
		* [ls.c](ucore/user/ls_c.md)
		* [matrix.c](ucore/user/matrix_c.md)
		* [pgdir.c](ucore/user/pgdir_c.md)
		* [priority.c](ucore/user/priority_c.md)
		* [sfs_filetest1.c](ucore/user/sfs_filetest1_c.md)
		* [sh.c](ucore/user/sh_c.md)
		* [sleep.c](ucore/user/sleep_c.md)
		* [sleepkill.c](ucore/user/sleepkill_c.md)
		* [softint.c](ucore/user/softint_c.md)
		* [spin.c](ucore/user/spin_c.md)
		* [testbss.c](ucore/user/testbss_c.md)
		* [waitkill.c](ucore/user/waitkill_c.md)
		* [yield.c](ucore/user/yield_c.md)
	* [Makefile](ucore/Makefile.md)
	* [(lab1) Makefile](ucore/Makefile_lab1.md)
* [附录：工具使用](tools/README.md)
	* [如何编辑该文档](tools/how_to_edit_this_doc.md)
	* [讨论区的维护方法](tools/how_to_update_gitbook_doc.md)

