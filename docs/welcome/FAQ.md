# FAQ

<center>
  <img class="header-img" src="assets/header-faq.png" alt="Frequently Asked Question Header Image" >
  <p class="img-credit"> Image Credit: <a href="https://thenounproject.com/creator/purpleiconn/" target="_blank" title="Purple iconn">Purple iconn</a> | <a href='mailto:info@ml5js.org'>Contribute ♥️</a> </p>
</center>

## Can I always use ml5.js in p5 web editor?

Mostly.

A number of the ml5 sketches don't currently work in the [p5 web editor](https://editor.p5js.org/) due to some of the ways that the editor handles data files and some of the network communication regarding making requests to external data (e.g. the big model files that allow ml5.js to run things like image detection, etc).

There are lots of developments in the p5 web editor as well as in ml5 to make sure these environments all play nicely together. If something doesn't work in the web editor, the best thing to do is to try and run things locally if possible. See [running you sketch with a local web server tutorial](/?id=try-ml5js-locally-3).

Thanks!

## Can I use ml5.js with node.js?

No. Not at the moment.

ml5.js uses TensorFlow.js which uses the browser's GPU to run all the calculations. As a result, all of the ml5.js functionality is based around using the browser GPU. We hope to have ml5.js run in node-js sometime in the near future (especially now that [node support for TensorFlow is a thing](https://www.tensorflow.org/js/guide/nodejs) but the current ml5 setup does not support node.js. We hope to support this in the future.

[For more discussion about node and ml5.js, visit this issue thread.](https://github.com/ml5js/ml5-library/issues/377)

<br>
