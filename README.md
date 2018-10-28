# BCIPs [![Telegram](https://img.shields.io/discord/:serverId.svg)](https://t.me/BitcoinCash123)
The Bitcoin Cash Improvement Proposals (BCIPs) describe standards for the Bitcoin cash platform, including new protocol specifications, client APIs, and smart contract standards.

A browsable version of all current and draft BCIPs can be found here.

# Contributing

 1. Review [BCIP-1](BCIPs/BCIP-1.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your BCIP to your fork of the repository. There is a [template BCIP here](BCIP-X.md).
 4. Submit a Pull Request to Bitcoin Cash Repository [BCIPs repository](https://github.com/sriharikapu/BCIPs).

Your first PR should be a first draft of the final BCIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new BCIP and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the BCIP as a whole.

If your BCIP requires images, the image files should be included in a subdirectory of the `assets` folder for that BCIP as follow: `assets/BCIP-X` (for BCIP **X**). When linking to an image in the BCIP, use relative links such as `../assets/BCIP-X/image.png`.

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft BCIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your BCIP contains either your Github username or your email address inside <triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

When you believe your BCIP is mature and ready to progress past the draft phase, you should do one of two things:


# BCIP status terms
* **Draft** - an BCIP that is open for consideration
* **Accepted** - an BCIP that is planned for immediate adoption, i.e. expected to be included in the next hard fork (for Core/Consensus layer BCIPs).
* **Final** - an BCIP that has been adopted in a previous hard fork (for Core/Consensus layer BCIPs).
* **Deferred** - an BCIP that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.


