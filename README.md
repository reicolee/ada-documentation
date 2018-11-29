# The Beginner Guide to Web Accessibility

## Modal

## Images

## Carousels
- use unordered list to structure your carousels
- use ```aria-live="polite" ``` in the carousels wrapper. This allows the screen readers to pronounce updates to the user if he / she is not doing anything

``` 
<div role="region" aria-label="XXX Carousels" aria-live="polite">
  <ul>
    <li></li>
    <li></li>
  </ul>
</div> 

``` 

## Forms
- Associate labels with the form input fields for both **normal** and **error label** with aria-describedby
- 

## HTML Semantics

## Datepicker
