# basic-html-sandbox
A basic html features for learning principal tags


#Doctype
All HTML documents must start with a <!DOCTYPE> declaration.  
The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect.  
In HTML 5, the declaration is simple:

```sh
<!DOCTYPE html>
```

#HTML5 Overview
HTML5 is the latest version of Hypertext Markup Language that adds a handful of new HTML elements we can use to better define our page’s content for search engines.

#What HTML5 Means For SEO
Standard HTML tags (e.g.title, h1, etc.) form the basis of on-page SEO. Search engines use these tags to better understand what a page is about. Optimizing these factors is a basic SEO practice to improve rankings in the search results. HTML5 has provided us with a couple of new semantic elements that we might want to consider when optimizing our page.

#What’s a Semantic Element?
Semantic Elements refer to HTML elements that have a specific meaning. For example **h1** is a semantic element. It tells google bots that the content within the tag is the most significant header contained in the HTML document. **div** on the other hand, is a non-semantic element as it only indicates a division in the HTML document and provide no information on what goes before, after or within the tag.

#New Semantic Tags in HTML5
The release of HTML5 has seen the introduction of several new semantic tags that provide even richer information to search engines. Here is an overview of several HTML5 elements and what they mean for WordPress on-page SEO:

- **main**: The **main** tag encloses the dominant content of the blog including all article content and other related sections that extend the central theme of the page, such as the **article** tag and supporting **section** tags. 

- **article**: The **article** tag makes it easy to mark new blog posts or article entries in an online publication. Search engines can put more weight on any content wrapped with this tag. It also helps to clean up the HTML code by reducing the use of **div** tags.

- **section**: Blog posts are typically broken into different sections to make it easier for users to find what they are looking for. The **section** tag can be used to specify these subsections of your content, each with their own separate HTML heading. 

- **header**: The **header** tag is similar to the **h1** tag in that it can be used to specify the header of a page. But it can also be used to indicate the header section of a page and can even contain navigation links and other relevant text.

- **footer**: While not as useful as the **header** tag, the **footer** tag still offers SEO benefits as it can be used to specify content in the footer section of a website such as company information and other useful links. Each page can even have its own footer section.

- **nav**: Navigation is undoubtedly one of the most important aspects of a site. The **nav** tag can be used to specify links on a page such in the main site navigation or for pagination.

- **video**: The **video** tag is easily one of the most useful tags as it allows for cross-browser compatibility to display videos without having to use Flash. HTML5 also makes it possible to include additional information about the video such as captions and subtitles.

- **aside**: An **aside** tag can be like a section tag, but one that focuses on secondary content such as  sidebar, or a post-article call to action might be a good place to use **aside** tags.


taken from https://www.inboundnow.com/html5-semantic-elements-mean-seo/


#Section Elements in HTML5
- **HTML Navigational Element** (**nav**) defines a section that contains navigation links that appear often on a site. You can have primary and secondary menus, but you cannot nest a **nav** element inside another **nav** element.

- **HTML Article Element** (**article**) defines a piece of self-contained content. It does not refer to the main content alone and can be used for comments and widgets.

- **HTML Section Element** (**section**) defines a section of a document to indicate a related grouping of semantic meaning. It makes sense to use the section element to provide extra context for the parent element.

- **HTML Aside Element** (**aside**) defines a section that, though related to the main element, doesn't belong to the main flow, like an explanation box or an advertisement. The aside element has its own outline, but doesn't belong to the main one.

#Other Semantic HTML elements used in Sectioning
- **HTML Body Element** (**body**) defines all the content of a document. It contains all the content and HTML tags.
  
- **HTML Header Element** (**header**) defines a page area that typically contains a logo, title, and navigation. The header can also be used inside other semantic elements such as **article** or **section**. A section header might contain the section's heading, author name, etc. **article**, **section**, **aside**, and **nav** can have their own **header**. Despite its name, the header is not necessarily positioned at the beginning of a page or section.
  
- **HTML Footer Element** (**footer**) defines a page footer, which typically contains copyright or legal notices and sometimes some links. In the context of a section, a footer might contain the sectioned content's publication date, license information, etc. **article**, **section**, **aside**, and **nav** can have their own **footer**. Despite its name, the footer is not necessarily positioned at the end of a page or section.
  
#How Do Sectional Elements Work?

```sh
 <body>
    <header>
      <nav>
        <ul>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
          <li><a href="#">link</a></li>
        </ul>
      </nav>
      <h1>
        Page Title
      </h1>
    </header>

    <section>
      <h2>
        My Blog Posts
      </h2>
      <article>
        <header>
          <p>
            Article Title
          </p>
        </header>
        <p>
          content
        </p>
      </article>
      <article>
        <header>
          <p>
            Article Title
          </p>
        </header>
        <p>
          content
        </p>
      </article>
      <aside>
        <p>
          Author info
        </p>
      </aside>
    </section>

    <footer>
      Copyright Info
    </footer>
  </body>
```

taken from: https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Using_HTML_sections_and_outlines#how_do_sectional_elements_work