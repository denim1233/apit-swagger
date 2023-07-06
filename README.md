change the path in 
        dev-helpers/dev-helper-initializer.js

        then change the path in 

    const ui = SwaggerUIBundle({
    url: "./apit.test.json",
    dom_id: "#swagger-ui",
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIStandalonePreset
    ],
    plugins: [
      SwaggerUIBundle.plugins.DownloadUrl
    ],
    // requestSnippetsEnabled: true,
    layout: "StandaloneLayout"
  })

the file of apit.test.json
is the content of api documentation

this is an react js
