# Installing JetBrains Mono Patched Font on Kali Linux

Follow these steps to install the JetBrains Mono patched font on Kali Linux:

### 1. Download the Patched Font

First, download the JetBrains Mono patched font from a trusted source. You can get the patched version from the [Nerd Fonts repository](https://www.nerdfonts.com/).

Here’s how to do it using the terminal:

```bash
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v2.3.3/JetBrainsMono.zip -O JetBrainsMono.zip
```

2. Unzip the Downloaded File
Unzip the downloaded font archive:

```bash
unzip JetBrainsMono.zip -d JetBrainsMono
```

3. Install the Font
Move the font files to the system's font directory:

```bash
sudo mkdir -p /usr/share/fonts/truetype/JetBrainsMono
sudo cp JetBrainsMono/*.ttf /usr/share/fonts/truetype/JetBrainsMono/
```

4. Update the Font Cache
Update the font cache so the system recognizes the new fonts:

```bash
sudo fc-cache -f -v
```

5. Verify the Installation
You can verify that the font was installed successfully by listing the installed fonts:

```bash
fc-list | grep "JetBrainsMono"
```