When writing documentation, attempt to infer the tone of voice from the repository, or other relevant sources if available.

Do not use en/em-dashes, instead punctuate properly. Also avoid colons and semicolons in prose, like code comments or readmes, when not necessary.
Also, when splitting prose along multiple lines (e.g. comments/markdown), prefer to split at punctuation, not mid-sentence (don't be strict about this, though).

Example of BAD prose:
> Decodes a source object and commits the result: its files and blobs first,
> then the manifest — which is what makes them visible to consumers: for example A,
> B and C.

Example of GOOD prose:
> Decodes a source object and commits the result.
> Files and blobs are decoded first, then the manifest.
> The manifest makes the result visible to consumers (e.g. A, B and C).

