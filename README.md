# [Less](http://lesscss.org/) + [Polymer](http://www.polymer-project.org/)

![Less + Polymer](https://cloud.githubusercontent.com/assets/398893/3542417/b6c0e0ae-0856-11e4-97e4-eca788ad9729.jpg)

> A demo of interoperability between [Less](http://lesscss.org/) and [Polymer](http://www.polymer-project.org/).

## Getting started

In order to run it locally you'll need to fetch some dependencies using [npm](https://www.npmjs.org/).

* Install [Bower](http://bower.io/):

    ```sh
    $ [sudo] npm install -g bower
    ```

* Install [Less](http://lesscss.org//):

    ```sh
    $ [sudo] npm install -g less
    ```

* Install local dependencies:

    ```sh
    $ bower install
    ```

* Invoke the compiler to output the CSS file:

    ```sh
    $ lessc src/my-element.less > src/my-element.css
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/webcomponents/less-interop/releases).

## License

[MIT License](http://webcomponentsorg.mit-license.org/) © WebComponents.org
