# prefix
include $(PRO_DIR)/prefix.mak

# module name
NAMES 					= xmake

# module type
xmake_TYPE 				= LIB

# config
xmake_CONFIG 			= y

# core files
xmake_C_FILES 			+= \
						xmake \
						machine \
						os/find \
						os/uuid \
						os/isdir \
						os/rmdir \
						os/mkdir \
						os/cpdir \
						os/chdir \
						os/mtime \
						os/mclock \
						os/curdir \
						os/tmpdir \
						os/isfile \
						os/rmfile \
						os/cpfile \
						os/rename \
						os/exists \
						os/setenv \
						os/getenv \
						os/emptydir \
						os/strerror \
						path/relative \
						path/absolute \
						path/translate \
						path/is_absolute \
						string/strcmp \
						string/endswith \
						string/startswith \
						process/open \
						process/openv \
						process/wait \
						process/waitlist \
						process/close 
						

# flags
xmake_CXFLAGS 			+= -D__tb_prefix__=\"xmake\"

# header files
xmake_INC_FILES 		= \
						xmake.h \
						machine.h \
						config.h \
						prefix.h \
						prefix/prefix.h \
						prefix/config.h \
						prefix/version.h 
						
# suffix
include $(PRO_DIR)/suffix.mak

