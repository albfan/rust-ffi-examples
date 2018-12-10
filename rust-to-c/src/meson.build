add_project_arguments(['--vapidir', join_paths(meson.source_root(), 'vapi')], language: 'vala')

double_lib = static_library('double', 'double.c')

executable('double', 'main.vala', link_with: double_lib, dependencies: dependency('glib-2.0'))
