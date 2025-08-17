<!-- Improved compatibility of back to top link: See: https://github.com/dhmnr/skipr/pull/73 -->
<a id="readme-top"></a>

<!-- *** Thanks for checking out the Best-README-Template. If you have a suggestion *** that would make this better, please fork the repo and create a pull request *** or simply open an issue with the tag "enhancement". *** Don't forget to give the project a star! *** Thanks again! Now go create something AMAZING! :D -->

<!-- PROJECT SHIELDS -->
<!-- *** I'm using markdown "reference style" links for readability. *** Reference links are enclosed in brackets [ ] instead of parentheses ( ). *** See the bottom of this document for the declaration of the reference variables *** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use. *** https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
<!-- [![LinkedIn][linkedin-shield]][linkedin-url] -->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">🌟 Personal Portfolio Website</h3>

  <p align="center">
    A simple, clean, and responsive Jekyll theme for academics and professionals, featuring light/dark mode, CV generation, publications, and more.
    <br />
    <a href="https://github.com/virtual457/virtual457.github.io"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/virtual457/virtual457.github.io">View Demo</a>
    ·
    <a href="https://github.com/virtual457/virtual457.github.io/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/virtual457/virtual457.github.io/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project implements a **Personal Portfolio Website** using the al-folio Jekyll theme, which is a simple, clean, and responsive theme designed for academics and professionals. The theme provides a comprehensive platform for showcasing personal information, projects, publications, and more.

### Key Features

- **Light/Dark Mode**: Built-in light/dark mode with automatic detection
- **CV Generation**: Multiple ways to generate CV content (JSON, YAML)
- **Publications**: Automatic generation from BibTeX bibliography
- **Projects**: Responsive grid layout for showcasing work
- **Blog Support**: Distill-style blog posts with full math and code support
- **Responsive Design**: Mobile-friendly layout with Bootstrap grid system
- **Social Media Integration**: Open Graph meta tags for social sharing
- **GitHub Integration**: Display repositories and user statistics

### Light/Dark Mode

This template has a built-in light/dark mode. It detects the user preferred color scheme and automatically switches to it. You can also manually switch between light and dark mode by clicking on the sun/moon icon in the top right corner of the page.

### CV Generation

