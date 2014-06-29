# &lt;video-camera-element&gt;

> Web Component wrapper for [getUserMedia API](http://dev.w3.org/2011/webrtc/editor/getusermedia.html) using Polymer.

## Demo

![Camera Element](http://f.cl.ly/items/3U3E2w0n3q0i3Y403s1Y/camera-element.gif)

[Check it live!](http://eduardolundgren.github.io/video-camera-element)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install video-camera-element --save
```

Or [download as ZIP](https://github.com/eduardolundgren/video-camera-element/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/video-camera-element/dist/video-camera.html">
    ```

3. Start using it!

    ```html
    <video is="video-camera" autoplay></video>
    ```

## Options

Attribute  | Options     | Default      | Description
---        | ---         | ---          | ---
`audio`    | `true`, `false` | `false`  | Capture audio using the device's local microphone
`filter`   | `blur`, `brightness`, `contrast`, `hue-rotate`, `saturate`, `grayscale`, `sepia`, `invert`  | None    | Apply CSS filter effects

> See [getUserMedia API spec](http://dev.w3.org/2011/webrtc/editor/getusermedia.html).

## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/eduardolundgren/video-camera-element/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
