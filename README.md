# Mr.dzakyhack
helloword
...

[ 28%] Building C object Source/kwsys/CMakeFiles/cmsysTestSharedForward.dir/testSharedForward.c.o
[ 28%] Building C object Source/kwsys/CMakeFiles/cmsysTestsC.dir/testEncode.c.o
[ 28%] Building C object Source/kwsys/CMakeFiles/cmsysTestsC.dir/cmsysTestsC.c.o
[ 29%] Building C object Utilities/cmlibarchive/libarchive/CMakeFiles/cmlibarchive.dir/archive_acl.c.o
[ 29%] Building C object Utilities/cmlibarchive/libarchive/CMakeFiles/cmlibarchive.dir/archive_check_magic.c.o
In file included from /mnt/cmlfs/sources/pkgs/cmake-3.20.5/Utilities/cmlibarchive/libarchive/archive_acl.c:37:
/usr/include/wchar.h:600:9: error: unknown type name '__gnuc_va_list'
                      __gnuc_va_list __arg)
                      ^
/usr/include/wchar.h:607:8: error: unknown type name '__gnuc_va_list'
                     __gnuc_va_list __arg)
                     ^
/usr/include/wchar.h:613:9: error: unknown type name '__gnuc_va_list'
                      __gnuc_va_list __arg)
                      ^
/usr/include/wchar.h:675:8: error: unknown type name '__gnuc_va_list'
                     __gnuc_va_list __arg)
                     ^
/usr/include/wchar.h:682:7: error: unknown type name '__gnuc_va_list'
                    __gnuc_va_list __arg)
                    ^
/usr/include/wchar.h:687:8: error: unknown type name '__gnuc_va_list'
                     __gnuc_va_list __arg)
                     ^
/usr/include/wchar.h:698:7: error: unknown type name '__gnuc_va_list'
                                  __gnuc_va_list __arg), __isoc99_vfwscanf)
                                  ^
/usr/include/wchar.h:701:6: error: unknown type name '__gnuc_va_list'
                                 __gnuc_va_list __arg), __isoc99_vwscanf)
                                 ^
/usr/include/wchar.h:705:11: error: unknown type name '__gnuc_va_list'
                                      __gnuc_va_list __arg), __isoc99_vswscanf)
                                      ^

... so many errors here ...
I don't know how to override headers PATH to /llvmtools/include, when I try to configure with CFLAGS="-I/llvmtools/include" CXXFLAGS="-I/llvmtools/include" ./bootstrap still fails to build.
