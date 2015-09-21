ness-github-api
============

`ness-github-api` is Polymer element for GitHub ajax call.

You should specifiy a `query` and a type of `sort` is optional.

## Demo

[Check it live!](http://www.baptistecarlier.com/bower_components/)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install BapNesS/ness-github-api --save
```

Or [download as ZIP](https://github.com/BapNesS/ness-github-api/archive/master.zip).

## Usage

1. Import polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>
    ```

2. Import custom element:

    ```html
    <link rel="import" href="bower_components/ness-github-api/ness-github-api.html">
    ```

3. Start using it! Example :
    ```html
    <ness-github-api
        items="{{items}}"
        sort="updated"
        query="user:BapNesS ness">
    </ness-github-api>
    ```

## History

For detailed changelog, check [Releases](https://github.com/BapNesS/ness-github-api/releases).
