# BB4-Accordion-with-Scrollspy
## Accordion with Scrollspy

This example is based on the content of <a href="https://www.w3schools.com">W3Schools</a>

<div id="collapseFour" class="collapse" data-parent="#accordion" >

The body of the archordion content item example
~~~html
<div id="collapseFour" class="collapse" data-parent="#accordion" >
   <div class="card-body">
        Content for Item #X.
   </div>
</div>
~~~

if you want to show an item as soon as it opens, add **show**
~~~html
<div id="collapseFour" class="collapse show" data-parent="#accordion" >
~~~

if you want an item to not be related to the others, remove this: **data-parent="#accordion"**
~~~html
<div id="collapseFour" class="collapse">
~~~
