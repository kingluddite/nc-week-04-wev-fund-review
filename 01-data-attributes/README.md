# Here's an example of how you can use HTML data attributes with a list of 1980s TV shows:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>1980s TV Shows</title>
    <style>
      ul {
        list-style: none;
        padding: 0;
      }
      li {
        margin-bottom: 10px;
      }
      li[data-genre="comedy"] {
        color: green;
      }
      li[data-genre="drama"] {
        color: blue;
      }
    </style>
  </head>
  <body>
    <h1>1980s TV Shows</h1>
    <ul>
      <li data-show-id="1" data-genre="comedy">Cheers</li>
      <li data-show-id="2" data-genre="comedy">The Golden Girls</li>
      <li data-show-id="3" data-genre="drama">Dallas</li>
      <li data-show-id="4" data-genre="drama">Dynasty</li>
      <li data-show-id="5" data-genre="comedy">The Cosby Show</li>
    </ul>
  </body>
</html>
```

In this example, we have an unordered list (`<ul>`) that contains a list of 1980s TV shows. We've used HTML data attributes to store additional information about each TV show. For example:

- `data-show-id` stores a unique identifier for each show.
- `data-genre` stores the genre of the show (comedy or drama).

We've also added some simple CSS styling to change the text color based on the genre using attribute selectors. Comedy shows are displayed in green, while drama shows are displayed in blue.

You can use data attributes like this to store additional information about elements in your HTML and then use CSS or JavaScript to manipulate and style those elements based on the data attributes.

## Why do I need HTML data attributes?

HTML data attributes are used to store additional information or metadata about elements on a web page. They provide a way to include custom data that is not part of the standard HTML attributes. Here are some common reasons why you might need HTML data attributes:

1. **Storing Custom Data**: You can use data attributes to store custom data that is specific to your application or website. This data might not have a predefined HTML attribute that accurately describes it. For example, you can store unique identifiers, additional descriptions, or custom settings for elements.

2. **JavaScript Interaction**: Data attributes are often used in JavaScript to provide additional information about elements. You can use JavaScript to access and manipulate the data stored in these attributes. This is particularly useful when building dynamic web applications.

3. **CSS Styling**: Data attributes can be used in CSS to apply styling to elements with specific data attributes. You can use attribute selectors in your CSS to target and style elements based on their data attributes.

4. **Accessibility**: Data attributes can be used to improve the accessibility of your web content. They can provide additional context or information to assistive technologies, making your website more user-friendly for people with disabilities.

5. **Third-party Libraries and Frameworks**: Many JavaScript libraries and frameworks, such as jQuery and Bootstrap, use data attributes for configuration and interactivity. By following their conventions and using data attributes, you can easily integrate these tools into your web pages.

6. **Avoiding Global Variables**: Instead of using global variables in JavaScript to store data related to specific elements, you can use data attributes to associate data directly with the HTML elements themselves. This can lead to cleaner and more maintainable code.

7. **Documentation and Semantics**: Data attributes can serve as a form of documentation, providing a clear way to understand the purpose or meaning of an element. This can be especially helpful for developers who are maintaining or working on a project.

8. **Compatibility and Validation**: Data attributes are valid HTML and do not interfere with HTML validation. They are a standard and recommended way to add custom data to your HTML elements.

In summary, HTML data attributes are a versatile and valuable tool that can enhance the functionality, accessibility, and organization of your web pages. They offer a structured way to attach custom data to elements and are particularly useful when working with JavaScript and CSS to create dynamic and interactive web content.
