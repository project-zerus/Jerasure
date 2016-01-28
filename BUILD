licenses(['notice'])

cc_library(
  name = 'jerasure',
  visibility = ['//visibility:public'],
  includes = [
    'include',
  ],
  hdrs = [
    'include/cauchy.h',
    'include/config.h',
    'include/galois.h',
    'include/jerasure.h',
    'include/liberation.h',
    'include/reed_sol.h',
  ],
  srcs = [
    'src/cauchy.c',
    'src/galois.c',
    'src/jerasure.c',
    'src/liberation.c',
    'src/reed_sol.c'
  ],
  deps = [
    '//gf-complete:gf-complete'
  ]
)
