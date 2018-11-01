---
title: Dart Tools for the Web
short-title: Tools
description: The tools that support web development using Dart.
show_breadcrumbs: false
---

This page lists specialized tools for developing web apps.
For information about general tools for Dart apps, see
[Dart Tools.]({{site.dartlang}}/tools)

## Recommended IDE {#ides}

If you don't already have a favorite IDE,
we recommend WebStorm, which comes with Dart support.

<a href="/tools/webstorm">
<img src="{% asset webstorm.svg @path %}" alt="WebStorm icon" width="48"><br>
<b>WebStorm</b>
</a>

See [Dart Tools]({{site.dartlang}}/tools#ides) for a list of other IDEs.

## SDK

Although [DartPad][]{: target="_blank"} is a great way to experiment with
Dart code, once you're ready to develop a web app, you need to
[install the Dart SDK.](/tools/sdk)

## Command-line tools

In addition to the [other Dart tools]({{site.dartlang}}/tools)
included in the SDK, the following tools
offer specialized support for web programming.

[webdev](/tools/webdev)
: A command line interface (CLI) for Dart web app development,
  including building and serving web apps.
{% comment %}
PENDING: say something about IDEs using webdev?
{% endcomment %}

[dart2js](/tools/dart2js)
: The original Dart-to-JavaScript compiler, with tree shaking.
  IDEs and the webdev CLI use dart2js when building web apps for deployment.

[dartdevc](/tools/dartdevc)
: The Dart dev compiler, a modular Dart-to-JavaScript compiler.
  IDEs and the webdev CLI use dartdevc when running a development server.

[build_runner]({{site.dartlang}}/tools/build_runner)
: A build package that's used behind the scenes by the webdev CLI.
  Also useful for [testing](/tools/webdev#test).

[DartPad]: {{site.custom.dartpad.direct-link}}
