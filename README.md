# This is a template that I use (link here: https://github.com/LeNPaul/academic). 

# This README documents how I use this template.

## Usage

### Layouts

The following sections describe usage instructions for this Jekyll theme,including available layouts, includes, sass and/or assets.

### website modules

The '_data/settings.yml' defines what modules the website shows.

#### Home

The `_layouts/home.html` layout defines the home page for this theme. An introduction to your research group or to yourself can be provided.
The 'index.md' is the content on the home page.

#### Publications

Publications (the content) are defined in the `_data/publications.yml` file, and any PDF files that are served can be placed in the `publications` directory.
The '_includes/publications.html' defines the aesthetics of the publications page.

#### Courses

The `_layouts/courses.html` layout can be used to showcase courses that were taught in the past or are currently being taught. Courses are defined in the `_data/settings.yml` file, and markdown pages for each course with the `_layouts/page.html` layout can be placed in the `courses` directory. Related course material, such as PDF files, can also be placed in the `courses` directory in a subdirectory with the same name as the corresponding course.

#### CV

The `_layouts/cv.html` layout can be used to showcase a curriculum vitae. (The sections of the cv are defined in the `_data/cv` directory, where each section has its own `<section>.yml` file.

#### Contact

The `_layouts/contact.html` layout can be used to provide contact information for the research group or the people that lead the research group. Contact information is defined in the `_data/settings.yml` file.

## Development

To set up your environment to develop this theme, run `bundle install`, then run `bundle exec jekyll serve`, and open your browser at `http://localhost:4000`. This starts a Jekyll server using this theme. Make changes to the pages, documents, data, etc. like normal to test this theme's contents. As you make modifications to this theme the site will regenerate and you should see the changes in the browser after a refresh.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
