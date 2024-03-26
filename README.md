## estonia-eid-integration-sample

This is a sample project to integrate Estonia eID to a webpage.
This project is the only thing recovered from the time I was working on it, so it's not so straight forward to start this project. I will update it in the future to make starting this project straight forward \*finger-crossed

### Signature produced
- length: 96 bytes
- algorithm: ECDSA
- varification process -> decodeNIST384S(signature) -> ecda.verify(payload, r, s)
- decodeNIST384S: first 48 bytes (s), last 48 bytes (r)
