HTML (Hyper Text Markup Language)

    -> HTML is the standard markup language for creating Web pages.
    -> HTML describes the structure of a web page
    -> HTML elements tell the browser how to display the content
    -> HTML consists of a series of elements
    -> HTML extention is .html
    -> HTML is not a programing language

    1. The Anatomy of HTML Tags:

        <a href="https://example.com" target="_blank">

        < … > → tag boundary
        a → tag name
        href="https://example.com" → attribute + value
        target="_blank" → another attribute

        Tags = structure, Elements = tags + content, Attributes = extra info


    <!DOCTYPE html> 
        -> It tells the browser which version of HTML the page is written in so the browser knows how to interpret and render it correctly. 

        -> It is not an HTML tag
        -> It must be at the very top of the document
        -> It helps the browser render your page correctly
        -> Modern HTML uses: <!DOCTYPE html>   

    2. Inside the head tag :

        <html lang="en"> 
            -> is the opening tag of the HTML document with a language attribute.
            -> lang="en" This is a language attribute that tells the browser and assistive technologies the primary language of the page.
            -> Helps screen readers read the text correctly
       
        <head> 
            -> The <head> tag is a section of an HTML document that contains information about the webpage, not the content shown directly on the screen.
            -> It is placed inside the <html> tag and before the <body> tag.
            <title> → Shows text in browser tab
            <meta charset> → Sets text encoding
            <meta name="viewport"> → Makes website responsive (important for mobile)
            <meta name="description"> → Helps in SEO
            <link> → Connect CSS file
            <script> → Connect JavaScript

    3. Inside body tag :

        <body>
            -> The <body> tag contains everything that is visible on the webpage.
            -> Whatever you put inside <body> will appear on the browser screen.
            -> It comes after the <head> tag.
            -> All visible page content, such as:
                1.Text 
                2.Headings
                3.Images
                4.Links
                5.Buttons
                6.Forms
                7.Tables
                8.Videos
                9.Lists
                1o.Any other UI content

            Text - In HTML, text is the content displayed on a webpage. You place text inside specific tags that tell the browser how to display it.

                1. Paragraph Text - Used for normal text content.
                    Use <p> for normal text
                Ex :-
                    <p>This is a paragraph of text.</p>

                2. Inline Text Formatting - Used to style parts of text.
                    -> Bold
                        <b>Bold Text</b>
                        <strong>Important Bold Text</strong>

                    -> Italic
                        <i>Italic Text</i>
                        <em>Emphasized Text</em>

                    -> Underline
                        <u>Underlined Text</u>

                    Use <b>, <i>, <u>, <strong>, <em> for styling

                    -> Line Break - Moves text to next line (without starting a new paragraph).
                        Use <br> for line breaks
                            Line 1<br>Line 2

                    -> Preformatted Text - Shows text exactly as typed (keeps spaces & line breaks).
                        Use <pre> for fixed formatting
                        <pre>
                            This text
                                keeps
                                    spaces and lines
                        </pre>
