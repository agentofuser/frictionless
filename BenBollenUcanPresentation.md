---
date: 2020-12-29T18:06
---

# UCAN (do) secure key management in the browser, with Ben Bollen

Video:

- https://www.youtube.com/watch?v=rQgecoUvmjU

## Notes

- High-level idea I got (?) is that UCANs help bridge [[OCAP]] world from
  browsers (permission bearer tokens) to [[ACL]] world of blockchains (identity
  keypairs)
- 2-of-2 BLS public key and signature combination magic stuff seems really cool
  - from what I understand this means you can have something that behaves like
    a single keypair without there being a private key that can be stolen
- Slides mention 2FA not really being an option somehow, but there has to be a
  "cosigner", so not sure who the second entity in the "2-of-2" thing is. I
  thought the cosigner a linked device I owned, but apparently it's a server
  somewhere? Whose?
  - Ok it seems like the cosigner would be a Fission server itself as a trusted
    party so that this could work purely on the web without any plugins or
    extensions or native apps required, but then the user could "upgrade" to a
    less-trust-needed scenario by replacing Fission's cosigner with something
    like Metamask or WalletConnect. A kind of progressive decentralization.
- First time I hear the term "trust marketplace" which sounds like an
  interesting concept. So I could shop around for a cosigner via some kind of
  market mechanism that establishes its trustworthiness I guess.
- Very condensed stuff, will have to look more careful into whitepaper and
  specs

## Navigation

- #ucan
