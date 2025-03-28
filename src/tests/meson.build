test_files = [
    'flap_test_action_store.f90',
    'flap_test_ansi_color_style.f90',
    'flap_test_basic.f90',
    'flap_test_choices_logical.f90',
    'flap_test_duplicated_clas.f90',
    'flap_test_group.f90',
    'flap_test_group_examples.f90',
    'flap_test_hidden.f90',
    'flap_test_ignore_unknown_clas.f90',
    'flap_test_minimal.f90',
    'flap_test_nargs_insufficient.f90',
    'flap_test_nested.f90',
    'flap_test_save_bash_completion.f90',
    'flap_test_save_man_page.f90',
    'flap_test_save_usage_to_markdown.f90',
    'flap_test_string.f90',
    'flap_test_value_missing.f90',
]

foreach file : test_files
    exe_name = file.split('.')[0]
    exe = executable(exe_name, file, dependencies: flap_dep)
    test(exe_name, exe)
endforeach