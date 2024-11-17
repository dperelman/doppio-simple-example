# doppio-simple-example

[doppio](https://github.com/plasma-umass/doppio/tree/master) is a JVM
that can run inside a browser. Unfortunately, the last commit was 3 years ago,
meaning it can be difficult to get running. There is an
[official demo](https://plasma-umass.org/doppio-demo/) that shows off
the full features, but is complicated enough that it is not
straightforward to modify. The documentation includes a simple example
[`simple.html`](https://github.com/plasma-umass/doppio/blob/master/docs/examples/simple.html),
but I had difficulty getting it to work, so I created this repository
showing a modified version of it functioning.

In order to avoid having to build anything myself, given that I was
having trouble getting the build to work, I grabbed the already built
files from the official demo:
 * [`doppio.js`](https://plasma-umass.org/doppio-demo/js/doppio.js)
 * [`browserfs.min.js`](https://plasma-umass.org/doppio-demo/js/browserfs.min.js)
 * [`doppio_home.zip`](https://plasma-umass.org/doppio-demo/doppio_home.zip)

They are included in this repository.

Note that doppio will take several seconds to load. Once it has, it will
display the message
> DoppioJVM now booted!
