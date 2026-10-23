# ruminote-packages

On-device code runtimes used by [Ruminote](https://ruminote.org) code cards.

Ruminote runs code entirely on the device, inside Android WebView (WebAssembly / JavaScript). Runtimes
that are not published as ready-made packages elsewhere are built from source and published here as
release assets; the app's build pulls them by tag and verifies their sha256 before packaging them into
Google Play asset packs.

Each release archive contains a `SOURCES.txt` with the exact upstream sources, revisions, build
command and licenses of the files it contains.

| Release tag | Contents | Upstream licenses |
|---|---|---|
| `rt-java-teavm-javac-208d4c9` | teavm-javac (OpenJDK javac + TeaVM, WasmGC) | Apache-2.0; javac GPLv2 with Classpath Exception |
