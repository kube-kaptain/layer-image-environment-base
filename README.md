# Layer Image Environment Base

Kaptain config layer providing common docker build settings for all image-environment-base images.

Projects that reference this layer inherit:

- **Multi-arch docker builds** — linux/amd64 and linux/arm64
- **Dockerfile in src/docker** — single path for both architectures
- **File pattern match versioning** — version extracted from Dockerfile ENV via kubectl pattern
