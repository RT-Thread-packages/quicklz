from building import *

cwd = GetCurrentDir()
src = Glob('*.c')
CPPPATH = [cwd]

group = DefineGroup('quicklz', src, depend = ['PKG_USING_QUICKLZ'], CPPPATH = CPPPATH)

Return('group')
