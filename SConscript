from building import *

cwd     = GetCurrentDir()
src     = Glob('*.c')
CPPPATH = [cwd]

group = DefineGroup('CherryRB', src, depend = [], CPPPATH = CPPPATH)

Return('group')
