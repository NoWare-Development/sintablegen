project(
  'sintablegen',
  'c',
  default_options: [
    'c_std=c89'
  ]
)

cc = meson.get_compiler('c')
m_dep = cc.find_library('m', required: false)

executable('sintablegen', 'src/main.c', dependencies: m_dep)
