# gulp-rollup

## Example

```javascript
import gulp from 'gulp';
import rollup from 'gulp-rollup';

gulp.task('foo', () => {
  rollup.src(...sources)
    .bundle({ ...options })
    .pipe(...)  // some gulp plugins
    .pipe(gulp.dest);
});

```

## TODO

- [ ] Loading sources using globs
- [ ] Bundling with handy options
- [ ] Returning a vinyl
- [ ] Supporting the sourcemaps with `sourcemap.init({ loadMaps: true })`
