# Memory-Management

尽管“可见度”不高，brk()也许是最常使用的系统调用了，用户进程通过它向内核申请空间。人们常常并不意识到调用brk(),原因在于很少人会直接使用系统调用
