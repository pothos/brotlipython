super slow pure python brotli decoder, please ignore

ported from brotli-rs to a minimal python subset and now back to standard python (but unpolished) as a side project

usage:

    from brotlipython import brotlidec
    in = open('test.br', 'rb').read()
    outbuf = []
    dec = brotlidec(in, outbuf)  # also returns bytes(outbuf) again

or see `./brotlipython.py --help`
