files=[
'lang.c',
'p/c.c',
# 'p/cpipe.c',
'p/lib.c',
'p/pipe.c',
'p/rust.c',
'p/vala.c'
]

r_lang = shared_library('r_lang', files,
  include_directories: include_directories(['../include']),
  c_args: ['-DCORELIB'],
  link_with: [r_util, r_cons],
  install: true
)
