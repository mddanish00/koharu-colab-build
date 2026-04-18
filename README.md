# koharu-colab-build

> ARCHIVED: No matter how I build this, I cannot seem to find way to make it work on Colab. Recompiling llama.cpp and replacing the downloaded runtime do not help either because well, the program automatically replace it with actual version anyway so, I give up. Hoping for Koharu project itself to support Google Colab in the future.

Builds the [Koharu](https://github.com/mayocream/koharu) app for usage in Google Colab. This is because right now at the time of writing, Colab still using Ubuntu 22.04 and not Ubuntu 24.04. As a result, the official Koharu release binary cannot be run on Colab.

> NOTE: Only temporary solution until the day Google Colab upgrades to Ubuntu 24.04. I will archive this repo as soon as possible when the day comes.

This repo licensed under [GPL-3.0 license](./LICENSE) same as the original [Koharu](https://github.com/mayocream/koharu/blob/main/LICENSE) app because [the build workflow](./.github/workflows/build.yml) just copied from the original repo with modifications for Colab's environment.