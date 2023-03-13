# Legible CSS
HTML was created as a document format, a way for content to be written and consumed by others, however these days that content is hard to consume and read. Legible aims to fix that, by focusing on HTML elements and content (no classes needed!) it makes it easy to consume your content on any device.

See a demo here: https://legible.jasongorman.uk

## Size
The aim is to be as small as possible with only small adjustments from sensible browser defaults. The framework should be included in one of two ways, either by `<link>` tag, or by simply copying everything into a single `<style>` tag.

|Type|Size|
|---|---|
|Normal|4.8 kb|
|Minified|3.9 kb|
|Gzip|1.5 kb|
|Brotli|1.2 kb|

Minified via `cat legible.css | tr -d " \t\n\r" > legible.min.css`
