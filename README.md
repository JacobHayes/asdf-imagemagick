# asdf-imagemagick
![GITHUB ACTIONS BADGE](https://github.com/mangalakader/asdf-imagemagick/workflows/Imagemagick%20Plugin%20Test/badge.svg)

ImageMagick plugin for asdf/mise version manager. Supports Linux and macOS.

## Prerequisites

- **Linux**: Standard build tools (gcc, make, etc.)
- **macOS**: Xcode Command Line Tools (`xcode-select --install`)

Optional dependencies (libjpeg, libpng, etc.) can be installed via your system's package manager for additional ImageMagick features.

### Passing Extra Arguments for configure:

Export the environment variable IMAGEMAGICK_EXTRA={OPTIONS}.

### Defaults:

The plugin installation defaults to asdf install directory, which might look like
/home/user/.asdf/install/imagemagick/{version}

If something is wrong, please look for logs in the asdf install dir named
config.log, make.log, make_install.log


