# LightningPagination
Lightning component to implement Pagination in lightning.
This article showcases how to implement Pagination in Lightning component.

In Lightning, it is possible to implement pagination in the client-side rather than always hitting the server-side logic on click of page number button. This helps to improve the UI performance and gives a better fluid design mechanism that is very light weight and responsive.
The most important attribute to focus for pagination in lightning is -
records.slice(<starting index of record for current page>, <ending index of record for current page>)

Eg : records.slice((pageNumber-1)*recordsPerPage, pageNumber*recordsPerPage);

The "slice" attribute divides all the records into a given slot.
