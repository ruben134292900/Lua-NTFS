# ⚠ This library will be completely deprecated in the future, as im working on a better library which supports both win32 and unix systems. ⚠

# Lua NTFS

A little module for interacting with the windows file system or NTFS

Each file you open will create a File object which has alot of manipulation methods including:
- Renaming
- Read and Write
- Copying
- Moving
- Deleting
- Finding files under itself / Getting the parent of the file
- and more

# Dependencies
- [winapi](https://github.com/stevedonovan/winapi)
- [luaFileSystem](https://lunarmodules.github.io/luafilesystem/)


# Q&A
> Q: UNIX support in the future:
> 
> A: No, you can probably modify it to work for UNIX

> Q: Tested lua versions:
> 
> A: LuaJIT
