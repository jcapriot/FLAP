flap_srcs = files(
    'flap.f90',
    'flap_command_line_argument_t.F90',
    'flap_command_line_arguments_group_t.f90',
    'flap_command_line_interface_t.F90',
    'flap_object_t.F90',
    'flap_utils_m.f90',
)

flap_lib = library(
    'flap',
    flap_srcs,
    dependencies: [face_dep, penf_dep]
)

flap_dep = declare_dependency(
    link_with: flap_lib,
    dependencies: [face_dep, penf_dep],
)