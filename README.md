

Find the real str0m [here][str0m]

[str0m]: https://github.com/algesten/str0m

*this is a tweaked version of str0m, specifically with six SRTP benchmarks*

This was on an intel 12400 CPU with 4400 MHz RAM.
(Crucial 16GB Ballistix MAX DDR4 44000 MHz UDIMM 288-pin)

When I run `cargom +nightly bench` I get:

```text
test rtp_::srtp::test::bench_aead_aes_128_gcm               ... bench:         143 ns/iter (+/- 1) = 3496 MB/s
test rtp_::srtp::test::bench_aes_128_cm_sha1_80             ... bench:          82 ns/iter (+/- 1) = 6097 MB/s
test rtp_::srtp::test::bench_openssl_ver_1_1_1w             - should panic ... bench:           0 ns/iter (+/- 0)
test rtp_::srtp::test::bench_protect_rtp2_aead_aes128_gcm   ... bench:         136 ns/iter (+/- 1) = 3676 MB/s
test rtp_::srtp::test::bench_protect_rtp2_aes128_cm_sha1_80 ... bench:         353 ns/iter (+/- 1) = 1416 MB/s
test rtp_::srtp::test::bench_protect_rtp_aead_aes128_gcm    ... bench:         155 ns/iter (+/- 2) = 3225 MB/s
test rtp_::srtp::test::bench_protect_rtp_aes128_cm_sha1_80  ... bench:         368 ns/iter (+/- 2) = 1358 MB/s
```


