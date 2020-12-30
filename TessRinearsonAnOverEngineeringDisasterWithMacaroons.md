---
date: 2020-12-28T16:21
---

# Tess Rinearson An Over Engineering Disaster with Macaroons

Video:

- https://www.youtube.com/watch?v=5RSMQEdQmCE

## Notes

- Revocation is hard because it can't be done immediately (have to wait for
  issued capabilities to expire)
- Hard to develop locally as discharge macaroons have to be reissued frequently
- Caused uptime dependency issue with server that had to stay up to
  mint/attenuate/validate macaroons or something like that (ACL via macaroons?)
