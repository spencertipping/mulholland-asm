# Mulholland assembler

This project implements a low-level assembler in Mulholland. It isn't nearly as nice as something you'd get from the GNU toolchain; in particular, it requires you to know some machine language
in order to get stuff done and generates no debugging symbols. The advantage of this assembler is that its abstraction syntax is extremely lightweight, and you get a full node.js runtime
environment to write macros.

MIT license as usual.