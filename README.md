# LuaWebTerminal
WebTerm+EMCC+Lua(5.4.7)

```
emcc lapi.c lcode.c lctype.c ldebug.c ldo.c ldump.c lfunc.c lgc.c llex.c lmem.c lobject.c lopcodes.c lparser.c lstate.c lstring.c ltable.c ltm.c lundump.c lvm.c lzio.c lauxlib.c lbaselib.c lcorolib.c ldblib.c liolib.c lmathlib.c loadlib.c loslib.c lstrlib.c ltablib.c lutf8lib.c linit.c -O2 -o build/lua.html -sNODEJS_CATCH_EXIT=0 -sNODEJS_CATCH_REJECTION=0 -sINITIAL_MEMORY=64MB -sALLOW_MEMORY_GROWTH=1 -sEXPORTED_FUNCTIONS="['_luaL_newstate','_luaL_openlibs','_luaL_loadstring','_lua_pcallk','_lua_close','_lua_tolstring','_lua_settop']" -sEXPORTED_RUNTIME_METHODS="['ccall','cwrap']" -sWASM=0 -sSINGLE_FILE --shell-file=webterm.html
```
