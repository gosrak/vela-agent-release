# vela-agent-release (private)

Release binaries of vela-agent (fork of supr-meow-vela v0.1.4, MIT — see LICENSE inside each package).
Packages bundle NVIDIA CUDA runtime redistributables (libcudart, libcublasLt; NVIDIA CUDA EULA Attachment A) and, for the compact build, CUTLASS (BSD-3).
Rental boxes download assets with a read-only fine-grained token (bootstrap: VELA_GH_TOKEN). Fallback: our web server.
