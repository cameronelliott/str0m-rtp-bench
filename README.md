

Find the real str0m [here][str0m]

[str0m]: https://github.com/algesten/str0m

*this is a tweaked version of str0m, specifically with six SRTP benchmarks*

When I run `cargom +nightly bench` I get:

```text
test rtp_::srtp::test::bench_aead_aes_128_gcm               ... bench:         213 ns/iter (+/- 1) = 2347 MB/s
test rtp_::srtp::test::bench_aes_128_cm_sha1_80             ... bench:          83 ns/iter (+/- 0) = 6024 MB/s
test rtp_::srtp::test::bench_protect_rtp2_aead_aes128_gcm   ... bench:         224 ns/iter (+/- 2) = 2232 MB/s
test rtp_::srtp::test::bench_protect_rtp2_aes128_cm_sha1_80 ... bench:         355 ns/iter (+/- 1) = 1408 MB/s
test rtp_::srtp::test::bench_protect_rtp_aead_aes128_gcm    ... bench:         275 ns/iter (+/- 2) = 1818 MB/s
test rtp_::srtp::test::bench_protect_rtp_aes128_cm_sha1_80  ... bench:         384 ns/iter (+/- 3) = 1302 MB/s
```


