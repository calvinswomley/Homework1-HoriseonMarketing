# Homework1-HoriseonMarketing
Homework 1 - 8-28-2021 - Horiseon Marketing Website Refactoring

Description: This webpage has been refactored to follow accessability standards that will optimize the website for search engines. Improvements are detailed below and mainly include updating syntax to be more semantic and consolidating reptitive styling within the code base.


List of index.html file changes:
1. Browser tab title updated from 'Website' to 'Horiseon Marketing'. This is a more concise and descriptive title.
2. Alternative 'Alt' text addeded to images.
3. Background image given 'title' instead of 'alt' text for accessibility.
4. <div> tags throughout the Html file changed to more semantic elements that include the following:
    A. <Header> for the header that includes the title and navigation bar.
    B. <nav> for the navigation bar.
    C. <main> for the main area of the site.
    D. <aside> for the area on the right side of the site.
    E. <footer> for the the bottom footer area of the site.
    F. <section> for each sub area within the main and aside areas.
5. An Id was added to the Search Engine Optimization section to fix the broken Search Engine Optimization Link.
6. Alternative text was added to the heart emoji in the footer.
7. Footer changed from h2 header to h4 header so that heading attributes fall in sequential order.

List of style.css file changes:
1. Simplified and improved calarity of styling by consolidating syntax. Consolidations include:
    A. Three separate benefit class selectors with the same styling were replaced with the <aside> and <section>  selector elements.
    B. Three separate benefit class selectors with the same styling were replaced with the <aside> and <h3> selector elements.
    C. Three separate benefit class selectors with the same styling were replaced with the <aside> and <img> selector elements.
    D. Three separate content class selectors with the same styling were replaced with the <main> and <section> selector elements.
    E. Three separate content class selectors with the same styling were replaced with the <main> and <img> selector elements.
    F. Three separate content class selectors with the same styling were replaced with the <main> and <h2> selector elements.

Completed Refactor Screenshot:
![ Completed Horiseon Marketing webpage screenshot including a header, main section, side section and footer with functioning links, images and a codebase that follows accessability standards.](./assets/images/Completed_Homework_Mock-Up_Screenshot.PNG)


Link to Deployed Application:
