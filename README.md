# &lt;camera&gt;

Web Component wrapper for getUserMedia API using Polymer

> Maintained by [Eduardo Lundgren](https://github.com/eduardolundgren).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="lib/polymer.min.js"></script>
	```

2. Import Custom Element:

	```html
	<link rel="import" href="src/camera.html">
	```

3. Start using it!

	```html
	<video is="camera"></video>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`audio`    | `true`, `false`           | `false`             | Capture audio using the device's local microphone


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.1.0 August 20, 2013
	* Initial development release
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[MIT License](http://opensource.org/licenses/MIT)