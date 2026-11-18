# ltx25-engine

Build workspace for the LTX-2.5 DiT engine (`libdit_engine.so`) that Nightmare's app downloads. Nothing upstream is vendored: `local-dream` and its pinned `stable-diffusion.cpp` are cloned at build time, and every change of ours travels as a patch under `patches/`.

Output: a release asset `dit-engine-abi<N>.zip` (contains `libdit_engine.so`), downloadable without a login.
