# Exploring OpenSSH: Hands-On Workshop for Beginners - Unlock Your Brain, Harden Your System 2024

The [presentation](https://github.com/wllm-rbnt/uybhys-2024-openssh-workshop/blob/main/uybhys-2024-openssh-workshop.patat.md) is written in Markdown.

Use [patat](https://github.com/jaspervdj/patat) to render the slides in your terminal or use the [PDF](https://github.com/wllm-rbnt/uybhys-2024-openssh-workshop/blob/main/uybhys-2024-openssh-workshop.pdf)/[HTML](https://github.com/wllm-rbnt/uybhys-2024-openssh-workshop/blob/main/document_name.html) versions.

    $ wget https://github.com/jaspervdj/patat/releases/download/v0.12.0.1/patat-v0.12.0.1-linux-x86_64.tar.gz
    $ tar xzf patat-v0.12.0.1-linux-x86_64.tar.gz patat-v0.12.0.1-linux-x86_64/patat
    $ patat-v0.12.0.1-linux-x86_64/patat uybhys-2024-openssh-workshop.patat.md

Use the [ws_gen](https://github.com/wllm-rbnt/uybhys-2024-openssh-workshop/blob/main/ws_gen) script to generate PDF/HTML versions from Markdown (this script requires [Pandoc](https://pandoc.org/) and [Chromium](https://www.chromium.org/Home/)):

    $ sudo apt install pandoc chromium
    $ ./ws_gen

or

    $ sudo dnf install pandoc chromium
    $ ./ws_gen

Note: this script will also create the final Markdown version along with the
README.md file of the repository.
