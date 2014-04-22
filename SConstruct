# vim: set ft=python:

build_dir = 'build'
src_dir   = 'src'

env = Environment()
Export('env')

VariantDir(build_dir, src_dir, duplicate=1)
SConscript(build_dir + '/SConscript')
