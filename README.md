# Week1--HTML-CSS
HTML- HyperText Markup Lannguage
    - declarative language -instructions are declared. 
    - simple, resilient and robust - incorrect syntax can be fixed and have the program running. 

CSS - Cascading Style Sheet
    - For styling. Your fonts, colour, animations etc. 
    - an error in css code can be skipped, the next part is executed. The browser produces the best possible outcome from the executed instructions.   
Javascript - more advanved in terms of capabilities in reference with  HTML and CSS.  
           - enables you to create a more interactive stuff.  
           - unlike HTML and CSS it has no way to cater for errors, any error in code or oudated browser of a code it doesnt understand, it just does not execute the code, doesnt even try. Its said to be fraigile                 - because of this.  

  TEXT FORMATING
  HTML Syntax - used to structure web pages. 
              - it uses tags- are enclosed by  <> signs i.e <p> .  
              - there are two types of tags - opening tags and closing tags. 
              - the opening tag for a paragraph is <p>, and the closing tag is </p>. 
              - enclosed between the tags is an element. It is the content insde. 

              - Some elements require both an opening and a closing tag, while others do not. 
              - spme elements can be nested.  

              - an entire HTML document is basically a bunch of HTML elements nested inside each other. 
              - The browser  builds a big family tree that shows how everything is related, this is called a DOM tree - Document Object Model. 
              - The browser uses the DOM tree to create an accessibility tree. 
                    - Your choice of HTML elements actually impacts the user experience on your website, including people with various disabilities. It all starts with nesting those HTML elements.
        Paragraphs: HTML tags are used to indicate the paragraphs. <p> as an opening tag and </p> as a closing tag. This tells the browser that it is a separate paragraph. 

  HTML HEADLINES
  -The HTML elements used for marking up headlines come in six different types: h1, h2, h3, h4, h5, and h6.
      -the heirachy gives an indication on how the browser presents it: h1 being the largest and boldest and h6 being the smallest and lest\ast attention grabbing.
      
