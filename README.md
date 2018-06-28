## RCSS Bootstrap utilities

A rewrite for [Bootstrap 4 utilities](https://getbootstrap.com/docs/4.1/)  with RSCSS helpers conventions. 

### Example
```
.mt-0 becomes ._mt-0
```

### To build
```bash
$ npm run compile-css
```
After that, you can copy and use css/bootstrap-utilities.css

### Spacing
It differs from bootstraps utilities in spacing only. Instead of the sizes being from 0 to 5 it becomes from 0 to 9. The sizes are multiples of 8 for both margins and paddings.
