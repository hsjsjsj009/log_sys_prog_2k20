# Week 01

Created: Sep 18, 2020 9:21 AM

# Course Plan

1. System Call

    Fungsi yang disediakan oleh kernel yang akan digunakan oleh aplikasi

2. Stat System Call
3. Processor
4. Memory
5. stdio
6. I/O Buffering
7. Shells
8. Signals
9. GNU (GNU Not Unix)
10. File Systems
11. Daemon & Sockets
12. Kernel Compilation
13. Boot Sequences
14. Kernel Module
15. Device Driver

- Driver merupakan pengendali hardware dan bisa diakses oleh kernel
- Aplikasi mengonsum layanan dari kernel untuk memanfaatkan hardware

## System Programming vs Application Programming

- Application Programming bertujuan untuk memproduksi sebuah software berdasarkan kebutuhan user
- System Programming bertujuan untuk memproduksi sebuah program yang digunakan untuk menjembatani aplikasi ke hardware, sehingga aplikasi dapat berjalan.

## Programming Language vs Scripting Language

- Scripting Language pakai interpreter, tidak perlu kompilasi, lebih banyak digunakan backend system.
- Programming Language perlu melakukan kompilasi, lebih banyak digunakan di user interface.

## Sistem Operasi

- Memanage semua hardware yang ada di sebuah komputer

## Kernel

- Merupakan inti dari sebuah sistem operasi
- Subbagian dari Sistem Operasi
- Task sebuah kernel
    - Manajemen memory
    - Penjadwalan proses
    - Sistem file
    - Mengakses hardware secara langsung
    - Mengatur jaringan komputer
    - System Call API

## Hierarchy Directory

1. /bin
2. /boot
3. /etc
4. /home
5. /usr

## Files di Linux

| Symbol | Definisi |
| ------ | -------- |
|d|directory|
|-|regular file|
|l|symbolic link|
|c|character drive|


### Relative path vs Absolute path

- Absolute path merupakan path yang dimulai dari root sebuah file sistem
- Relative path merupakan path yang bergantung pada posisi folder yang dibuka sekarang

## Shell

Jenis - jenis :

- Bourne Again shell
- Bourne shell
- C shell
- Korn shell
- Dan lain lain

Command interpreter di unix

## User, Group dan Permission

Untuk melihat user di /etc/passwd

Untuk melihat group /etc/groups

Permission lihat di ls -l