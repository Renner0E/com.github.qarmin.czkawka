## Building from Source
1. Install [`org.flatpak.Builder`](https://github.com/flathub/org.flatpak.Builder) from Flathub
2. Clone `https://github.com/flathub/com.github.qarmin.czkawka` (or your fork)
3. Run `flatpak run org.flatpak.Builder --install --install-deps-from=flathub --default-branch=master --force-clean build com.github.qarmin.czkawka.yaml`
 in the terminal (use `--user` if necessary)
4. Run `flatpak run com.github.qarmin.czkawka//master` to launch it.
