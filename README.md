
# WhiteSur GTK Theme (Espelho Pessoal)

Este repositório é uma **cópia pessoal** do tema WhiteSur GTK, inspirado no visual do macOS, e utilizado em distribuições Linux como Ubuntu, Pop!_OS, Fedora, Zorin, entre outras.

> ✅ Repositório original: [https://github.com/vinceliuice/WhiteSur-gtk-theme](https://github.com/vinceliuice/WhiteSur-gtk-theme)

## 📌 Objetivo

Este repositório foi criado apenas para **uso pessoal, testes e instalação em ambientes controlados**. Nenhuma modificação foi feita no código original.

## 🎨 Recursos do tema

- Compatível com GTK 3, GTK 4, libadwaita
- Temas claros e escuros
- Várias cores de destaque (accent colors)
- Estilo visual baseado no macOS Big Sur / Monterey
- Suporte a GNOME, XFCE, Cinnamon, etc.

## 💻 Instalação

1. Instale dependências:

```bash
sudo apt update
sudo apt install -y sassc libglib2.0-dev-bin libxml2-utils imagemagick optipng inkscape dialog
````

2. Clone este repositório:

```bash
git clone https://github.com/Israzuba0023/WhiteSur-gtk-theme.git --depth=1
cd WhiteSur-gtk-theme
```

3. Instale o tema:

```bash
./install.sh -c dark -t blue -m -l
```

### Opções:

| Flag | Descrição                             |
| ---- | ------------------------------------- |
| `-c` | Cor do tema (`dark` ou `light`)       |
| `-t` | Cor de destaque (`blue`, `red`, etc.) |
| `-m` | Estilo Monterey                       |
| `-l` | Suporte ao libadwaita (GTK4)          |

## 🔧 Ajustes adicionais (opcional)

### Aplicar tema à tela de login (GDM):

```bash
sudo ./tweaks.sh --gdm --color dark --opacity solid
```

### Ativar suporte a Flatpak:

```bash
./tweaks.sh -F
```

### Aplicar tema ao Firefox:

```bash
./tweaks.sh -f monterey
```

## 📄 Licença

Este projeto segue a [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html), conforme o repositório original.

## 🙏 Agradecimentos

Criado por [vinceliuice](https://github.com/vinceliuice) – todos os créditos ao autor original.

Este repositório é apenas uma cópia para fins de estudo e personalização no Ubuntu.


### ✅ Como adicionar ao repositório

1. No terminal:
```bash
cd WhiteSur-gtk-theme
nano README.md
````

2. Cola o conteúdo acima, guarda com `CTRL+O`, depois `ENTER`, e sai com `CTRL+X`.

3. Comita e envia:

```bash
git add README.md
git commit -m "Adiciona README com instruções e créditos"
git push origin main
```

---

#### 1. Run command to fix it

```sh
sudo flatpak override --filesystem=xdg-config/gtk-3.0 && sudo flatpak override --filesystem=xdg-config/gtk-4.0
```

If you use flatpak apps, you can run this to fix theme issue

#### 2. Connect WhiteSur theme to Flatpak (gtk 3.0) (Snap not support)

Parameter: `--flatpak` `-F`

Example: `./tweaks.sh -F`

## <p align="center"> <b> Other recommended stuff </b> </p>
### <p align="center"> <b> WhiteSur Icon Theme </b> </p>
<p align="center"> <a href="https://github.com/vinceliuice/WhiteSur-icon-theme">
  <img src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/icon-theme.png"/>
</a> </p>
<br>
<p align="center"> <a href="https://github.com/vinceliuice/WhiteSur-icon-theme">
  <img src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/download-button.svg"/>
</a> </p>
<br>

### <p align="center"> <b> WhiteSur Wallpapers </b> </p>
<p align="center"> <a href="https://github.com/vinceliuice/WhiteSur-wallpapers">
  <img class="image" src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/wallpaper.gif"/>
</a> </p>
<br>
<p align="center"> <a href="https://github.com/vinceliuice/WhiteSur-wallpapers">
  <img src="https://github.com/vinceliuice/WhiteSur-gtk-theme/blob/pictures/pictures/download-button.svg"/>
</a> </p>
<br>

## Technical details and getting involved
Please go read [CONTRIBUTING.md](.github/CONTRIBUTING.md) for more info
