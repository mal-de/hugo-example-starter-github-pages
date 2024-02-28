# Hugo Example Starter for GitHub Pages

This repository provides a simple starter template for creating a website using Hugo and hosting it on GitHub Pages. Follow the instructions below to set up the project.

## Installation Process

1. Open your terminal.
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hugo-example-starter-github-pages.git
   ```
3. Change directory to the cloned repo:
   ```bash
   cd hugo-example-starter-github-pages
   ```
4. Run the setup script:
   ```bash
   ./setup.sh
   ```

## File Structure

### Content
- In the `content` folder, you'll find the `_index.md` file. Edit this file to customize the main content of your site.

### Layouts
- The `layouts` folder contains HTML files that structure the entire website. Only edit these if you are familiar with Hugo templating.

### Static
- In the `static` folder:
  - `assets`: Contains the CSS files, primarily `split.css` for styling. Edit this file if you want to customize the styles.
  - `images` and `videos`: Save the images and videos you want to use on the website.
  - `favicon.ico`: This is the favicon for your site. Replace it with another icon if needed. A favicon is a small icon associated with a website, typically displayed in the browser's address bar or tabs, serving as a visual identifier for the site.

### Public
- The `public` folder contains the generated build files. Developers typically don't need to touch this folder as it's automatically generated.

### Config.toml
- Edit the `config.toml` file. Pay attention to lines under "[params]". Lines starting with # are comments. Customize these settings according to your preferences.

## Getting Started Developing Locally

1. Edit the content in `_index.md`.
2. Add images and videos to `static/images` and `static/videos`.
3. Replace the `favicon.ico` with your desired icon.
4. Edit configuration settings in `config.toml`, especially those under "[params]".
5. Customize styles in `static/assets/split.css` if needed.
6. Customize structure in `layouts` if needed.

Now, your Hugo website is ready for customization and can be deployed on GitHub Pages! To preview your site, run `hugo server -D` in the terminal and visit the provided local address.

## Deploy to Github Pages

Refer to following page for more information: https://gohugo.io/hosting-and-deployment/hosting-on-github/

Note: A github workflow was already added to the repository. Update `.github/workflows/hugo.yaml`, if necessary.

--------------------------------------------------------------------------------

## License

The original template is released under the [Creative Commons Attribution 3.0 License](//github.com/escalate/hugo-split-theme/blob/master/LICENSE.md). Please keep the original attribution link when using for your own project. If you'd like to use the template without the attribution, you can check out the license option via the template [author's website](//onepagelove.com/split).

## Annotations

- Original [Split](//onepagelove.com/split) Template by [One Page Love](//onepagelove.com)
- Hugo Port of Split template by [Felix Börner](https://github.com/escalate/hugo-split-theme)
