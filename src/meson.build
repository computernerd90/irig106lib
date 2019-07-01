project('irig106lib', 'c')

add_project_arguments('-D_LARGEFILE64_SOURCE', language: 'c')

static_library('irig106', 'i106_decode_1553f1.c', 'i106_decode_16pp194.c',
    'i106_decode_arinc429.c', 'i106_decode_can.c', 'i106_decode_discrete.c',
    'i106_decode_ethernet.c', 'i106_decode_index.c', 'i106_decode_pcmf1.c',
    'i106_decode_time.c', 'i106_decode_tmats.c', 'i106_decode_tmats_g.c',
    'i106_decode_tmats_p.c', 'i106_decode_tmats_r.c', 'i106_decode_uart.c',
    'i106_decode_video.c', 'i106_index.c', 'i106_time.c', 'irig106ch10.c', 'sha-256.c')

shared_library('irig106', 'i106_decode_1553f1.c', 'i106_decode_16pp194.c',
    'i106_decode_arinc429.c', 'i106_decode_can.c', 'i106_decode_discrete.c',
    'i106_decode_ethernet.c', 'i106_decode_index.c', 'i106_decode_pcmf1.c',
    'i106_decode_time.c', 'i106_decode_tmats.c', 'i106_decode_tmats_g.c',
    'i106_decode_tmats_p.c', 'i106_decode_tmats_r.c', 'i106_decode_uart.c',
    'i106_decode_video.c', 'i106_index.c', 'i106_time.c', 'irig106ch10.c', 'sha-256.c')
