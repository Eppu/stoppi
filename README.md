# Stoppi - A bus tracker for students in Tampere

> Stoppi is an interactive, real-time bus tracking application, directed towards new English speaking TAMK students and visitors. 

[![Website eetueskelinen.com](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://eetueskelinen.com/stoppi)


Stoppi was built using the <a href="https://developers.google.com/maps/documentation/javascript/overview" target="_blank">Google Maps JavaScript API</a>, and it uses a proxy of the Lissu API provided by the City of Tampere to find real-time data from buses around Tampere.

In the app, you can select which bus lines you are currently interested in. Those lines will then display on a map of the city in real time. There are also quick shortcuts for buses going to different campuses built with students in mind!

Stoppi is currently available as a web app that can be found <a href="https://eetueskelinen.com/stoppi">here</a>.

![](https://i.gyazo.com/da46b657e20226e2b3b4ec94da1f6aed.png)

## Installation

```sh
git clone https://github.com/Eppu/stoppi.git
```

<a href="https://developers.google.com/maps/documentation/javascript/get-api-key" target="_blank">Get an API key</a> for the Google Maps Javascript API. Then insert your API key at the bottom of `index.html` like this:
```sh
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY_HERE" type="text/javascript"></script>
```



## Meta

Eetu Eskelinen – [Twitter](https://twitter.com/edwardtehgreat) – [LinkedIn](https://linkedin.com/in/eetueskelinen) – [eetueskelinen.com](eetueskelinen.com)


## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
