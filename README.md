# cloud-custom-element-samples
Collection of the simple Kentico Cloud custom elements used for quick testing and further development.

## How to run the custom element locally
1. Open your draft-client and run ```npm run build-custom-element```
2. Start your draft-client local server ```npm run start-dev```
3. Create your custom element in the UI and paste custom element url

## How to run the custom element on some hosted enviroment
1. Create your custom element in the UI and paste custom element url with appended query string

```<yourElementUrl>?apiUrl=\<pathToHostedApp\>/js-api/custom-element.js```

## Custom element samples
1. Simple markdown element: [https://kenticointernal.github.io/cloud-custom-element-samples/markdown.html](https://kenticointernal.github.io/cloud-custom-element-samples/markdown.html)
2. RGB color picker: [https://kenticointernal.github.io/cloud-custom-element-samples/color-picker.html](https://kenticointernal.github.io/cloud-custom-element-samples/color-picker.html)
3. API diagnostics element: [https://kenticointernal.github.io/cloud-custom-element-samples/api-diag.html](https://kenticointernal.github.io/cloud-custom-element-samples/api-diag.html)

## How to create a new sample custom element
1. Create html page and place your code there
2. Check the apiUrl query string and fetch the custom-element.js or fallback to localhost (see existing examples)
3. Update the elements list in this readme :)
