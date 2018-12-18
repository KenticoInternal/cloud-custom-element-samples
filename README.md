# cloud-custom-element-samples
Collection of the simple Kentico Cloud custom elements used for quick testing and further development.

## How to run the custom element locally
1. Start your local draft-client 
2. npm run build-custom-element
3. Create your custom element in the UI and paste custom element url

## How to run the custom element on some hosted enviroment
1. Create your custom element in the UI and paste custom element url with appended query string

```<yourElementUrl>?apiUrl=\<pathToHostedApp\>/js-api/custom-element.js```

## Custom element samples
1. Simple markdown element: [https://kentico.github.io/cloud-custom-element-samples/markdown.html](https://kentico.github.io/cloud-custom-element-samples/markdown.html)
2. RGB color picker: [https://kentico.github.io/cloud-custom-element-samples/color-picker.html](https://kentico.github.io/cloud-custom-element-samples/color-picker.html)

## How to create new sample custom element
1. Create html page and place your code there
2. Check the apiUrl query string and fetch the custom-element.js or fallback to localhost (see existing examples)
3. Update the elements list in this readme :)
