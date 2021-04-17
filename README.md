afpacket
============

Rust bindings for Linux AF_PACKET (raw) sockets, including Async wrapper
for use with `async_std` or `futures`, based on `async_io`.

> Packet sockets are used to receive or send raw packets at the device
> driver (OSI Layer 2) level.  They allow the user to implement
> protocol modules in user space on top of the physical layer.
  -- [packet(7)](http://man7.org/linux/man-pages/man7/packet.7.html)

# License

```
Copyright © 2021 nyantec GmbH <oss@nyantec.com>

Authors:
  Milan Pässler <mil@nyantec.com>

Provided that these terms and disclaimer and all copyright notices
are retained or reproduced in an accompanying document, permission
is granted to deal in this work without restriction, including un‐
limited rights to use, publicly perform, distribute, sell, modify,
merge, give away, or sublicence.

This work is provided “AS IS” and WITHOUT WARRANTY of any kind, to
the utmost extent permitted by applicable law, neither express nor
implied; without malicious intent or gross negligence. In no event
may a licensor, author or contributor be held liable for indirect,
direct, other damage, loss, or other issues arising in any way out
of dealing in the work, even if advised of the possibility of such
damage or existence of a defect, except proven that it results out
of said person’s immediate fault when using the work as intended.
```

`src/sync.rs` is derived from the
[mio-afpacket](https://github.com/polachok/mio-afpacket) crate by
Alexander Polakov \<plhk@sdf.org>, licensed under the MIT license.
