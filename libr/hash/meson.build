
files=[
'adler32.c',
'calc.c',
'crca.c',
'entropy.c',
'hamdist.c',
'hash.c',
'luhn.c',
'md4.c',
'md5.c',
'sha1.c',
'sha2.c',
'state.c',
'xxhash.c'
]

r_hash = shared_library('r_hash', files,
  include_directories: include_directories(['../include']),
  dependencies: [mth],
  link_with: [r_util],
  install: true
)

