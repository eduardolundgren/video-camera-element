# &lt;video-camera&gt;

Web Component wrapper for [getUserMedia API](http://dev.w3.org/2011/webrtc/editor/getusermedia.html) using Polymer.

## Demo

![Camera Element](http://f.cl.ly/items/3U3E2w0n3q0i3Y403s1Y/camera-element.gif)

> [Check it live](http://eduardolundgren.github.io/video-camera).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="src/video-camera.html">
    ```

3. Start using it!

    ```html
    <video is="video-camera"></video>
    ```

## Options

Attribute  | Options                                                                                     | Default | Description
---        | ---                                                                                         | ---     | ---
`audio`    | `true`                                                                                      | `false` | Capture audio using the device's local microphone
`filter`   | `blur`, `brightness`, `contrast`, `hue-rotate`, `saturate`, `grayscale`, `sepia`, `invert`  | None    | Apply filter effects

> See [getUserMedia API spec](http://dev.w3.org/2011/webrtc/editor/getusermedia.html).

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* [v0.1.2](https://github.com/eduardolundgren/google-maps/releases/tag/0.1.2) September 18, 2013
	* Rename element from `<camera>` to `<video-camera>`
* [v0.1.1](https://github.com/eduardolundgren/video-camera/releases/tag/0.1.1) August 21, 2013
    * Add filter effects
* [v0.1.0](https://github.com/eduardolundgren/video-camera/releases/tag/0.1.0) August 20, 2013
    * Initial development release
* v0.0.1 August 19, 2013
    * Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)