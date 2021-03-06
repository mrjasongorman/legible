# Legible CSS
HTML was created as a document format, a way for content to be written and consumed by others, however these days that content is hard to consume and read. Legible aims to fix that, by focusing on content and making it easy to consume on any device.

## Size
The aim is to be as small as possible with only small adjustments from sensible browser defaults. The framework should be included in one of two ways, either by `<link>` tag, or by simply copying everything into a single `<style>` tag.

|Type|Size|
|---|---|
|Normal|1.7 kb|
|Minified|1.4 kb|
|Gzip|638 bytes|
|Brotli|504 bytes|

Minified via `cat legible.css | tr -d " \t\n\r" > legible.min.css`
