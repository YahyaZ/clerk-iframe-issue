An issue I'm having running clerk in an iframe.

Essentially:

run `npm run dev`

If you open up `localhost:3000` you should see in the network tab that the example hello query works fine.

However, open up `index.html` in your browser. It will open up an iframe, and if you check the network requests there. It gets caught up in some clerk middleware.