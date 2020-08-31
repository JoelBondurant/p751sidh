我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# `p751sidh`

The `p751sidh` package provides a Go implementation of  (ephemeral)
supersingular isogeny Diffie-Hellman, as described in [Costello-Longa-Naehrig 2016](https://eprint.iacr.org/2016/413).
Internal functions useful for the implementation are published
in the p751toolbox package.

The implementation is intended for use on the `amd64` architecture only -- no
generic field arithmetic implementation is provided.  Portions of the field
arithmetic were ported from the Microsoft Research implementation.

This package follows their naming convention, writing "Alice" for the party
using 2^e-isogenies and "Bob" for the party using 3^e-isogenies.

This package does NOT implement SIDH key validation, so it should only be
used for ephemeral DH.  Each keypair should be used at most once.

If you feel that SIDH may be appropriate for you, consult your
cryptographer.

Special thanks to [Craig Costello](http://www.craigcostello.com.au/), [Diego Aranha](https://sites.google.com/site/dfaranha/), and [Deirdre Connolly](https://twitter.com/durumcrustulum) for advice
and discussion.

