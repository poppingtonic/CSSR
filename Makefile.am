# Ask for all the warnings ... except those that occur.
AM_CXXFLAGS = -Wall -Wextra -Wno-unused-variable			\
 -Wno-unused-but-set-variable -Wno-unused-parameter -Wno-sign-compare

CSSR_SOURCES = Main.cpp Hash.cpp States.cpp AllStates.cpp		\
 ParseTree.cpp G_Array.cpp Hash2.cpp Machine.cpp TransTable.cpp		\
 Test.cpp AllStates.h Common.h G_Array.h Hash2.h Hash.h Machine.h	\
 Main.h ParseTree.h States.h Test.h TransTable.h

bin_PROGRAMS = CSSR

dist_doc_DATA = ReadMe.txt ReadMe.pdf ReadMe.ps.gz ReadMe.html

EXTRA_DIST = binary01-alphabet COPYING_WARRANTY
