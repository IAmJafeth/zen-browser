<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://zen-browser.app/">Zen Browser</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/zen-browser/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/zen-browser?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/zen-browser/issues"><img src="https://img.shields.io/github/issues/catppuccin/zen-browser?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/zen-browser/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/zen-browser?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

1. [Create a `chrome` folder](https://www.userchrome.org/how-create-userchrome-css.html) in your browser's profile directory.
2. Copy the `userChrome.css`, `userContent.css`, and `zen-logo.svg` files of your preferred theme from the [`themes/`](themes/) directory in this repository to your `chrome` folder.

> [!NOTE]
> If you're using the [🌻 Latte](themes/Latte/) theme, set your browser to light mode. For [🪴 Frappé](themes/Frappe/), [🌺 Macchiato](themes/Macchiato/), or [🌿 Mocha](themes/Mocha/), enable dark mode to apply the theme correctly.

## 🙋 FAQ

- **Q:** What if I already have a `userChrome.css` and/or `userContent.css` configuration?
  
  **A:** You have two options:
  
  1. Copy and paste the content of our `userChrome.css` and/or `userContent.css` files into your existing ones.
  2. Alternatively, you can import them directly by adding the following lines to your existing files:
  
     **For `userChrome.css`:**
     ```css
     /* Latte Pink */
     @import url("https://raw.githubusercontent.com/IAmJafeth/zen-browser/main/themes/Latte/Pink/userChrome.css");

     /* Mocha Mauve */
     @import url("https://raw.githubusercontent.com/IAmJafeth/zen-browser/main/themes/Mocha/Mauve/userChrome.css");
     ```

     **For `userContent.css`:**
     ```css
     /* Latte Pink */
     @import url("https://raw.githubusercontent.com/IAmJafeth/zen-browser/main/themes/Latte/Pink/userContent.css");

     /* Mocha Mauve */
     @import url("https://raw.githubusercontent.com/IAmJafeth/zen-browser/main/themes/Mocha/Mauve/userContent.css");
     ```

- **Q:** Can I automatically switch flavors between light and dark mode?
  
  **A:** Yes! You can concatenate or import the `userChrome.css` and `userContent.css` files for 🌻 Latte (light mode) along with one of the dark mode themes like 🪴 Frappé, 🌺 Macchiato, or 🌿 Mocha. The browser will automatically switch between these themes when toggling between light and dark mode.

## 💝 Thanks to

- [IAmJafeth](https://github.com/IAmJafeth)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