There are currently 2 different ways of generating the CV page content:
1. **JSON File**: Using a json file located in `assets/json/resume.json` following the [JSON Resume standard](https://jsonresume.org/)
2. **YAML File**: Using a yml file located in `_data/cv.yml` as a fallback option

### Publications

Your publications' page is generated automatically from your BibTeX bibliography. Simply edit `_bibliography/papers.bib`. You can also add new `*.bib` files and customize the look of your publications by editing `_pages/publications.md`.

### Collections

This Jekyll theme implements `collections` to let you break up your work into categories. The theme comes with two default collections: `news` and `projects`. Items from the `news` collection are automatically displayed on the home page. Items from the `projects` collection are displayed on a responsive grid on projects page.

### Layouts

**al-folio** comes with stylish layouts for pages and blog posts:

- **Distill Style**: Create blog posts in the [distill.pub](https://distill.pub/) style
- **Math Support**: Fast math typesetting through MathJax
- **Code Highlighting**: GitHub-style syntax highlighting
- **Charts & Diagrams**: Support for Chart.js, Mermaid, and TikZ
- **Media Support**: Photos, audio, video, and more with Bootstrap grid

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [Jekyll](https://jekyllrb.com/)
* [Bootstrap](https://getbootstrap.com/)
* [MathJax](https://www.mathjax.org/)
* [Chart.js](https://www.chartjs.org/)
* [Mermaid](https://mermaid-js.github.io/mermaid/)
* [TikZ](https://tikzjax.com/)
* [GitHub Pages](https://pages.github.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Ruby and Jekyll
* Git
* GitHub account for deployment

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/virtual457/virtual457.github.io.git
   ```
2. Navigate to the project directory
   ```sh
   cd virtual457.github.io
   ```
3. Install Jekyll and dependencies
   ```sh
   bundle install
   ```
4. Run the development server
   ```sh
   bundle exec jekyll serve
   ```

For detailed installation and deployment instructions, please refer to [INSTALL.md](INSTALL.md).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

### Customization

For customization details please refer to [CUSTOMIZE.md](CUSTOMIZE.md).

### GitHub Integration

**al-folio** uses [github-readme-stats](https://github.com/anuraghazra/github-readme-stats) and [github-profile-trophy](https://github.com/ryo-ma/github-profile-trophy) to display GitHub repositories and user stats on the `/repositories/` page.

Edit the `_data/repositories.yml` and change the `github_users` and `github_repos` lists to include your own GitHub profile and repositories.

### Theming

A variety of beautiful theme colors have been selected for you to choose from. The default is purple, but you can quickly change it by editing the `--global-theme-color` variable in the `_sass/_themes.scss` file.

### Social Media Previews

**al-folio** supports preview images on social media. To enable this functionality you will need to set `serve_og_meta` to `true` in your `_config.yml`. Once you have done so, all your site's pages will include Open Graph data in the HTML head element.

### Atom (RSS-like) Feed

It generates an Atom (RSS-like) feed of your posts, useful for Atom and RSS readers. The feed is reachable simply by typing after your homepage `/feed.xml`.

### Related Posts

By default, there will be a related posts section on the bottom of the blog posts. These are generated by selecting the `max_related` most recent posts that share at least `min_common_tags` tags with the current post.

### Code Quality Checks

Currently, we run some checks to ensure that the code quality and generated site are good:

- [Prettier](https://prettier.io/) - check if the formatting of the code follows the style guide
- [lychee](https://lychee.cli.rs/) - check for broken links
- [Axe](https://github.com/dequelabs/axe-core) - do some accessibility testing

_For more examples, please refer to the [Documentation](https://github.com/virtual457/virtual457.github.io)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] Enhanced mobile responsiveness
- [ ] Additional theme color options
- [ ] Improved accessibility features
- [ ] Performance optimizations
- [ ] Additional layout options
- [ ] Enhanced social media integration
- [ ] Multi-language support
- [ ] Advanced analytics integration

See the [open issues](https://github.com/virtual457/virtual457.github.io/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contributing Guidelines

For detailed contributing guidelines, please refer to [CONTRIBUTING.md](CONTRIBUTING.md).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Chandan Gowda K S - chandan.keelara@gmail.com

Project Link: [https://github.com/virtual457/virtual457.github.io](https://github.com/virtual457/virtual457.github.io)

Project Link: [https://github.com/virtual457/virtual457.github.io](https://github.com/virtual457/virtual457.github.io)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [al-folio](https://github.com/alshedivat/al-folio) for the excellent Jekyll theme
* [Jekyll](https://jekyllrb.com/) for the static site generator
* [Bootstrap](https://getbootstrap.com/) for the responsive framework
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emojis](https://gist.github.com/rxaviers/7360908)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search.html?q=search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/virtual457/virtual457.github.io.svg?style=for-the-badge
[forks-shield]: https://img.shields.io/github/forks/virtual457/virtual457.github.io.svg?style=for-the-badge
[stars-shield]: https://img.shields.io/github/stars/virtual457/virtual457.github.io.svg?style=for-the-badge
[issues-shield]: https://img.shields.io/github/issues/virtual457/virtual457.github.io.svg?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/virtual457/virtual457.github.io.svg?style=for-the-badge
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[contributors-url]: https://github.com/virtual457/virtual457.github.io/graphs/contributors
[forks-url]: https://github.com/virtual457/virtual457.github.io/network/members
[stars-url]: https://github.com/virtual457/virtual457.github.io/stargazers
[issues-url]: https://github.com/virtual457/virtual457.github.io/issues
[license-url]: https://github.com/virtual457/virtual457.github.io/blob/master/LICENSE.txt
[linkedin-url]: https://www.linkedin.com/in/chandan-gowda-k-s-765194186/
