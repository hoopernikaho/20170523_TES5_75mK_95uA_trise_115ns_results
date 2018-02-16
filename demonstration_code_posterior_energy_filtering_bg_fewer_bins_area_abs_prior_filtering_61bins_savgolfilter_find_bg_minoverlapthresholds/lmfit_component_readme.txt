[[Model]]
    (Model(one_pulse, prefix='one_') + Model(one_pulse, prefix='two_'))
[[Variables]]
    one_x_offset:      3.0703e-06 (init= 3.035253e-06)
    two_x_offset:      3.2987e-06 (init= 3.731253e-06)
    sum_amplitudes:    2.17463166 (init= 1.96965)
    diff_amplitudes:  -0.24640966 (init= 0)
    one_amplitude:     0.96411099  == '(sum_amplitudes + diff_amplitudes)/2'
    two_amplitude:     1.21052066  == '(sum_amplitudes - diff_amplitudes)/2'
