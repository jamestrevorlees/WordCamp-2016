- Minify and compress CSS using online tools
- Minify and compress JS using online tools
- wp_enqueue_script needs async and to be by `</body>`. Use https://wordpress.org/plugins/async-javascript/? Just add http://scottnelle.com/756/async-defer-enqueued-wordpress-scripts/ snippet in theme?
- what does https://wordpress.org/plugins/w3-total-cache/ do? All The Things?
- https://wordpress.org/plugins/above-the-fold-optimization/
- https://github.com/addyosmani/critical-path-css-tools
- https://aarontgrogg.com/blog/2016/01/13/how-to-add-critical-css-to-a-wordpress-site/
- https://gomakethings.com/inlining-critical-css-for-better-web-performance/
- remove jQuery?
- https://github.com/CTFEDs/ctfeds.org/blob/gh-pages/open-design-2015-checklist.md#tools

## Images

- Optimise your images and use as few as possible.
- Use the best format for your image: SVGs; JPGs (for photos, images with many colours); PNGs (for images with fewer colours); GIFs (for animations).
- Use the `picture` element and `srcset` to provide the image most suitable for the user's device. You can use [Picturefill](http://scottjehl.github.io/picturefill/) to enable support for `picture` in browsers that don't support it yet.