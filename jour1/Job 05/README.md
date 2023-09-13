# Job 05 - Structuring a Table in HTML

In this task, you learned how to create a structured table in HTML using the `thead`, `tbody`, and `tfoot` elements. This table was used to display data related to One Piece characters.

### Questions:

1. How to Use the `thead`, `tbody`, and `tfoot` Tags to Structure a Table?

   - The `thead`, `tbody`, and `tfoot` elements are used to structure an HTML table for better organization and semantics.

   - `<thead>` (Table Head): This element is used to group the header content of a table. It typically contains one or more `<tr>` (table row) elements that define the table's column headers.

   - `<tbody>` (Table Body): The `<tbody>` element contains the main content of the table, including the data rows. Each row of data is represented by a `<tr>` element within the `<tbody>`.

   - `<tfoot>` (Table Foot): The `<tfoot>` element is used to group the footer content of a table. It usually contains summary information or totals related to the data in the table. Similar to `<thead>`, it contains one or more `<tr>` elements.

   - Here's a basic example of how these elements are used:

     ```html
     <table>
       <thead>
         <tr>
           <th>Header 1</th>
           <th>Header 2</th>
         </tr>
       </thead>
       <tbody>
         <tr>
           <td>Data 1</td>
           <td>Data 2</td>
         </tr>
         <!-- More data rows here -->
       </tbody>
       <tfoot>
         <tr>
           <td>Total</td>
           <td>Sum</td>
         </tr>
       </tfoot>
     </table>
     ```

   - This structure provides better organization and accessibility for tabular data, making it easier for screen readers and search engines to understand the table's content.

2. How Does Structuring a Table with `thead`, `tbody`, and `tfoot` Elements Benefit Accessibility and User Experience?

   - Accessibility: Structuring a table with these elements helps screen readers and assistive technologies interpret the table's content correctly. Users with visual impairments can navigate through the table more efficiently, understanding which rows contain headers, data, and footers.

   - Semantics: Proper use of `thead`, `tbody`, and `tfoot` elements adds semantic meaning to your table, making it more understandable for both humans and machines. This can improve the overall accessibility of your web page.

   - User Experience: A well-structured table enhances the user experience by providing a clear separation of table parts. It allows users to identify column headers, locate specific data, and understand the summary or totals presented in the footer.

   - SEO (Search Engine Optimization): Search engines may use the structured content of a table to better index and understand the information on your webpage. This can potentially improve your site's visibility in search engine results.

   - In summary, using `thead`, `tbody`, and `tfoot` elements not only improves accessibility but also contributes to a more organized and semantically meaningful presentation of tabular data on your website.
