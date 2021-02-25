# PhotoEffectsApp
 
H E L L O  V I S I T E R !!!

This useful app is coded with Pure Javascipt, CSS and HTML.

You can see these codes in script.js :

for (let i = 0; i < data.length; i += 4) {
    const grey = data[i] * 0.21 + data[i + 1] * 0.71 + data[i + 2] * 0.07;
    data[i] = grey + 95;
    data[i + 1] = grey + 58;
    data[i + 2] = grey;
  }

This for loop means data changes every 4 pixels that you can find with console.log for all data(pixels). 
**I assume that you already know "the picture consists of lots of pixels.