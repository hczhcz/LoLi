CC = g++
CLANG = clang++
CFLAGSG = -std=c++11 
CFLAGSC = -std=c++11

GC = -L/home/zshang/Program/LoLi/git/src/gc/build -lgc
GCINCLUDE = -I/home/zshang/Program/LoLi/git/src/gc/include

HEADERS = loli_types.h loli_symbols.h loli_cons.h loli_prim.h loli_list.h loli_ast.h loli_gc.h
MAIN = loli_types.cpp loli_symbols.cpp loli_cons.cpp loli_prim.cpp loli_list.cpp loli_ast.cpp loli_main.cpp

currentg: $(HEADERS) $(GCHEADER)
	$(CC) $(CFLAGSG) $(GCINCLUDE) $(GC) -o currentg $(MAIN)

currentc: $(HEADERS)
	$(CLANG) $(CFLAGSC) $(GCINCLUDE) $(GC) -o currentc $(MAIN)
