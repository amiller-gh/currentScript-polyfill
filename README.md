# document.currentScript Polyfill

#### An exceptionally slim (~310b minified) polyfill for document.currentScript in IE9-IE11

This polyfill may not adhere strictly to spec when called in async code or in a callback. In these situations the spec calls for document.currentScript to return null. However, for the grand majority of your document.currentScript needs, this polyfill will do the job!
