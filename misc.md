# MISC

1. Bundle Update
    ```bundle update```
2. Start local server
    ```bundle exec jekyll serve```

### YAML options

1. Add table of contents
    ```yaml
    toc: true
    toc_label: "Title for TOC"
    toc_icon: "cog" # FA icons can be used
    toc_sticky: false #Stick table of contents to top of screen
    ```

2. Excerpt
    ```yaml
    excerpt: "String"
    ```

3. Wide Page
    ```yaml
    classes: wide
    ```

4. Author Profile
    ```yaml
    author_profile: true
    author: Antariksh Narain
    ```

5. Header Overlay
    ```yaml
    excerpt: "This post should display a **header with an overlay image**, if the theme supports it."
    header:
        overlay_color: "#333"
        overlay_filter: 0.5
        overlay_image: /assets/images/unsplash-image-1.jpg
        caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
        actions:
            - label: "More Info"
            url: "https://unsplash.com"
    ```

6. Custom side bar content
    ```yaml
    sidebar:
        - title: "Title"
            image: http://placehold.it/350x250
            image_alt: "image"
            text: "Some text here."
        - title: "Another Title"
            text: "More text here."
    ```

## Collections

1. Refer the following [link](https://jekyllrb.com/docs/collections/)

2. Working with media [link](https://mmistakes.github.io/minimal-mistakes/docs/helpers/)

3. Utility classes [link](https://mmistakes.github.io/minimal-mistakes/docs/utility-classes/)