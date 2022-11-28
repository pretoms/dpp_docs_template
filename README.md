# DPP documentation template

This is a template for the *Design for Physical Prototyping* project documentation. 
It is a modified version of the *bare-minimum* [Jekyll] template [Just the Docs].
It can be built and published on [GitHub Pages].

To get started with creating a site, clone this repository by clicking "[use this template]"!

After completing the creation of your new site on GitHub, update it as needed:

## Replace the content of the template pages

Update the following files to your own content:

- `index.md` (your new home page)
- `README.md` (replace it with your text or just keep it empty: information for those who access your site repo on GitHub)

## Get familiar with Markdown

Markdown is a lightweight markup language for creating formatted text using a plain-text editor.
[Here](https://commonmark.org/help/) you can find a reference and a tutorial for getting started.

## Publishing your site on GitHub Pages

1.  If your created site is `YOUR-USERNAME/YOUR-SITE-NAME`, update `_config.yml` to:

    ```yaml
    title: YOUR TITLE
    description: YOUR DESCRIPTION
    theme: just-the-docs

    url: https://YOUR-USERNAME.github.io/YOUR-SITE-NAME

    aux_links: # remove if you don't want this link to appear on your pages
      Template Repository: https://github.com/YOUR-USERNAME/YOUR-SITE-NAME
    ```

2.  Push your updated `_config.yml` to your site on GitHub.

3.  In your newly created repo on GitHub:
    - go to the `Settings` tab -> `Pages` -> `Build and deployment`, then select `Source`: `GitHub Actions`.
    - if there were any failed Actions, go to the `Actions` tab and click on `Re-run jobs`.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Jekyll]: https://jekyllrb.com
[Just the Docs]: https://github.com/just-the-docs/just-the-docs-template
[GitHub Pages]: https://docs.github.com/en/pages
[use this template]: https://github.com/pretoms/dpp_docs_template/generate
