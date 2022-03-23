# Site-Refactor

## The Purpose of This Project

In this project, I was provided an existing set of HTML and CSS code for a digital marketing company. The original code, while functional, did not include the proper accessibility features based on W3C Accessibility Standards.

My objective was to refactor this code for accessibility by doing the following: adding semantic HTML elements wherever possible, reviewing and reorganizing the code to ensure a logical overall structure, adding accessible alt attributes to icons/images, ensuring sequential order of all heading attributes, updating the title element with a concise, descriptive title.

## Examples

HTML with semantic elements.
```html
 <header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
```

HTML that is structured logically and provides accessible alt text to imaages.
```html
<section class="content">
        <article id="search-engine-optimization" class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="Desktop with writing utensils, computer, notebook, and cup of coffee" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>    
```

## License

MIT License

Copyright (c) 2022 Andrew Mason

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## References

Original code provided by UC Berkeley Extension

![HTML Badge](https://img.shields.io/badge/Language-<HTML>-<blue>)
![HTML Badge](https://img.shields.io/badge/Language-<CSS>-<red>)