HTML BOLD and ITALICS
      -There are four HTML elements related to this, two for bold and two for italic.
         - ITALICS
          -use the "<i>" element to apply visual italics and the "<em>" element to add emphasis. 
              - they look the same but serve different purposes. It is about communicating semantics and human meaning. 
        - BOLD
            - "<strong>" to highlight a specific part of a phrase as more significant than the rest. 
            - f we want to make certain words bold without conveying any meaning, we can use the "<b>" element. This is useful when we want a specific phrase to catch the reader's attention, but we do not want it                 to hold any special significance for the browser or screen reader. 

  HTML LISTS
     - 3 type of lists ; 1. nordered lists
                         2. ordered lists
                         3. Definition lists.
                         
              nordered lists
                - make use of <li>  tag. 
                    e.g. <li> flour</li>
                         <li> bones</li>
                when viewed on the browser it will be a list with bullets next to each item. 
                -the lists are enclosed between <ul> and </ul> tags. 
                    - no numerical order. 
                    - this gives an indication that this is an unordered list. 
                    
             ordered lists
                 -makes use of <li> tag. 
                    e.g  - <li> flour</li>
                         -<li> bones</li>
                      -the lists are enclosed between <ol> and </ol> tags. 
                      this <ol> indicates that this is an orderd list and on the browser a list with numbers will show. 
                         e.g 1. flour
                             2. bones
                             
            - Unordered and ordered lists are quite similar, except for the wrapping element they use.

              definition list/description list
                - tags used: <dt> definition term  - 
                             <dd> definition description
                               - can be used multiple times if you want multiple descrptions.  
                             <dl> definition list - The entire list is wrapped in a <dl>
                          Interestingly, the <dd>  and  <td> tags are placed side by side without any additional wrapper around them. This is simply how a definition list is structured. 
              - HTML Quotes
              
                      two elements:  
                      <cite> and <blockquote>  
                        serve a semantic purpose.   
                        <blockquote> 
                        <p> TEXT </P>
                        <cite> -Jeremy Z
                        </blockquote>

                    inline quotes
                    <strong>, <b>, <I>, and <em>, are called "inline" because they are meant to wrap around phrases of text that are inline with other content. 
                    <q> ued for quote. 

              -block-level elements, like block quotes, paragraphs, and unordered lists.

            Date elements 

            HTML Date and Time Inputs
              - uses <time> elements. 
              - opening tag (<time>) and a closing tag (</time>). 
              - i.e. <time>May 8th</time> 
                    -<time>May 8th 2025</time> 

        HTML Code, pre and br
                - showcase code on a webpage:
                    -code element
                        - <code> {colour green} </code>
               Let's say we want to change the word "H4" by putting brackets around it. However, doing so turns the word into an actual H4 headline instead of displaying "H4" as text. Let me try wrapping it in a                  code element, but unfortunately, that will not prevent the browser from interpreting it as an H4 tag. To achieve this, we need to type "&lt;". This is known as an HTML entity. When we type                         "&lt;", it will be displayed as a less than sign. Similarly, typing "&gt;" will show a greater than sign.

         Br element
                 - line breaks in sentences at the end of each lines. 
                 - i.e.  <p>
                         They<br>
                        you took my open <br>
                        </p>
                - notice how  there the br element is a simple tag without an opening or closing tag.
        pre element
                -when  you want the spacing to be an integral part of the content's meaning. 
                - use HTML and the pre element <pre> to achieve that. 
                    -Wrap the poem in pre tags, and now you can see that the browser respects the spacing, line breaks, and everything else. 
     
        HTML Superscripts, Subscripts and Small Text
            - can be used where you need to mark up certain bits of content as having a different meaning than the rest.

            superscripts
                -Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. 
                -Superscript text can be used for footnotes, like WWW[1]
            Subscripts are characters that are set below the normal baseline for text. 
            
            - i.e <p>something that has a footnote <sup>2<sup></p> = something that has a footnote. (to the power2) 
                    <small> 2019 fancy campany = 2019 fancy company (appears as a small font)
                    <p>H<sub>2</sub>o</p>

    HTML Capabilities
    Troubleshooting and Debugging HTML Code
    -debugging code
        -broken code
        <ol>
        <li>one</li>
        <li>two<li>
        <li>three</li>
        <li>four</li>
        </ol>

        Code excecuted by the browser
            1. one
            2. two
            3. 
            4. three
            5. four
    - issue with the code is that there is no proper closing of the list element. 

    HTML Attributes
        -global attributes
            - class attribute: most commonly used. 
                -It allows one to assign a reusable name to any element. 
                    -can then be styled using CSS for all elements sharing that class. 
            -ID attribute
                - can only use unique names once on an entire HTML page
                come in handy when we need to address specific elements in JavaScript or targeted links. The uniqueness of an ID name ensures that there will always just be one element with that ID, making it                      useful for interacting with JavaScript or links. Regardless of the use case, class and ID attributes provide a way to name HTML elements and reference them in other parts of the code stack.
            -dir attribute 
                -Specifies the text direction for the content in an element
            -lang	
                -Specifies the language of the element's content

        ARIA Roles
            - are like extra attributes that we can add to HTML elements to make them more meaningful and help browsers understand what they represent. 
            -The goal is to rely on proper HTML elements to convey the right message about the content's meaning, without needing ARIA Roles. However, reality does not always align with ideals, and sometimes                     compromises have to be made in the code. It becomes a big problem if these compromises make a website difficult or impossible for people with disabilities to use it. In fact, it is against the law in               many places to have an inaccessible website for people with disabilities. 
                - browser accessibility tree
                    -he accessibility tree is like a companion to the DOM tree, which the browser creates from the website's content. While the DOM tree represents the structure of the HTML, the accessibility tree                  is crucial for assistive devices like screen readers. It allows them to provide a better experience to users. When we look at the accessibility tree, we can see that it treats the content as                        separate text containers. However, this can result in a poor experience, such as each letter of "hello" being read out individually. To improve this, we can use ARIA.


        ARIA roles are added to HTML elements using role="role type", where role type is the name of a role in the ARIA specification.
                -For example, <ul role="tabpanel"> will be announced as a 'tab panel' by screen readers. However, if the tab panel doesn't have nested tabs, the element with the tabpanel role is not in fact a tab                   panel and accessibility has actually been negatively impacted.
      
        There are 6 categories of ARIA roles:
            -. Document structure roles
                    - provide a structural description for a section of content
            - Widget roles
            -Landmark roles
                    -landmark roles provide a way to identify the organization and structure of a web page. By classifying and labeling sections of a page, structural information conveyed visually through layout                        is represented programmatically. 
            - Live Region Roles
                    -used to define elements with content that will be dynamically changed. Sighted users can see dynamic changes when they are visually noticeable. These roles help low vision and blind users know                      if content has been updated.
            - Abstract roles
                    - Abstract roles are only intended for use by browsers to help organize and streamline a document.
       
        Formatting HTML
        REDO

        HTML Navigation and Linking
            -HTML Links
                - The HTML <a> tag defines a hyperlink. It has the following syntax:
                -The target Attribute
                    -The target attribute can have one of the following values:

                        _self - Default. Opens the document in the same window/tab as it was clicked
                        _blank - Opens the document in a new window or tab
                        _parent - Opens the document in the parent frame
                        _top - Opens the document in the full body of the window

    - Absolute URLs vs. Relative URLs
        -Both examples above are using an absolute URL (a full web address) in the href attribute.

            -A local link (a link to a page within the same website) is specified with a relative URL (without the "https://www" part):
            Absolute url has "www"
            Relative URL has  no www at he beginning. 
    - HTML Links - Use an Image as a Link
        -To use an image as a link, just put the <img> tag inside the <a> tag:
            -<a href="default.asp">
            <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
            </a>

Example
                
        
    HTML Working with Graphics and Images
    Images


              
              
  
