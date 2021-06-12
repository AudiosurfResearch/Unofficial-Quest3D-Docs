# .cgr files

.cgr files are **Channel group files**.

## Information

They store channel graphs, images/textures, 3D models and audio and are vital for games to function. It's also possible to load a .cgr file from disk or download one from a server and load it at runtime. This is utilized by Audiosurf during loading and to download songs for Audiosurf Radio.

Optionally, .cgr files can be compressed (this feature uses the [LZMA compression algorithm](https://en.wikipedia.org/wiki/Lempel%E2%80%93Ziv%E2%80%93Markov_chain_algorithm)) and protected, preventing them from being opened in the Quest3D editor. However, this is easily bypassed by using [Quest3DTamperer](https://github.com/AudiosurfResearch/Quest3DTamperer).

As of now, the only tool that is able to extract files from a .cgr file is [Ravioli Game Tools](https://www.scampers.org/steve/sms/other.htm), but it only works with Audiosurf Radio songs.

## Format

**Not a lot is known about this so far, contributions are appreciated.**

Compressed .cgr files contain the string ``ACTF`` at the beginning of the file.