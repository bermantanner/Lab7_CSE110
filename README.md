Tanner Berman
1. I think within a github action that runs whenever code is pushed because you get feedback right awway without developers needing to remember to test all of the time. This also prevents merging if a test fails. 
2. No, that's what unit tests are for.
3. Lighthouse does a full page load like a user would and simulates network and CPU throttling. It tests the page performance and accessibility. Snapshot mode checks the current DOM in its exact state without reloading the page. This is best for testing components, states, pages, that are already loaded.
4. how to improve
    1. Preload largest image (says Largest Conteful Paint image, or LCP element), which in this case is the wolf backpack.
    2. Properly sizew images, it says serve images that are appropriately sized to save cellular data and improve load time
    3. Preconnect to required origins, which in our case in fakestoreapi.com






