#BEST PRACTICES

** perfomance is always a never ending concepts.
** choose your time wisely. 

- minimize script and style files
- can some of the styles like animation be achieved natively ? (meaning can we get rid of the unecessary libraries)
- combine files
- unless its crucial move script tags to the bottom right before the end of the body tag
- caching
- gzipping assets on the server so that page loads faster and users can complete their goals as quickly as possible
- pre fetching 

POSSIBLE STYLE LOADING
- you can create a style tag directly on the html for when a user sees the first part of the page right away. So you can load the rest of the style sheets right after the page loads. 

LOAD SCRIPTS
- load scripts asynchronously
- defer loading of scripts
- minimize DOM manipulations
- Avoid long running javascript
