# TESTE
Just a test
<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>Teste</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[97]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span> <span class="c1"># linear algebra</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span> <span class="c1"># data processing, CSV file I/O (e.g. pd.read_csv)</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">math</span>
<span class="kn">import</span> <span class="nn">warnings</span>
<span class="n">warnings</span><span class="o">.</span><span class="n">filterwarnings</span><span class="p">(</span><span class="s1">&#39;ignore&#39;</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">style</span><span class="o">.</span><span class="n">use</span><span class="p">(</span><span class="s1">&#39;ggplot&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;BankChurners.csv&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[6]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>CLIENTNUM</th>
      <th>Attrition_Flag</th>
      <th>Customer_Age</th>
      <th>Gender</th>
      <th>Dependent_count</th>
      <th>Education_Level</th>
      <th>Marital_Status</th>
      <th>Income_Category</th>
      <th>Card_Category</th>
      <th>Months_on_book</th>
      <th>...</th>
      <th>Credit_Limit</th>
      <th>Total_Revolving_Bal</th>
      <th>Avg_Open_To_Buy</th>
      <th>Total_Amt_Chng_Q4_Q1</th>
      <th>Total_Trans_Amt</th>
      <th>Total_Trans_Ct</th>
      <th>Total_Ct_Chng_Q4_Q1</th>
      <th>Avg_Utilization_Ratio</th>
      <th>Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1</th>
      <th>Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>768805383</td>
      <td>Existing Customer</td>
      <td>45</td>
      <td>M</td>
      <td>3</td>
      <td>High School</td>
      <td>Married</td>
      <td>$60K - $80K</td>
      <td>Blue</td>
      <td>39</td>
      <td>...</td>
      <td>12691.0</td>
      <td>777</td>
      <td>11914.0</td>
      <td>1.335</td>
      <td>1144</td>
      <td>42</td>
      <td>1.625</td>
      <td>0.061</td>
      <td>0.000093</td>
      <td>0.99991</td>
    </tr>
    <tr>
      <th>1</th>
      <td>818770008</td>
      <td>Existing Customer</td>
      <td>49</td>
      <td>F</td>
      <td>5</td>
      <td>Graduate</td>
      <td>Single</td>
      <td>Less than $40K</td>
      <td>Blue</td>
      <td>44</td>
      <td>...</td>
      <td>8256.0</td>
      <td>864</td>
      <td>7392.0</td>
      <td>1.541</td>
      <td>1291</td>
      <td>33</td>
      <td>3.714</td>
      <td>0.105</td>
      <td>0.000057</td>
      <td>0.99994</td>
    </tr>
    <tr>
      <th>2</th>
      <td>713982108</td>
      <td>Existing Customer</td>
      <td>51</td>
      <td>M</td>
      <td>3</td>
      <td>Graduate</td>
      <td>Married</td>
      <td>$80K - $120K</td>
      <td>Blue</td>
      <td>36</td>
      <td>...</td>
      <td>3418.0</td>
      <td>0</td>
      <td>3418.0</td>
      <td>2.594</td>
      <td>1887</td>
      <td>20</td>
      <td>2.333</td>
      <td>0.000</td>
      <td>0.000021</td>
      <td>0.99998</td>
    </tr>
    <tr>
      <th>3</th>
      <td>769911858</td>
      <td>Existing Customer</td>
      <td>40</td>
      <td>F</td>
      <td>4</td>
      <td>High School</td>
      <td>Unknown</td>
      <td>Less than $40K</td>
      <td>Blue</td>
      <td>34</td>
      <td>...</td>
      <td>3313.0</td>
      <td>2517</td>
      <td>796.0</td>
      <td>1.405</td>
      <td>1171</td>
      <td>20</td>
      <td>2.333</td>
      <td>0.760</td>
      <td>0.000134</td>
      <td>0.99987</td>
    </tr>
    <tr>
      <th>4</th>
      <td>709106358</td>
      <td>Existing Customer</td>
      <td>40</td>
      <td>M</td>
      <td>3</td>
      <td>Uneducated</td>
      <td>Married</td>
      <td>$60K - $80K</td>
      <td>Blue</td>
      <td>21</td>
      <td>...</td>
      <td>4716.0</td>
      <td>0</td>
      <td>4716.0</td>
      <td>2.175</td>
      <td>816</td>
      <td>28</td>
      <td>2.500</td>
      <td>0.000</td>
      <td>0.000022</td>
      <td>0.99998</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 23 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Podemos ver que temos várias colunas que nada agregam a analise, vamos efetuar a exclusão das mesmas.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[7]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">&#39;CLIENTNUM&#39;</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span> <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span> 
<span class="n">df</span><span class="o">.</span><span class="n">drop</span><span class="p">([</span><span class="s1">&#39;Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1&#39;</span><span class="p">],</span> 
          <span class="n">inplace</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">)</span> 

<span class="n">display</span><span class="p">(</span><span class="n">df</span><span class="o">.</span><span class="n">shape</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>(10127, 20)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[9]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[9]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Attrition_Flag</th>
      <th>Customer_Age</th>
      <th>Gender</th>
      <th>Dependent_count</th>
      <th>Education_Level</th>
      <th>Marital_Status</th>
      <th>Income_Category</th>
      <th>Card_Category</th>
      <th>Months_on_book</th>
      <th>Total_Relationship_Count</th>
      <th>Months_Inactive_12_mon</th>
      <th>Contacts_Count_12_mon</th>
      <th>Credit_Limit</th>
      <th>Total_Revolving_Bal</th>
      <th>Avg_Open_To_Buy</th>
      <th>Total_Amt_Chng_Q4_Q1</th>
      <th>Total_Trans_Amt</th>
      <th>Total_Trans_Ct</th>
      <th>Total_Ct_Chng_Q4_Q1</th>
      <th>Avg_Utilization_Ratio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Existing Customer</td>
      <td>45</td>
      <td>M</td>
      <td>3</td>
      <td>High School</td>
      <td>Married</td>
      <td>$60K - $80K</td>
      <td>Blue</td>
      <td>39</td>
      <td>5</td>
      <td>1</td>
      <td>3</td>
      <td>12691.0</td>
      <td>777</td>
      <td>11914.0</td>
      <td>1.335</td>
      <td>1144</td>
      <td>42</td>
      <td>1.625</td>
      <td>0.061</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Existing Customer</td>
      <td>49</td>
      <td>F</td>
      <td>5</td>
      <td>Graduate</td>
      <td>Single</td>
      <td>Less than $40K</td>
      <td>Blue</td>
      <td>44</td>
      <td>6</td>
      <td>1</td>
      <td>2</td>
      <td>8256.0</td>
      <td>864</td>
      <td>7392.0</td>
      <td>1.541</td>
      <td>1291</td>
      <td>33</td>
      <td>3.714</td>
      <td>0.105</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Existing Customer</td>
      <td>51</td>
      <td>M</td>
      <td>3</td>
      <td>Graduate</td>
      <td>Married</td>
      <td>$80K - $120K</td>
      <td>Blue</td>
      <td>36</td>
      <td>4</td>
      <td>1</td>
      <td>0</td>
      <td>3418.0</td>
      <td>0</td>
      <td>3418.0</td>
      <td>2.594</td>
      <td>1887</td>
      <td>20</td>
      <td>2.333</td>
      <td>0.000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Existing Customer</td>
      <td>40</td>
      <td>F</td>
      <td>4</td>
      <td>High School</td>
      <td>Unknown</td>
      <td>Less than $40K</td>
      <td>Blue</td>
      <td>34</td>
      <td>3</td>
      <td>4</td>
      <td>1</td>
      <td>3313.0</td>
      <td>2517</td>
      <td>796.0</td>
      <td>1.405</td>
      <td>1171</td>
      <td>20</td>
      <td>2.333</td>
      <td>0.760</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Existing Customer</td>
      <td>40</td>
      <td>M</td>
      <td>3</td>
      <td>Uneducated</td>
      <td>Married</td>
      <td>$60K - $80K</td>
      <td>Blue</td>
      <td>21</td>
      <td>5</td>
      <td>1</td>
      <td>0</td>
      <td>4716.0</td>
      <td>0</td>
      <td>4716.0</td>
      <td>2.175</td>
      <td>816</td>
      <td>28</td>
      <td>2.500</td>
      <td>0.000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[10]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">info</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>&lt;class &#39;pandas.core.frame.DataFrame&#39;&gt;
RangeIndex: 10127 entries, 0 to 10126
Data columns (total 20 columns):
 #   Column                    Non-Null Count  Dtype  
---  ------                    --------------  -----  
 0   Attrition_Flag            10127 non-null  object 
 1   Customer_Age              10127 non-null  int64  
 2   Gender                    10127 non-null  object 
 3   Dependent_count           10127 non-null  int64  
 4   Education_Level           10127 non-null  object 
 5   Marital_Status            10127 non-null  object 
 6   Income_Category           10127 non-null  object 
 7   Card_Category             10127 non-null  object 
 8   Months_on_book            10127 non-null  int64  
 9   Total_Relationship_Count  10127 non-null  int64  
 10  Months_Inactive_12_mon    10127 non-null  int64  
 11  Contacts_Count_12_mon     10127 non-null  int64  
 12  Credit_Limit              10127 non-null  float64
 13  Total_Revolving_Bal       10127 non-null  int64  
 14  Avg_Open_To_Buy           10127 non-null  float64
 15  Total_Amt_Chng_Q4_Q1      10127 non-null  float64
 16  Total_Trans_Amt           10127 non-null  int64  
 17  Total_Trans_Ct            10127 non-null  int64  
 18  Total_Ct_Chng_Q4_Q1       10127 non-null  float64
 19  Avg_Utilization_Ratio     10127 non-null  float64
dtypes: float64(5), int64(9), object(6)
memory usage: 1.5+ MB
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Vemos que não temos dados faltantes, por tanto, não vamos necessitar de uma tratativa com relação a valores nulos.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[105]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Definindo as colunas que irei analisar.</span>
<span class="n">colunas</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Attrition_Flag&#39;</span><span class="p">,</span> <span class="s1">&#39;Gender&#39;</span><span class="p">,</span> <span class="s1">&#39;Education_Level&#39;</span><span class="p">,</span> <span class="s1">&#39;Marital_Status&#39;</span><span class="p">,</span> <span class="s1">&#39;Income_Category&#39;</span><span class="p">,</span> <span class="s1">&#39;Card_Category&#39;</span><span class="p">]</span>

<span class="c1">#Criando a função</span>
<span class="k">def</span> <span class="nf">pltCountplot</span><span class="p">(</span><span class="n">colunas</span><span class="p">):</span>
    <span class="n">fig</span><span class="p">,</span> <span class="n">axis</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">colunas</span><span class="p">)</span> <span class="o">//</span> <span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">12</span><span class="p">))</span>  

    <span class="n">index</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">colunas</span><span class="p">)</span> <span class="o">//</span> <span class="mi">3</span><span class="p">):</span>
        <span class="k">for</span> <span class="n">j</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">3</span><span class="p">):</span>
            
            <span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">colunas</span><span class="p">[</span><span class="n">index</span><span class="p">],</span> <span class="n">data</span><span class="o">=</span><span class="n">df</span><span class="p">,</span> <span class="n">ax</span><span class="o">=</span><span class="n">axis</span><span class="p">[</span><span class="n">i</span><span class="p">][</span><span class="n">j</span><span class="p">])</span> <span class="c1">#Sempre que houver um incremento a coluna será</span>
            <span class="c1">#alterada</span>
            <span class="k">if</span> <span class="n">colunas</span><span class="p">[</span><span class="n">index</span><span class="p">]</span> <span class="ow">in</span> <span class="p">[</span><span class="s1">&#39;Education_Level&#39;</span><span class="p">,</span> <span class="s1">&#39;Income_Category&#39;</span><span class="p">]:</span> <span class="c1">#Como essas colunas tem mais dados</span>
                <span class="k">for</span> <span class="n">item</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">():</span> <span class="c1">#sempre que elas aparecerem os seus valores em x serão rotacionados</span>
                    <span class="n">item</span><span class="o">.</span><span class="n">set_rotation</span><span class="p">(</span><span class="mi">15</span><span class="p">)</span> <span class="c1">#em 15º</span>
                
            <span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
                <span class="n">height</span> <span class="o">=</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span>
                <span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span><span class="o">+</span><span class="n">p</span><span class="o">.</span><span class="n">get_width</span><span class="p">()</span><span class="o">/</span><span class="mf">2.</span><span class="p">,</span>
                        <span class="n">height</span> <span class="o">+</span> <span class="mi">3</span><span class="p">,</span>
                        <span class="s1">&#39;</span><span class="si">{:1.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">height</span><span class="o">/</span><span class="nb">len</span><span class="p">(</span><span class="n">df</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">),</span>
                        <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;center&quot;</span><span class="p">)</span> 
            <span class="n">index</span> <span class="o">+=</span> <span class="mi">1</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[106]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pltCountplot</span><span class="p">(</span><span class="n">colunas</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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SRgMBgwGA4mJiY/kfEREcpKKUiIiIiIikqe5uLhQr149y+NatWpx4cIFIiIicHBwwMfHB4BevXrxww8/AGQ7ll3J0VG80b8fL3TvxsmTJ2n0fH2+nP8RG5YtpWXTprT29cXFBlp5PYUxMpyTO3+h74u9MEaGUzGfgWZ1atGpfTvatWxJ8pVY2tV4msTjkUwcPIBhgwbi17oVG79ezdAuHTFGhmOMDOe34EBuxsdR1mDCGBlOy7retG/Vkt92/ErtYkUwRoaTHJ15DSsRkbxCC52LiIiIiMhjIy0tja+//hpfX1+ioqIoWbKkJebq6kpaWhrx8fHZjmX17nVhYWEZHnukJvFq0kVe9XQD3G5t3PcjAN6lCt56fC6Cv94bb2nzug0cnzkOgGZAM48CtwLXL3A64B0ASgEziqevQ5XMjeUfcfz/P7IBevF/z+ED+Lg7AAmW9h7DJxJ1/sI9zyXRoUiWztnajEYjYWFnczsNEXmEVJQSEREREZHHxowZMyhYsCAvvfQSP/74Y67l4e3tneGxMTKcvDgmycnJiZJP17jnPofOXLJSNg/GycmJmtUr5nYaIvKA7iza34uKUiIiIiIi8ljw9/fnzJkzfPzxx9jY2ODh4cGFC/83CiguLg4bGxtcXFyyHRMREevRmlIiIiIiIpLnffjhh0RERLBo0SLs7W9NZ6tevTpJSUkcOHAAgDVr1tCmTZuHiomIiPVopJSIiIiIiORpf/31F5988gnly5e33L2udOnSLFq0iICAAKZMmUJycjKlSpVi9uzZANjY2GQrJiIi1qOilIiIiIiI5GlPPfUUx44du2usTp06BAUF5WhMRESsQ9P3RERERERERETE6lSUEhERERERERERq1NRSkRERERERERErE5FKRERERERERERsToVpURERERERERExOpUlBIREREREREREauzs9aBfH19sbe3x8HBAYDRo0fTqFEjDh48yOTJk0lOTqZUqVLMnj0bNzc3gGzHREREREREREQkb7PqSKn58+cTGBhIYGAgjRo1Ii0tjTFjxjB58mRCQkLw8fFhzpw5ANmOiYiIiIiIiIhI3per0/ciIiJwcHDAx8cHgF69evHDDz88VExERERERERERPI+q03fg1tT9sxmM97e3owaNYqoqChKlixpibu6upKWlkZ8fHy2Yy4uLlnOJywsLNvn4pGa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KYkDBw4AsGbNGtq0afNQMRERERERERERyfusMlLqr7/+4pNPPqF8+fL06tULgNKlS7No0SICAgKYMmUKycnJlCpVitmzZwNgY2OTrZiIiIiIiIiIiOR9VilKPfXUUxw7duyusTp16hAUFJSjMRERERERERERydusfvc9EZE7jR8/nvr16+Pn55dh+5dffkmbNm1o3749AQEBd20bGhpK69atadmyJUuXLrVs7927N506daJTp040bNiQoUOHAhASEkL79u3p3bs3V65cAeDs2bO8+eabj+bkRERERERE5K6sfvc9EZE7de3alZdeeomxY8datu3du5dt27bx7bffYm9vT2xsbKZ2JpOJ6dOns2LFCtzd3enevTu+vr5UqlSJ1atXW/Z74403aN68OQBfffUV33zzDVu3biU4OJiXX36ZuXPnqiglIiIiIiJiZRopJSK5rm7duhQuXDjDtq+//ppBgwZZbozg5uaWqV14eDjlypWjTJky2Nvb0759e7Zt25Zhn4SEBPbu3UuLFi0AMBgMpKSkkJSUhJ2dHQcOHKBo0aKUL1/+0ZyciIiIiIiI3JWKUiKSJ50+fZoDBw7Qo0cPXnrpJcLDwzPtEx0dTYkSJSyP3d3diY6OzrDPTz/9RP369XF0dARg8ODB9O3bl59//hk/Pz8WL15smdonIiIiIiIi1qPpeyKSJ5lMJq5evcq6des4fPgwb775Jtu2bcNgMDzQ8wQHB9OjRw/L4wYNGtCgQQMANm/eTOPGjTl9+jSfffYZzs7OTJw4kQIFCuTouYiIiIiIiEhmGiklInmSu7s7LVu2xGAwUKNGDWxsbCwLk9++z8WLFy2Po6OjcXd3tzyOi4vj8OHDNG3aNNPzJyYmsnHjRvr06cOCBQt4//338fb21l09c4m/vz++vr5UqVKF48ePW7afOnWKnj170rp1a3r27Mnp06cfOiYiIiIiInmDilIikie1aNGCffv2AbcKDDdv3qRIkSIZ9nnmmWc4ffo0586dIyUlhS1btuDr62uJh4SE0LRpUxwcHDI9//Lly3nllVfIly8fSUlJGAwGDAYDiYmJj/bE5K6aN2/OqlWrKFWqVIbtU6ZMoXfv3oSEhNC7d28mT5780DEREREREckbNH1P5AkQdSWBmGuPbzFl7ntTiAw/iPFqPPUbNOSFl/vTuEVrfvpgFi1atcEu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Xl64urrmcmYiIpIXqJ8QEZF7UT8hIpL7Hts1pQBOnDjBuHHjuHbtGs7Ozvj7+1OxYsXcTktERPII9RMiInIv6idERHLXY12UEhERERERERGRx9NjO31PREREREREREQeXypKiYiIiIiIiIiI1akoJSIiIiIiIiIiVqeilIiIiIiIiIiIWJ2KUrnE19eXNm3a0KlTJ8v/zp8/f882X3/9NStXrrznPj/99BPh4eGWx4cPH+att97KiZQz2LFjB7169aJVq1Z07dqVwYMHc+zYsWw915EjR/juu+9yOEPJjqtXr1KjRg3efffdDNs3btzIqVOnLI+z8p5t27YNf39/AM6fP8/atWuznVeVKlW4fv36XWPh4eH07duXFi1a0K1bN1555RV+++23bB3nYfMUkVv9W8OGDTGZTJZtGzdupEqVKnz11Ve5mJn8l935veu9997L7ZRE8oybN2/y559/5nYa/+pJvi/XiRMn2L59O/Bkn6fIvdjldgL/ZfPnz6dy5cpZ3v/FF1+87z4//fQT1atXp0aNGgA888wzfPDBB9nO8W527tzJxIkTWbRoEc888wxwq0hx6dIlqlSp8sDPd+TIEX755RfatWuXo3lmVWpqKnZ2+lMACA4OpmbNmmzZsoW3334be3t7ADZt2kSRIkWoUKECcP/3LDU1lebNm9O8eXMA/vnnH9auXUvPnj1zNN9jx44xePBgAgICaNSoEQBnz57lyJEj2Xq+R5VnVqWlpWEwGDAYDLlyfJGcUrx4cXbu3EmTJk2AW/8NqVatWi5nJf91D/q9S+RJZjabLd83fv31Vz777DP8/f0pU6ZMLmf2f9LS0rCxsXnivheZzWZu3ryJvb09ERERTJs2jd9//z3De5Lb+ZnNZmxs8v74lbS0NIDHItecZjabSUtLw9bWNrdTsTCZTBgMhgd+P3QlnsecOHGCfv36sXr1akqVKsXChQs5ceIEH330EQsWLODGjRuMHTuW33//nRkzZpCWlkZqaipDhgyhcOHCbN++nd27d7N+/Xr69u2Lh4cH/v7+bNy4kfPnz9OtWzd69erFr7/+SmJiIjNnzsTHxweAr776ii+++AInJyeaNGnCqlWr2LdvX6YcFy1axNChQy0FKQAvLy8AyzHS293+ODY2lrfeeovY2FgA6tevz5AhQ5g/fz4JCQl06tSJunXrMmnSJEJD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Cmaz2XJBWKtWLVatWmV5fjc3N86fP4+Li4tlNEavXr1wdnamffv2lkLIc889lym3u61NlO7MmTNs3LiRwoULU7hwYfbs2cOzzz6LnZ0dBw4coE2bNpZRQgcOHODVV19lx44d2NraWu6O3b17d06ePEm7du1o0qQJc+fOJTAwkBYtWjB06FCGDBnCgAEDMo0uyQl3rnVz++3rExMTLTNTrl69yvvvv0+lSpV44403qFixIufOnWPWrFmWOxYWKVKEggULsmfPHpo1a4aHhwc1a9Zk2bJlvPTSS1y8eJHg4GBq1qzJ8OHD6dOnDy1btqRIkSL3PLf09b/S72KWXjS7ceMGv//+O/v27WP//v0kJCRQp04d3njjDZKTkzl8+DCvv/469vb2dO3aleTkZL777jveeOMN/vrrLzZv3sz169cZOXIkV65cYcCAAfTr14+UlBQcHR3p27evZUS/2WymU6dO/5rj9evXuXTpEuXLl890x0Gz2YyLiwtPPfUU0dHRmEwmypUrx65du7h48SJms5k//viDsmXLMmvWLCIjI3F3d6dQoUJ4enqyZcsWLly4QLly5XB0dOTw4cOEh4fTq1cv3nnnHb755ht27txJ8+bNadCgQYZijLXc7W8k/XU4ceIEhw8fJioqips3b5KQkEBSUhK//vorvr6+uLm50ahRI8u6WUWKFGHJkiW8/PLLtGjRggsXLtCqVSuuXbtGhQoVqFmzJq+99honTpxg9uzZtG3b1rLW1+2Fn/Tj//rrrwA0adLEEktMTGT16tV899135M+fn3bt2tGtWzeqVq3KZ599RoMGDWjbti1wa8mTpUuX4uvry6hRoyw3sAFo1aoVq1evZvny5URGRjJnzhzmzJnD9u3bKVq0qGWaYVaoKCUWU6ZMye0URERERET+U9LvOvftt99att28eROA8+fPExQUxJtvvkm9evUscW9vb+zs7HBzcwNu3SH43Xff5Z9//qFVq1Z88MEHfPHFF5a7vaXfCatgwYIMGzaMYcOG3bXQdOcF9u1Fm9tHVVy+fJk5c+ZQvHhxnn76aWxtbdmzZw8jRozAx8eHdevWAbduglStWjW+/fZbTCYTp06dIn/+/Fy4cIG///7bshZtVFSUZSROiRIlKFasmOW4OVWQio2NZfHixbzzzjuZzs1kMhEYGIifnx/29vZ8//33nDp1iiFD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fPny0a5dO3bu3MkHH3yA0Wi0TDNNf49zuhh17tw5QkNDOXDgANeuXcPPz48uXbpYCnoxMTFs2rSJQoUKUbduXb7//nsaNmzIwIEDGThwII6OjrRr146jR4/SrFkzy/PWrFmTY8eOkZycTKNGjfj5559xdXXFyckJs9nMtWvXiI6Opl+/frRq1QoPD49MN1e6c3rk7WJiYpgyZQoXL17kmWeeoXv37vTu3Zt//vmHJk2aWAq+CQkJVKpUicTERAoUKICdnR2FCxcmNjYWT09PyyhBLy8vXF1dmTJlChEREVStWvWR3aRJRSkREREREZGHcOdojXz58nHlyhVOnz5NRESEZR2W4cOHW4oK6Z555hnmzp3L9evXuX79OrGxsaxevZqVK1fSo0cP7OzsWLFiBePGjePvv//m8OHDdOnShaZNm7J3715LoWPo0KGZ8jKZTBkuYtPXE+rTpw8NGzYkf/78nD9/HgcHBz7++GO2b99uucBOX1vo559/ZvTo0Vy6dImYmBgOHjxI2bJlSUpKYv/+/bRv355z586RmJjI999/T4sWLZg4cSIbN25k37599OjRg9q1a1um4f3bHb5zwp0jjdLS0li6dClffPEFfn5+2NraEhoaSo8ePfDz8yM0NNSyb6NGjXj//fcBKFu2LIGBgXTp0oV8+fJx7tw54NYdlY8fP86YMWOoVasWo0aNolSpUuTLlw+z2XzXgpTRaKR3794EBQVZ3qvGjRszd+5cS2GwTZs21KtXjzJlyjBgwABGjx5NqVKleP755y3TpEqXLp3h7nzly5cnPDyckydPUqZMGUqVKsWNGzfYv38/PXr04K233uLvv/+mcuXKFCpUKMde4/j4eBITEylXrlyGEYApKSmcOHGC5557jps3b2JjY0ODBg1YtmwZiYmJVKxYkfPnz5OUlETp0qX57bffiIyMpFatWrz33nscO3aMihUrWkYJpkufbubr60uDBg0sU0gfhfDwcGbNmkW5cuVo164d5cuX59dff7UUg55//nmaNWuGu7s7zZs3p2TJkpZpk7Nnz+aff/4hNDSUdu3a4e3tzbZt22jZsiVwayrrvn37OHLkCJ06dcLGxoZly5bh4+PDiBEj8PLysrxPqampfPnllxw4cICqVavy3HPPUa9ePcu6Z/v37+fgwYNUr17dcmOCzZs3U758eZYsWZLhnFxcXDhy5Ai1a9fG3d0dLy8vfvjhBypXrkz9+vXZvXs3VatWxc3NDXd3dzw9PTP8HVWqVIlKlSo9stccVJQSeSjffvstmzdv5rPPPrtr/MCBA0ycOJGQkBArZwb79u1jzJgxGTpbERF5smzcuJH169fz9ddf53YqIv8ZV65cISkpKcOt528fuZA+eqhs2bIcOXKE48ePU716dXbu3MnChQvp37+/ZRHzdFWqVMnwOC0tjTVr1jB27Fj69evHt99+S8eOHcmfPz8NGjQgISGB9u3bW9ZySZc+xSjdnUWauXPnUqVKlQzT+UqXLg2Ap6cnmzZton79+tSqVQuAgwcP8t133zF48GBq1qzJO++8w88//8zEiROpXr06X3zxBQcOHODy5cu0b9+eGzduALdGzowdO/ZBX9r7utft7KOiovj555+Ji4ujbdu2eHp6cuTIEbZt28ZPP/1EwYIF+fzzz5k/fz5wa2H327/Dp6+9dPnyZfr27ctvv/3GyJEjuXDhAkajkbfffpumTZsyefLkTCNY4N9Hejk5OXH69GmuXLlCkSJFSEtLo1ixYhQsWJD9+/fTpk0bPD09uXjxIu+88w758uWjRYsWbN26leeff5569epx+fJlfHx8mDt3LhUqVOCtt96iVKlSJCUl8eeff9KkSRMqVarEwIEDqVChguW4t9/5L6c4OjpSoECBDHduN5lM2NvbU6hQIf755x+MRiOurq6cPHmSggULkj9/fjw8PDh48CBRUVHUqlWL/PnzU7FiRctr//zzz1uOcfvnuEGDBtm6I+SDSkpKYsKECbzxxhu0bt3asj19FBiAl5cX586dY+bMmZZtX375Jfv372fYsGF06NCBpUuXcu7cOXr06IG/v79lOmNkZCR169bFaDRiMBjo2LEjHTt2zJBDYmIirVu3pmTJkjzzzDN069aNf/75h+HDhzN69Gh69OjBlClTOHPmDHXq1OHDDz/k7NmzvPjii2zdupW+ffsCt9Z/s7e3x87OjqeeeoqwsDBL4dzX15eEhASWLVvGzJkzcXV1tRS0a/4/9u48Pqbr/+P4a5JIhCQiQYSqJbWrLVFVWxs7iYS2ttLWWqVoldZWVC0NWtVFraWLUoqkQVEUtRSxpailahdSWUjIIsn8/vBzv2KNSGYS3s/Ho4/O3HPPnc8ZkzlzP/ecc6tVo1q1atn2Ht+NklLy2OnSpQuHDh1iy5YtRofi6+vL2LFjjS/DM2fO0KhRIw4cOHDP4da3fpmUL1+eNWvWGENZfXx8sj0hVb58eRwdHY2O0NbWlrCwsGx9TRERubcVK1Ywb948jh49iqOjI0888QSBgYF06tQpS6aoiIhl7dy5kxIlSlCkSBEWLlzIs88+aySlLl++zOrVq9m3bx82NjZERUUxZswYKlWqxE8//cS7775rJB5WrlzJgQMHqF+/vjH6Aq6PPklNTcXZ2ZktW7awceNG/P39AahZsyZVqlQhPj7+tmTWrevK3Gnx8pv9+++/vPjii8D1E//4+HhWrlxJbGws9vb2NGjQgP/++8/Y/+jRo5w8eRJvb2+io6M5fvw458+fZ/jw4cYd2g4ePEj79u2zdGrPg6y7BNcXYP7888+pWrUqXl5eDBkyhClTppCamkpiYiL58uUjNTWV1157jU8//ZS///6bSpUqkZaWxoYNG3j++ec5ePAgly5dYs2aNXTq1IkpU6YQHh6Ou7t7upEid0pI3U/z5s3ZtGkTAQEBpKSkYG9vT61atdiyZQvNmzfH29ub3bt3G5+H559/nunTpwNQu3ZtFi9eTPfu3Tl37hwhISG0bt3auLNf8eLFAcibN2+2rMl1q5IlS2Iymdi9ezcNGjRIN1qqQoUK7Nixg5kzZ/L000+zevVqmjVrhslkon79+lSpUsVImt1YoPuGm/8e7vc5flApKSmcOXOGYsWK3fXfb+/evRQrVuy2z3FMTAznzp2jcuXKNGjQIN0NCc6dO8fvv/9Oly5dqFChAleuXGHfvn2EhYXRpk0bJkyYwIwZM0hLS6Nfv373/Ru5MZ3u448/plSpUsZ2V1dXfvzxR65evcqVK1eYOHEiHh4ePPnkk2zbtg0fHx8qVapEWFgYrVq1SjeazNvbm/DwcAYOHIi7uzudO3emc+fO1K5dGycnp3TJdWvJntXARHKoM2fOEBYWhslkYt26dQ91rBtz9nOCkJAQ9uzZw549e5SQEhGxsm+++YZx48bRvXt34643H374Ibt37zbuqJUTpKamWjsEkRzrxkK+N3z00Uf8/vvvmEwm3nzzTTw9PYmPjwfgu+++Y+XKlbRq1QoHBweOHz/O2bNnKV26NFWrVjWOVbp0aRwdHfn3339ve72YmBiGDRtGQEAAS5YsoUaNGrRp08Yot7e3NxYDT01NxWw2Aw+2nk5iYiKVK1dm//79wPUkwObNm/ntt9/4+++/OXHihDGq54Znn30We3t7unfvTo8ePXjxxRfp2LEjSUlJxvSsnj17ZmlCKi0tDZPJxJIlS+jWrZvRTrPZTEREBJ988gmvv/46ixcvNtoxc+ZMBg8eTKNGjTh9+jRHjx5l165dXLlyhVKlSnHo0CFsbW1JTk7G3d2dP/74A4C+ffsyb9486tWrx9mzZ5k0aRJ16tQBricIateunSVTl9q0acOaNWvSbfP19WXHjh3A9bsnHjt2jOjoaADq1KnD+fPnOXTokJHsOH78OBUqVGDw4MEEBwdTpEgRatSocdtd/LKbl5cX1atX5+uvv+bvv//Gzs6O+Ph4FixYQFxcHIMHDyYtLY3NmzfTsWNHY6F3Nzc3vLy8jOPc+AzfkNUXbNLS0ox+7sZdCm8sDB8XF2fEcGMEUWRkJElJSUaC7eLFiwwdOpQXX3yRvn37AtCoUSMOHz5sxF6sWDGKFSvG8uXL6d+/P99++y0BAQEULVqUlJQUihQpwgcffJChhNQNzZo1M2a63DjffOaZZyhdujTffvsthQsXNqb51apVi3z58nHmzBnatm3Lli1bWLVqFUeOHGHGjBn8/PPPlCxZkh49euDv789bb71lrMlVtmzZHJGQAo2UksdMcHCwMSwxODiYFi1aMHjwYM6dO0fv3r2xtbWlT58+zJ8/H7j+hw7XTzCOHz/OokWLqFq1KiEhIXTo0IGSJUsa0yZuzPEOCAjAZDIxbtw43N3d002hO3bsGKNHj+bvv//Gw8ODgQMH0qhRIwCGDBmCo6MjZ8+eZefOnTz11FN88sknPPnkk1nS9pkzZ7Jo0SKioqLw9PTknXfeMeY4p6amMmnSJGPRvm7duvHRRx/dd6SYiIikFxcXx+eff05QUFC64f+VKlXik08+Aa6vuzFlyhR+/fVXkpOTady4McOGDSNv3rzG1OvXX3+dWbNmYWtryzvvvGOMbIiJiWHo0KHs2LGDMmXKGHcruuHYsWOMHTuWAwcOULBgQQYMGEDLli2B6/2Mg4MD586dY+fOnUybNi3ddAkRua5Lly40btyY1157zbjzVpMmTTh27Bgmk4m1a9eycOFCBgwYQJEiRdi/fz89e/akTp06lChRgoSEBGNR78KFCxsnwsWLF6dQoUKcPHnSOO4NJUqUYMiQIcYokru520ihjLC3t6dChQqsXr2aAQMGYDKZjCmAK1asYP369ZhMJk6fPk1sbCyurq6UK1eOUaNG8d9//+Hj40OBAgUy9dr3k9l1l5544gkjgfPmm2/i4+NDhQoVCAkJoWTJkiQkJPDzzz8zZ84cRo0axe+//46zszO//vorvXr1ol27djRs2BBXV1djKlp2qFat2m13uPP29ubChQtcu3aNihUrkpKSwqFDhyhSpAj58+enatWqxMbGArBy5UpjLbLsusvcg+jbty/ffPMNU6dO5b///iMlJYWSJUvy2muv4eHhwbBhw+57jOweNXzz+5SYmMiff/7Jpk2bcHJyIjAwkI4dOxoL48P1f6OvvvqKc+fOUbx4cVxcXOjVqxcTJkzgueeeY+/evVSvXh17e3u2b99uJHeGDx/O4sWLyZ8/Py+88MJtoxkfVJMmTZg3bx6dO3c2zsNcXFx48skn+euvvzh69CinTp2iUqVKFC9enF27dtGuXTsqVarE6NGjWbhwITExMTz99NPGNN0nnniCTp06PVRc2Ulnm/JYCQkJ4fXXX6datWq0b9+eixcvMmnSJHbt2pVu+l6LFi1o1KgRO3fuNL4Mjh8/Tnh4OK1atWLLli2kpKSwcuVK49jz58+nfPnyRicI19d1uuHatWv07t2bF198kTlz5rBr1y769OnDkiVLjPnUK1euZNasWVSqVIn333+fKVOmMGXKlCxpe4kSJZg/fz6FCxdm1apVDB48mDVr1lCkSBEWLVrEpk2bCAkJwdHRkQEDBmTJa4qIPG727NlDcnKyccHhTiZPnsypU6cIDg7Gzs6OQYMG8dVXXxl3yrp48SJxcXFs2rSJrVu30r9/fxo3bkyBAgUYM2YMDg4ObN68mTNnztC9e3djPZirV6/SrVs3+vfvz6xZszhy5Ahdu3alXLlyxpX+5cuXM3PmTGbMmJGjRm2J5CQ1a9bk8OHDwP+marm4uLB582YuXbpExYoVcXFx4eLFizz55JOcP3+eEiVKkJycTPHixXF0dOT48ePY2NhQokQJDh48aNw9r3DhwsTFxXHp0iUKFy5svKadnZ2RkEpLS8NsNt9x3aSHYWNjQ9u2bfn222+ZNm0aPXr0wMbGhr1797J+/Xrq169P3rx5cXZ2NkaPAMbt6LNTZtZdatSoEevWraNWrVpUrlwZR0dHhg8fbhzzyJEjlCtXjv79+/PTTz8REBBAw4YNmTBhAu7u7sD1BelvfIdmp/z581OoUCE2bdpEgwYNANixYweNGjXi0qVLFCpUiJo1axpJKIBp06YZj29dHN/a3NzcGDRoEEeOHCE1NZWKFSvets+ti+xnh5SUFGxsbG57jatXr7Jp0yb+/PNPnnrqKVq0aIGNjQ158uThu+++w8HBASDdqKiSJUtSrlw5Vq1axRNPPIGnp6fxN+nl5WWshXVjVNuNpJSjoyOvvvpqlrWpYsWKHD161EjG2traYm9vz549e+jSpQtHjx5l+vTpNGzYkN27d/P0008b55LPPfccPj4+mZpiak1KSsljIywsjHPnztGiRQvc3NwoUaIEy5cv5/XXX8/wMYoUKUKXLl0AHngE0b59+7h69Sq9evXCxsaGOnXq8MILL7BixQr69esHQOPGjY2Ov3Xr1kyYMCFDx27Tpo3xZRwYGMiIESNu26dFixbG45YtWzJjxgzCw8Np3Lgxv/76K6+++qpxt4tevXqxbdu2B2qfiIhgnFDd3Ed06NCBf/75h+TkZGbPns2iRYv45ZdfcHV1BeCNN97g3XffNZJSdnZ29O3bFzs7Oxo2bEi+fPk4fvw4Tz/9NGvWrOGXX34hX758lCtXjjZt2rBz504ANmzYQPHixY1RVZUqVaJZs2asWrWKt956C7g+9cDb2xvA+FEuIuk9//zzDB06lHnz5rFv3z5OnTqFvb09ERERHD16FB8fH5ycnDh69CgvvPAC7u7urFu3zvhNeebMGZKTk40T3cOHD3P58mU8PDwIDAw07kJ3N9l5Eu/u7s64ceNYt24dPXv25OzZs5QtW5Z69erx/PPPG99L1vCg6y698MILzJo1CxsbGwICAhg+fDienp4kJSWxdetWHB0dmTJlCiVLluSdd97hvffes1rbAN555x2WLl3Kpk2bOH/+POfOnWPAgAEUKlQIgIkTJ1o1vgdlNpspV66c8fzWJFRWrwt17Ngxfv/9dxITE2nZsiVlypS54/lYfHw8AwYMwM3NjWeeeYYqVarg7u7OZ599xrvvvktSUhIODg5ERUXxzTffsH79eurWrcugQYMYMmQIH3zwAePHj6dChQrs37+f6OhoqlWrho+PDwBffvlllrbrVo6OjuTLl49z584Zn41Dhw4RGRlJzZo1adeuHUuWLGH37t2UK1cOf39/8ubNa9TPbQkpUFJKHiPBwcHUrVvXGFLp5+fHsmXLHigpdestSh9EZGQkRYsWTfdDo1ixYly4cMF4fuOLB64vVnjjDib3s2zZMmN01t0EBwczd+5czp49C1y/ghATE2PEdvOc4odpp4jI48zV1ZWYmJh0C78uXLgQgAYNGnDx4kUSEhJo27atUefmNS1uHOPmH9qOjo5cvXqV6OhoUlJS0n1f33z78bNnzxIeHm78cIbrJwk335Ajp6wfIZKT1ahRw7jtemBgILVq1aJgwYK88847HDhwAB8fH8qUKcPJkye5evUqr776qnGSmJycDEDBggWJioqiXr166abZ3khI3byos6U1bNiQ5557jn///ZfSpUvnmJPYNm3aMH/+fAICAoxtvr6+BAUFAddHgSxevJjo6GiKFClCnTp1GD16NEeOHKFWrVrMmjWL+fPnkzdvXt566y1q1apl/O6+XyLQEho3boynpydbt26lYcOGPPvsszkirsy68fm98VnO6iTUDTffka5y5crky5ePV199lfXr17Ny5UpWr17NhQsXaN68OZ06deLkyZOkpqYaI4lvTMvMmzcvLi4ubNq0CT8/P/LkycNzzz1H586djb6xePHiTJ06lX379rF582batm1L3bp10y0cbgktW7Zk4cKFhIWFsWXLFi5evEifPn2MJODLL7/Myy+/bNGYspOSUvJYSExM5NdffyUtLc24pWhycjKXL1/m0KFDt+1/tx8JD/PjoUiRIpw/fz7dXVIiIiLS3Vkhu5w9e5YRI0Ywb948atSoga2tbboOv3Dhwpw/f954fvNjERHJuBo1amBvb8+6devSrSl1Q8GCBcmbNy8rVqy47c5D9+Pm5oadnR0RERHGYrERERFGuaenJ7Vq1WLu3LkP1wgRoWTJkjRo0ICmTZsa28qXL2/8bixfvjxbtmxh3759NGzYkFKlSrFnzx68vb2Ji4vjo48+Mu6KBrcnoax9F047OzvKly9v1Rhuldl1l24sWl2yZMkMrWVkTZUrV6Zy5crWDiNLZfdn+cYd6SZMmGBMp1uxYgXLly9n69at+Pn50bBhQ1577TXS0tJo3749xYsXZ/z48ZQtW5bjx49TvXp1+vfvT5kyZdi+fTt+fn5cuHDBOC+E//2NOjs735ZMtjRfX1+WLVtGwYIF6dq1K88880yOSR5nB+uvkiZiAWvXrsXW1pYVK1YQHBxMcHAwK1euxMfHh+DgYAoVKsTp06eN/d3c3LCxsUm3LSNuPc7NqlatSt68eZk9ezbXrl1j+/btrF+/3liANjslJCRgMpmMUWJLlizh6NGjRnmLFi347rvvuHDhApcvX2bWrFnZHpOIyKPIxcWFvn378uGHH7Jq1Sri4+NJS0vj77//JiEhARsbG15++WXGjx9PVFQUABcuXDDuBHUvtra2NGnShC+//JKEhAT++ecfli1bZpQ///zznDhxguDgYK5du8a1a9cIDw/n2LFj2dZekUdV3bp12bBhA8nJycZIxlq1arFr1y7OnTtHpUqVeOGFF4yR6kWLFiVPnjzMnj2bwYMH07JlS5ydnY3jWTsJdaucFg+kX3fpxgn4zesuAXdcd+nGjYnk0dWsWTO2bNliPH/qqacYMWIE+fLlo1WrVjg5OfHmm29y9OhRYmNjGTduHN999x3vvPMOnTp1YunSpcD10Xh79uzB39+fRYsWpbsDYE76myhdujTLly9n8ODB1KtX75FOSIFGSsljYtmyZbRt2zbdNAeAV155hXHjxvHhhx8yduxYJk2axJtvvkn37t3p3bs3HTt2JCUlhdmzZ2fodd566y2GDBlCYmIiY8aMMRZRhOvze6dPn86HH37IjBkz8PDwYOLEielujZpdnnrqKbp160aHDh0wmUwEBgZSs2ZNo7xdu3acOHGC1q1bkz9/fl599VV27NiRbcNwRUQeZT179sTDw4PZs2fz/vvv4+joSIkSJRg0aBA1atSgevXqfPXVV7Rr146YmBg8PDzo2LEj9evXv++xR44cydChQ6lbty5lypShbdu2xk01nJycmDNnDh9//DEff/wxZrOZ8uXLM3To0Oxussgjp169esycOZPo6GhjWQNvb28GDx6Mu7s7Dg4O6e5m5eDgwJkzZ3jmmWcYOHBgtt2l7lH3qK27JFmjcePGzJkzhyeffJLffvuNYsWK8fbbb6e76VSlSpWYPHky+fPnJyoqiosXL3LgwAG2bdtG69atSUtLo2LFinz99dcUL148R9zFUK4zmW9OD4qIABs3bmT06NH8/vvv1g5FRERExCoGDhzIO++8Q4kSJYDbp+DdOI3KSSMsHgUHDhxg69atVKhQIdevuyRZIzExkXr16lGzZk2ee+45mjVrhoODA40aNWL+/PlUqlSJ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81KzZk18fHweOk55dJjMZrPZ2kGIiIiIiIiIiMjjRdP3RERERERERETE4jR9T0REREREROQR98svvzBq1KjbthcrVowVK1ZYISIRTd8TEREREREREREreGxHSu3atcvaIYiI5Fje3t7WDsHq1E+IiNzd495PqI8QEbm3jPYTj21SCtSZiojciX5o/4/6CRGR26mfuE59hIjInT1IP6GFzkVERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkREREREREREbE4JaVERERERERERMTilJTKJqmpqQQGBvLGG28AYDabmTJlCs2aNaNFixZ89913t9X5+++/ad++Pa1atcLf35+VK1caZdu2baNNmzYEBATQsWNHTp48CcD333+Pn58fPXv2JDk5GYCwsDDGjx9vgVaKiMijKCkpiZdeeonWrVvTqlUrPv/8cwCGDBmCr68vAQEBBAQE8Pfff9+xfvfu3fHx8TH6wBvu1heuXr2aVq1a0alTJ2JiYgA4deoUb7/9dvY1UkQkB/v222/x8/OjVatWzJs3D4DPPvsMf39/AgIC6NatGxcuXLhj3bt9B+t8QkRyIjtrB/Co+u677/Dy8iI+Ph6ApUuXEhERwa+//oqNjQ1RUVG31cmbNy9BQUGUKlWKCxcu8OKLL1KvXj1cXFwYPXo006ZNw8vLi/nz5/P111/z8ccfExoayi+//ML06dPZvHkzL7zwAl9//TWffPKJpZssIiKPCHt7e7799lvy58/PtWvX6NSpEw0aNADgvffeo3nz5ves36NHDxISEvjpp5/Sbb9bX/jDDz/w888/s2bNGpYvX06XLl347LPPlJQSkcfSkSNHWLx4MYsXLyZPnjz06NGDF154gR49ehjfi9999x1fffUVY8aMua3+3b6DdT4hIjmRRkplg/Pnz7NhwwZeeuklY9uCBQvo27cvNjbX33J3d/fb6pUuXZpSpUoB4OHhgZubG9HR0Ub5jQRXfHw8RYoUAa5fdU5JSSExMRE7OztCQkKoX78+rq6u2dQ6ERF51JlMJvLnzw9ASkoKKSkpmEymDNevU6eOUf9md+sLTSYTycnJRl8WFhZGoUKFjD5RRORxcuzYMapWrYqjoyN2dnbUqlWLNWvW4OTkZOyTkJBw1+/lu30Hg84nRCTnUVIqG4wfP57BgwcbP7oBTp8+zcqV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jY0NEydOZNSoUSQlJVG8eHEmTZp03zIREREREckZlJQSERGrK1SoEIsWLbpjWXBw8F3r1axZk9DQ0AcuExERERER69P0PRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkREREREREREbE4JaVERERERERERMTilJQSERERERERERGLU1JKREREREREREQsTkkpERERERERERGxOCWlRERERERERETE4pSUEhERERERERERi1NSSkRERERERERELE5JKRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkREREREREREbE4JaVERERERERERMTilJQSERERERERERGLU1JKREREREREREQsTkkpERERERERERGxOCWlRERERERERETE4pSUEhERERERERERi1NSSkRERERERERELE5JKRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpyrKSkJF566SVat25Nq1at+PzzzwHYtm0bbdq0ISAggI4dO3Ly5Mnb6iYnJzN06FD8/f1p3bo127dvv22f3r174+fnZzyfNGkS/v7+vPfee8a2kJAQ5s2bl/WNExEREREREXnMWTwp9eWXX1K+fHmOHDkCwN69e2ndujXNmjWjW7duREVFGftmtkweDfb29nz77bf88ssvBAcH88cff7B3715Gjx7N5MmTCQkJwc/Pj6+//vq2uosXLwYgNDSUuXPnEhQURFpamlG+Zs0a8ufPbzyPi4vj4MGDhIaGkidPHg4fPkxiYiJLly7llVdeyf7GioiIiIiIiDxmLJqUOnDgAHv37qV48eIApKWlMXjwYEaOHMnq1avx8fFh8uTJD1Umjw6TyWQkjlJSUkhJScFkMgEQHx9v/L9IkSK31f3nn3+oXbs2AO7u7jg7O7N//34Arly5wty5c3nzzTfTvVZKSgpms5nExETs7OyYM2cOXbp0IU+ePNnaThERERG5v99//53AwEACAgJo3bo1a9asAeD48eO0b9+eZs2a0b59e06cOGHUyWyZiIhYhsWSUsnJyYwZM4bRo0cb2/bv34+DgwM+Pj4AdOjQgVWrVj1UmTxaUlNTCQgI4LnnnuO5556jWrVqjBs3jl69etGgQQNCQkLo1avXbfUqVKjA+vXrSUlJ4fTp0xw4cICIiAgApk6dSrdu3cibN6+xv5OTEw0aNCAwMJDChQvj7OxMeHg4jRs3tlhbRUREROTOzGYz7733HhMnTiQkJISJEyfy/vvvk5aWxqhRo+jUqROrV6+mU6dOjBw50qiX2TIREbEMO0u90NSpU2ndujVPPPGEsS0iIoJixYoZz93c3EhLSyM2NjbTZa6urhmOadeuXXct80xJzPBxHmVxcXEcucf7ZAkjR47kypUrTJkyheDgYH7++WcGDhzIU089RWhoKO++++5tianSpUuzbds2WrZsSaFChShTpgzHjx9nyZIl/PXXXzRr1oz9+/eTkJBgfA5q1qxJzZo1Afjggw9o0qQJkydPJjw8nCeffJI2bdpYvO0ij5M+ffpw5swZbGxsyJcvHx988AEVK1bk+PHjDBkyxPiODwoKolSpUgCZLhMRkdzHxsaGuLg44Ppv1CJFihATE8PBgweZO3cuAH5+fnz00UdER0djNpszVebm5madBoqIPIYskpTas2cP+/fvZ9CgQZZ4uQzz9va+a1ncwXAiLBhLTuXs7EyxSlWtHQYA4eHhXLx4kfPnz9O+fXsAPD096dGjxx3/LZ955hnjcYcOHWjcuDE7duzg9OnTDB48mJSUFKKjo/nss8/4/vvvjX0PHjyIu7s7LVu2pF+/fnz33XcMHToUd3d3ndDKY+FeCfvsFBQUhLOzMwBr165l2LBhLFu2zLiSHRAQQEhICCNHjuS7774DyHSZiIjkLiaTic8++4w+ffqQL18+rly5wsyZM4mIiMDDwwNbW1sAbG1tKVKkCBEREZjN5kyVZTQpdb/+Uhe5c8YFbhHJ2SySlNq5cyfHjh2jUaNGAJw/f57u3bvTpUsXzp07Z+wXHR2NjY0Nrq6ueHp6ZqpMHh3R0dHY2dnh4uJCYmIiW7dupWfPnsTFxXH8+HFKly7Nli1b8PLyuq1uQkICZrOZfPnysWXLFmxtbXnqqad46qmn6NSpEwBnzpyhd+/e6RJScH1U35gxY0hJSSE1NRW4/kMoMVE/LESy042EFFxfL85kMhEVFaUr4CIiQkpKCjNmzGDatGl4e3uza9cu3n77bSZOnGi1mO51gRt0kRty1gVuEbGcB7nIbZGkVK9evdJNr/L19WX69Ok89dRTLFq0iLCwMHx8fFi4cCHNmzcHoEqVKiQmJj5wmeQsETHxRF5OyFTdk//+w1eTxpGWloY5LY06DX1xK1OFHv0H07N3H2xsTOR3cubNd4ey7+R/hG3bzLEjh2j/Wg8iz0cwbthAbEw2uBUqRO+B1/e5WeT5aBKTU9Jt37FlE4WeKM35RBtITMK9eEkaN2tBydJeJDm633aMjCri4ohnQadM1RV5nAwfPpwtW7ZgNpuZPXu2Va+Ag/VGjVlDgkNBa4fwQOLi4ti165S1wxARC/n777+JjIw0EkHe3t44Ojri4ODAhQsXSE1NxdbWltTUVCIjI/H09MRsNmeqTERELMdia0rdiY2NDRMnTmTUqFEkJSVRvHhxJk2a9FBlkrNEXk5g8I+bMn+A+l0xASZgO7D9x02ACZvnewBwBZj8+zHg2PX985Qj7P9fz77x9bvrXQYmrjsCHLnt8DYv9Lw9Pruy7LyxzakqNs9X5TQ8VDsmdWqgpJRIBowbNw6A4OBgJk6cyIABA6waz/2ugj9KMpt0txZnZ2eqVSlj7TBEHkvWSNgXLVqU8+fP8++//1KmTBmOHTtGVFQUJUuWpGLFiixfvpyAgACWL19OxYoVjQsQmS0TERHLsEpSav369cbjmjVrEhoaesf9MlsmIiK5W2BgICNHjqRo0aK6Ai4iIhQuXJjRo0czYMAATCYTAOPHj8fV1ZXRo0czZMgQpk2bhouLC0FBQUa9zJaJiIhlWHWklIiICMCVK1e4fPmykTRav349BQoUwN3dXVfARUQEgNatW9O6devbtnt5ebF48eI71slsmYiIWIaSUiIiYnUJCQkMGDCAhIQEbGxsKFCgANOnT8dkMukKuIiIiIjII0pJKRERsbpChQqxaNGiO5bpCriIiIiIyKPJxtoBiIiIiIiIiIjI40dJKRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkREREREREREbE4JaVERERERERERMTilJQSERERERERERGLU1JKREREREREREQsTkkpERERERERERGxOCWlRERERERERETE4pSUEhERERERERERi1NSSkRERERERERELE5JKRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkREREREREREbE4JaVERERERERERMTilJQSERERERERERGLU1JKREREREREREQsTkkpERERERERERGxOCWlRERERERERETE4pSUEhERERERERERi1NSSkRERERERERELE5JKRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkREREREREREbE4O2sHICIiEhMTw3vvvcepU6ewt7enZMmSjBkzBjc3N8qXL0+5cuWwsbl+HWXixImUL18egPXr1zNx4kRSU1OpXLkyEyZMwNHR8b5lIiIiIiJifRopJSIiVmcymejRowerV68mNDSUEiVKMHnyZKN84cKFhISEEBISYiSkrly5wgcffMD06dP57bffyJ8/P3PmzLlvmYiIiIiI5AxKSomIiNW5urpSu3Zt43n16tU5d+7cPets2rSJKlWqUKpUKQA6dOjAr7/+et8yERERERHJGTR9T0REcpS0tDQWLFiAr6+vsa1Lly6kpqbSoEED+vXrh729PRERERQrVszYp1ixYkRERADcs0xERERERHIGJaVERCRH+eijj8iXLx+dO3cGYMOGDXh6ehIfH8/gwYP56quveOeddywSy65duyzyOjlBgkNBa4fwQOLi4ti165S1wxARERGRh6CklIiI5BhBQUGcPHmS6dOnGwube3p6AuDk5MTLL7/M3Llzje3bt2836p47d87Y915lD8Lb2zvTbclt9p38z9ohPBBnZ2eqVSlj7TBEHkuPU8JeRESyl9aUEhGRHOHTTz9l//79fPXVV9jb2wNw6dIlEhMTAUhJSWH16tVUrFgRgPr16/PXX39x4sQJ4Ppi6C1atLhvmYiIiIiI5AwaKSUiIlZ39OhRZsyYQalSpejQoQMATzzxBD169GDkyJGYTCZSUlKoUaMGAwYMAK6PnBozZgxvvPEGaWlpVKxYkeHDh9+3TEREREREcgYlpURExOrKli3L4cOH71gWGhp613qNGzemcePGD1wmIiIiIiLWp+l7IiIiIiIiIiJicUpKiYiIiIiIiIiIxSkpJSIiIiIiIiIiFqeklIiIiIiIiIiIWJySUiIiIiIiIiIiYnFKSomIiIiIiIiIiMUpKSUiIiIiIiIiIhanpJSIiIiIiIiIiFicklIiIiIiIiIiImJxdpZ6oT59+nDmzBlsbGzIly8fH3zwARUrVuT48eMMGTKE2NhYXF1dCQoKolSp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lURERETQSCkRERF5jNSqVYsCBQpkad0FCxbQq1cv7O3tAXB3dwfAzs6OhIQEEhMTsbOz49SpU0RERFC7du3MN0BERETkEaKklIiIiDz25s+fj7+/P0OHDuXSpUsPVPfEiROEhYXx8ssv07lzZ8LDwwF44403eP/995kxYwadO3dmypQpvP3229kQvYiIiEjupKSUiIiIPNY6duzIb7/9RkhICEWKFOHjjz9+oPqpqalcunSJRYsW8d577/H2229jNpupWLEiixYt4vvvv+f06dMULlwYs9nM22+/zaBBg7h48WI2tUhEREQkd7BIUiomJoaePXvSrFkz/P39eeutt4iOjgZg7969tG7dmmbNmtGtWzdjHYaHKRMRERHJqEKFCmFra4uNjQ0vv/wyf/311wPV9/DwoEmTJphMJuP29jExMUa52Wzm66+/pk+fPnz55ZcMHjyYdu3a8f3332d1U0RERERyFYskpUwmEz169GD16tWEhoZSokQJJk+eTFpaGoMHD2bkyJGsXr0aHx8fJk+eDJDpMhEREZEHERkZaTxeu3YtZcuWfaD6jRs3Zvv27QAcP36ca9euUbBgQaM8ODiYBg0a4OrqSmJiIjY2NtjY2JCQkJA1DRB5zHz55ZeUL1+eI0eOALrILSKSm1kkKeXq6ppuUc/q1atz7tw59u/fj4ODAz4+PgB06NCBVatWAWS6TEREcp+goCB8fX3TnWQA+Pr60rx5cwICAggICOCPP/4wynSiIRlx+VISEWfjjP/e7N2Pl19ux7///kvduvWZPet7xnw4nubNW9KiRSs2bthM9679iTgbx1/7/uXVLl3vWTfibBx16zTjyJHjNGvWgn5vDeC9QaM4fy6eiLNxHD/2HwsXLqbRCwFEnI2jtV97unbtzoejP6LRC/7pYos4G8flS0nWfstEcrQDBw6wd+9eihcvDmT+QrYucouI5Ax2ln7BtLQ0FixYgK+vLxERERQrVswoc3NzIy0tjdjY2EyXubq6ZjiWXbt23bXMMyXxwRr2iIqLi+PIPd6n+0lwKHj/nR4DcXFx7Np1ytphiORYjRo14tVXX+WVV165rezzzz+nXLly6bbdOJmYMGECPj4+TJs2jcmTJzNhwoR7lsnj50p8MqtC/5fofKb66zxT/fX/7ZAK3k9Xwvvp/23auTUauL7MwAt13zLq36nujTKf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dSr6cA0WERG5ByWlREREREQs5PLVi/y0aaS1w8iQ9g3GKCklIiLZSmtKiYiIiIiIiIiIxSkpJSIiIiIiIiIiFqeklIiIiIiIiIiIWJySUiIiYnVBQUH4+vpSvnx5jhz530K7x48fp3379jRr1oz27dtz4sSJhy4TEREREZGcQUkpERGxukaNGjF//nyKFy+ebvuoUaPo1KkTq1evplOnTowcOfKhy0REREREJGdQUkpERKzOx8cHT0/PdNuioqI4ePAgfn5+APj5+XHw4EGio6MzXSYiIiIiIjmHnbUDEBERuZOIiAg8PDywtbUFwNbWliJFihAREYHZbM5UmZub2wPFsGvXrnTPPVMSs6BllhMXF8eRW9pwNwkOBbM5mqwVFxfHrl2n7rufs5PnfffJSeLi4zi368j9dwTs7HLXz7j4+Pjb/qYeR3kLJls7hAyLi49j12n9m4mISPbJXb9mRERELMjb2zvd87iD4URYKZbMcHZ2plilqhnad9/J/7I5mqzl7OxMtSpl7rtfxNk4yEX/as5OzpQrXyxD+x47diybo8laTk5OeHl5WTsMqzsVud/aIWSYs5MzlctUuW27kosiIpJVlJQSEZEcydPTkwsXLpCamoqtrS2pqalERkbi6emJ2WzOVJmIiIiIiOQcWlNKRERyJHd3dypWrMjy5csBWL58ORUrVsTNzS3TZSIiIiIiknNopJSIiFjd2LFjWbNmDRcvXqRr1664urqyYsUKRo8ezZAhQ5g2bRouLi4EBQUZdTJbJiIiIiIiOYOSUiIiYnUjRoxgxIgRt2338vJi8eLFd6yT2TIREREREckZNH1PREREREREREQsTkkpERERERERERGxOCWlRERERERERETE4pSUEhERERERERERi1NSSkRERERERERELE5JKRERERERERERsTglpURERERERERExOKUlBIREREREREREYtTUkpERERERERERCxOSSkRERERyTX+/fdfAgICjP9q1qzJvHnz0u1z7Ngx2rdvT5UqVZgzZ066snnz5tGqVSv8/PwYOHAgSUlJALz77rv4+/vz6aefGvtOmzaNtWvXZnubREREHlcWSUoFBQXh6+tL+fLlOXLkiLH9+PHjtG/fnmbNmtG+fXtOnDjx0GUiIiIi8ugqU6YMISEhhISEsHTpUhwdHWnSpEm6fVxdXRk+fDjd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B7K1LWJ9dtYOQERERERERERyj2+//RY3N7e7lqempjJ58mTq1q1rbNu9eze7d+/ml19+AaBTp07s2LGD+Ph4vL296d27Nx07duSVV17h0KFDpKamUrly5Wxvi1iXRkqJiIiIiIiISJb5/vvvadasGe7u7sY2k8lEcnIy165dM/5fqFAh7OzsSExMJCUlBbPZDMBnn33GgAEDrBW+WJCSUiIiIiIiIiKSYd27d6dt27b89NNPt5VduHCBtWvX0rFjx3Tba9SoQe3atalXrx716tWjfv36eHl5UbduXc6ePUu7du3o0qUL69ato3Llynh4eFiqOWJFmr4nIiIiIiIiIhmyYMECPDw8iIqKomvXrpQpU4ZatWoZ5ePGjWPQoEHY2KQfA3Py5EmOHTvGxo0bAejWrRthYWH4+PjwySefAHDt2jW6d+/OtGnTmDBhAhEREQQEBNCoUSPLNVAsSkkpEREREREREcmQGyOY3N3dadKkCeHh4emSUvv372fgwIEAxMTEsHHjRuzs7Dhx4gTVqlUjf/78ANSvX589e/bg4+Nj1P3xxx8JDAxk3759ODs789577/Haa68pKfUI0/Q9EREREREREbmvq1evEh8fbzzesmULZcuWTbfP+vXrjf+aNWvGqFGjaNy4McWKFWPnzp2kpKRw7do1du7ciZeXl1Hv0qVLbNiwgcDAQBISEjCZTJhMJhITEy3aRrEsjZQSEREREREReYRdvpTElfjkhz7OuXNn+GDkYOD6HfYaNWpGWa8aTP96LgABrV9Kt//Vq9eIiU4g4mwcVas8x/p1m2jRohUmk4lnatWhYvlaRJyNA+DLr6bw8kuvciHiCk95VWfuN9/xS8hyWvu3NfZ5GPmd7HEp4PDQx5GspaSUiIiIiIiIyCPsSnwyq0KPZMmxXg74MN3zVaFHcDBVNR7frEalTiRe/t/2ymVfpnLZl9PVveGpJ/25cBpWnb6+rXGDAXfcL7Oa+5dTUioH0vQ9ERERERERERGxOCWlRERERERERETE4pSUEhERERERERERi1NSSkRERERERERELE5JKREREREREXmkDR06lDp16uDn53fH8mPHjtG+fXuqVKnCnDlz0pX5+vri7+9PQEAAbdu2NbZPmjQJf39/3nvvPWNbSEgI8+bNy5Y2iDyKlJQSERERERGRR1rbtm2ZPXv2XctdXV0ZPnw43bt3v2P5t99+S0hICEuXLgUgLi6OgwcPEhoaSp48eTh8+DCJiYksXbqUV155JVvaIPIoUlJKREREREREHmm1atWiQIECdy13d3enatWq2NnZZeh4JpOJlJQUzGYziYmJ2NnZMWfOHLp06UKePHmyKmyRR56SUiIiIiIiIiL30L17d9q2bctPP/0EgJOTEw0aNCAwMJDChQvj7OxMeHg4jRs3tnKkklts2rSJZs2a0aRJE2bOnHlb+dy5c2nZsiX+/v689tprnD171ihbtmwZTZs2pWnTpixbtgyA5ORkunfvjp+fH/Pnzzf2/eCDDzhw4ED2NyiTMpYGFhEREREREXkMLViwAA8PD6KioujatStlypShVq1a9OzZk549ewIwfPhw+vfvz+LFi9m8eTPly5enT58+Vo5ccqrU1FTGjBnD3Llz8fDw4KWXXsLX15ennnrK2KdixYosWbIER0dHfvzxRyZNmsRnn31GbGwsX375JUuWLMFkMtG2bVt8fX0JCwvD29ub3r1707FjR1555RUOHTpEamoqlStXtmJr700jpURERERERETuwsPDA7g+xa9JkyaEh4enKz948CBms5nSpUuzatUqpk6dyunTpzlx4oQVopXcIDw8nJIlS1KiRAns7e1p1aoV69atS7fPs88+i6OjIwDVq1fn/PnzAGzevJm6devi6upKgQIFqFu3Ln/88Qd2dnYkJiYa00oBPvvsMwYMGGDZxj0gJaVERERERERE7uDq1avEx8cbj7ds2ULZsmXT7TN16lQGDBhASkoKqampwPU1pxITEy0er+QOFy5coGjRosZzDw8PLly4cNf9f/75Zxo0aHDPunXr1uXs2bO0a9eOLl26sG7dOipXrmwkVXMqTd8TERERERGRHCkiJp7IywkPfZzPxo/iYPhe4i7FUqduPdp16U5KagoATf0CiY2OYshbPUi4egWTyYbZ38zl01k/EHc5lskfDgOuT7mq90ITCpSsyL6T/wGwY8smCj1RmvOJNpCYhHvxkjRu1oKSpb1IcnQ39nsYRVwc8Szo9NDHkdwpJCSE/fv388MPP9xzPzs7Oz755BMArl27Rvfu3Zk2bRoTJkwgIiKCgIAAGjVqZImQH0iuTkodP36cIUOGEBsbi6urK0FBQZQqVcraYYmISA6hfkJERO5F/UTOF3k5gcE/bnr4A5Vq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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Podemos ver que a maioria dos clientes são mulheres, ganham menos de $40K, tem apenas a graduação e tem o cartão básico e se tivermos uma visão anual, vemos que 83,93% dos clientes saem do banco todos os anos.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[101]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set_style</span><span class="p">(</span><span class="s1">&#39;whitegrid&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">=</span><span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;Card_Category&#39;</span><span class="p">,</span><span class="n">data</span><span class="o">=</span><span class="n">df</span><span class="p">,</span><span class="n">hue</span><span class="o">=</span><span class="s1">&#39;Gender&#39;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="s1">&#39;</span><span class="si">{:0.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span><span class="o">/</span><span class="nb">len</span><span class="p">(</span><span class="n">df</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">),</span> <span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span><span class="o">+</span><span class="mf">0.10</span><span class="p">,</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span><span class="o">+</span><span class="mi">10</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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nTt36ocffsix39WrV/XBBx/o4Ycftm1zdHTUmDFjNHHixGz77ty5Uz4+PtqwYYM2bNggSTp27JiysrLk5eVVqP0BUDYRxAEAJY7JZFLFihUlSZmZmcrMzJTJZMqx34IFCzR06FA5OjratlWoUEG+vr7ZtkmSvb29UlNTlZmZKavVKkl66623NGbMmELsCYCyjCAOACiRsrKyFBISokceeUSPPPJItlFvSTpy5IjOnz+vdu3a5el8rVq10tmzZ9W7d2/1799fW7dulZeXl9zd3QuhegCQ7I0uAACA/LCzs1N4eLiuXLmikSNH6vjx4/L09JQkWSwWvf7663rttdfyfD57e3u98cYbkqSMjAwNHjxYS5Ys0WuvvabY2FiFhISoQ4cOhdIXAGUTI+IAgBLN2dlZzZs3186dO23brl27puPHj+upp56Sv7+/fvjhB40YMcJ2w+adrF69WqGhofrxxx/l5OSk+fPna+XKlYXVBQBlFEEcAFDiJCYm6sqVK5Kk1NRUfffdd6pdu7at3cnJSXv27FF0dLSio6PVqFEjLV26VA899NAdz/3nn39q27ZtCg0NVUpKikwmk0wmk1JTUwutPwDKJqamAABKnPj4eIWFhSkrK0tWq1WdOnVS+/bttWDBAnl7e99xCom/v7+uXr2qjIwMbdmyRe+++67q1q0rSVq8eLGGDx8us9msNm3aaPXq1QoODlafPn2KomsAyhCT9cat4WXM/v375ePjk+/jk47G6PissAKsqOQyTVmssPUHjC6jWJjb108P31fV6DKAYistLlbpCReMLqNYcKhSVY7uHv/4PLGxsZo4caISEhJkMpnUu3dvDRgwINs+VqtVs2bN0vbt21WuXDm9/vrr8vLy0vfff59tHv2vv/6q+fPnq2PHjho3bpyOHz+u9u3b6/nnn5ckLVmyRJ6enurYseM/rhsoK26XORkRBwAUmfSECwxi/H+ek18vkCBuZ2ensLAweXl56erVq+rRo4datWplG+GXpB07duj06dP66quv9OOPP+rll1/WmjVr1KJFC4WHh0uSLl++rEcffVStWrXSsWPHVK5cOUVERGjgwIFKSkpSSkqKYmJi9O9///sf1wzgOuaIAwBQgrm5udkeOFSpUiXVrl1bcXFx2fbZunWrQkNDZTKZ1KhRI125ckXx8fHZ9tm8ebPatGmj8uXL6667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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Destrinchando esses dados, vemos que a maioria das mulheres tem o cartão básico e os cartões Gold, Silver e Platinum são todos dominados por homens.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[102]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">12</span><span class="p">,</span><span class="mi">6</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">set_style</span><span class="p">(</span><span class="s1">&#39;whitegrid&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">=</span><span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">x</span><span class="o">=</span><span class="s1">&#39;Gender&#39;</span><span class="p">,</span><span class="n">data</span><span class="o">=</span><span class="n">df</span><span class="p">,</span><span class="n">hue</span><span class="o">=</span><span class="s1">&#39;Income_Category&#39;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">annotate</span><span class="p">(</span><span class="s1">&#39;</span><span class="si">{:0.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span><span class="o">/</span><span class="nb">len</span><span class="p">(</span><span class="n">df</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">),</span> <span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span><span class="o">+</span><span class="mf">0.07</span><span class="p">,</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span><span class="o">+</span><span class="mi">10</span><span class="p">),</span><span class="n">ha</span><span class="o">=</span><span class="s1">&#39;center&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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EydOZP78+fTq1YuPPvqI2rVr2/sbNWqU5b3T3dzc7CEcoH79+pw/fx6AY8eO4ezsTKNGjQDo1asXW7ZsyTQ+NjaWl156iZdffvmBIVxEREREck9BvJCyWCxYrVYuXboEQKlSpahevXqO5sjIyODTTz/F398fuH2lu1KlSvZ+d3d3MjIyuHr1qr2tf//+DB48mB49ejz0OYiIiIjIvWlpSiFVokQJFi5cyIIFCzh+/Dg///wzQ4cO5W9/+1u255gyZQolS5akb9++2R7z7LPP8r//+7907NgRFxeXLI/56aefCA0NBW5fub927RpBQUEAtGvXjqFDh2b7/UREREQeVwrihVizZs1o1qwZc+fOxcvLi0GDBrFv375sjY2IiODMmTMsWbIEq/X2Lz48PT3ty1QALl++jNVqxc3Nzd725ptvMnPmTIKDg1m2bFmWYdzHx4fIyEhAa8RFREREcktLUwqpGzducPr0aQAcHR2pW7cuN27cICMj44Fj58yZw7Fjx1i4cCFOTk729jp16pCSksKhQ4cAWL16NR07dsw01mKxMHnyZLy9vQkODiYpKSnvTkpERERE7HRFvJBKT09n+vTpXL9+nbi4OLZu3crUqVPtV7enTp3Ktm3buHTpEgMGDMDNzY1Nmzbx66+/snTpUqpXr06vXr0AqFKlCgsXLsRqtTJz5kzCwsIy3b7wv90J4xMnTrzvlXERERERyT2LYRiG2UWYITo6Gl9f30xtFy9epHz58pnaCut9xOXhZfX9FhHJDz+eucjoT/aaXUa2zerjR71q+vkokheyypx36Ir4AziWLJftwJxfnn76aVPfX0RERETyntaIFwF/vi+4iIiIiDwaFMRFREREREygIC4iIiIiYgIFcREREREREyiIi4iIiIiYQHdNeYCrSX9w/ealPJ+3dMlyuLlUvO8xNWvW5Pvvv6dUqVL2tiZNmvDFF19QpUqV+4719/dnyZIleHt750m9IiIiIpK3FMQf4PrNS3y2d2Kez9vTL/yBQVxEREREHl1amlKE+fv7M3/+fHr27Im/vz8ff/xxlsf9+9//5h//+AeJiYm88847jBw5kkGDBtGxY0deeeUVkpOTAbhx4wbjxo0jICCAgIAA3n//fQB+++03OnXqBNx+4qevry/Lli0DYPPmzbz++usAvPTSS0RERNC7d2/atGnD7Nmz8/sjEBERESmyFMSLuJSUFD777DNWrlzJ22+/zY0bN+x9GRkZTJ06lePHj/P+++/j6uoKwLFjx3j77bf5z3/+Q3p6OlFRUQAsWrSIjIwMoqKiWL16NevXr2fPnj3UqFGDpKQkLly4wNGjR/nrX//K119/DcA333zDM888Y3/PuLg4Vq1axfr161mzZg2nT58uuA9DREREpAhREC+CLBaL/evnnnsOgCpVqlC6dGn++OMPe9/48eMBmD17Nk5OTvb2Fi1aULp0aSwWC3Xr1iU2NhaAr7/+mh49emCxWHBxcaFTp072wP3MM8/w9ddfc+DAAXr27Mkff/zBrVu3OHDgQKYg3rFjR6xWK66urnh5ednnFhEREZHMFMQLMXd3d65evWp/nZ6eTlJSEu7u7vY2Z2dn+9cODg7YbDb768aNGxMdHc3ly5czzXu/MffyzDPP8M033/DNN9/QtGlT6tWrx6ZNmzAMg6pVqz7U3CIiIiKPIwXxQqxZs2Z89tln9tefffYZ9erVo0SJEtka3717dwYMGED//v2Jj49/4PFNmzbliy++wDAMkpKS2Lx5M82aNbP37du3j2vXrlGxYkWaNWvGO++8Q9OmTXN3ciIiIiKPOd01pRCbMGEC06ZNIzAwEKvViqenJzNnzszRHJ07d8bZ2Zn+/fvbN1/ey5AhQ5gyZQqBgYH2sX5+fgBUrFiRUqVK4evrC9y+Qn7+/PlMy1JEREREJPsshmEYZhdhhujoaHuovOPixYuUL18+U5uZ9xGX/JXV91tEJD/8eOYioz/Za3YZ2Tarjx/1qunno0heyCpz3qEr4g/g5lJRgVlERERE8pzWiIuIiIiImEBBXERERETEBAriIiIiIiImUBD/E6vVSkpKitllSAFISUnBatVffxERETGPNmv+ibu7O5cvXyYxMdHsUiSfWa3WTA9GEhERESloCuJ/YrFYKFu2rNlliIiIiMhjQL+bFxERERExgYK4iIiIiIgJFMRFREREREygIC4iIiIiYgIFcRERERERExRIEL9y5QqDBg2iQ4cOBAYGMnToUC5fvgzADz/8QOfOnenQoQMvv/wyCQkJ9nG57RMRERERKewKJIhbLBaCg4PZunUrUVFRVK1aldmzZ5ORkcHo0aOZOHEiW7dupVGjRsyePRsg130iIiIiIkVBgQRxNzc3mjRpYn9dv359zp8/z7Fjx3B2dqZRo0YA9OrViy1btgDkuk9EREREpCgo8DXiGRkZfPrpp/j7+xMXF0elSpXsfe7u7mRkZHD16tVc94mIiIiIFAUF/mTNKVOmULJkSfr27cuXX35Z0G+fSXR0tKnvLyIij4dk5zJml5AjiYmJREfHml2GyCOvQIN4REQEZ86cYcmSJVitVjw9PTl//ry9//Lly1itVtzc3HLdlxO+vr4PfU4iIiIP8uOZi2aXkCOurq7Uq1PD7DJEHgn3u/BbYEtT5syZw7Fjx1i4cCFOTk4A1KlTh5SUFA4dOgTA6tWr6dix40P1iYiIiIgUBQVyRfzXX39l6dKlVK9enV69egFQpUoVFi5cyMyZMwkLCyM1NZXKlSsza9YsAKxWa676RERERESKAothGIbZRZghOjpaS1NERKRA/HjmIqM/2Wt2Gdk2q48f9aqVN7sMkUfC/TKnnqwpIiIiImICBXERERERERMoiIuIiIiImEBBXERERETEBAriIiIiIiImUBAXERERETFBtoP48uXLs2xfsWJFnhUjIiIiIvK4yHYQX7hwYZbtixcvzrNiREREREQeFw98subXX38NQEZGBt988w1/fv7PuXPnKFWqVP5VJyIiIiLyiHpgEJ8wYQIAqampjB8/3t5usVgoX748b7zxRv5VJyIiIiLyiHpgEN+5cycAY8aMYebMmflekIiIiIjI4+CBQfyOP4fwjIyMTH1Wq26+IiIiIiKSE9kO4sePHyc8PJyff/6Z1NRUAAzDwGKx8NNPP+VbgSIiIiIij6JsB/HQ0FBat27N9OnTKV68eH7WJCIiIiLyyMt2EP/999/517/+hcViyc96REREREQeC9le3N2uXTv279+fn7WIiIiIiDw2sn1FPDU1laFDh+Lr60u5cuUy9eluKiIiIiIiOZPtIP6Xv/yFv/zlL/lZi4iIiIjIYyPbQXzo0KH5WYeIiIiIyGMl20H8zqPus9K0adM8KUZERERE5HGR7SB+51H3d1y5coW0tDQ8PDzYsWNHnhcmIiIiIvIoy3YQv/Oo+ztsNhuLFy+mVKlSeV6UiIiIiMijLtfPpndwcGDw4MEsW7YsL+sREREREXks5DqIA3z11Vd6wI+IiIiISC5ke2lKq1atMoXu5ORkbt26RVhYWL4UJiIiIiLyKMt2EJ81a1am1yVKlODJJ5/ExcUlz4sSEREREXnUZTuIP/300wBkZGRw6dIlypUrh9X6UCtbREREREQeW9lO0klJSYwZM4a6devi5+dH3bp1GTt2LImJiflZn4iIiIjIIynbQXzq1KkkJycTFRXFkSNHiIqKIjk5malTp+ZnfSIiIiIij6RsL03Zt28f27dvp0SJEgA8+eSTzJgxg3bt2uVbcSIiIiIij6psXxF3dnbm8uXLmdquXLmCk5NTnhclkt/GjRtH06ZNCQgIsLe98847tGzZkqCgIIKCgtizZ0+2x97x0Ucf0bFjRzp16sTMmTMBiI6OJjAwkG7dunH69GkArl+/zssvv0xGRkben5yIiIgUCdm+Iv7888/z8ssv079/fypVqsT58+f54IMP6NGjR37WJ5IvunXrRt++fRk7dmym9v79+zNw4MBcjf3mm2/YsWMHGzZswMnJiYSEBABWrFjB+++/z7lz51i9ejWhoaEsXryYV199VRueRUREHmPZDuKvvfYaHh4eREVFceHCBSpUqEBwcLCCuBRJjRs35ty5c3k69tNPP+WVV16x/5aobNmyADg6OpKcnExKSgqOjo7ExsYSFxdHkyZNcn8CIiIiUuRl+3LctGnTePLJJ/nggw/YvHkzH3zwAV5eXkybNi0/6xMpUKtWrSIwMJBx48Zx7dq1HI09ffo0hw4dokePHvTt25cjR44A8OqrrzJ27FiWLl1K3759mTt3LiNGjMiH6kVERKQoyXYQ37hxI3Xq1MnUVqdOHTZu3JjnRYmYoXfv3nz55ZdERkZSoUIF3nrrrRyNt9lsXLt2jc8//5wxY8YwYsQIDMPAx8eHzz//nI8++oizZ89Svnx5DMNgxIgRjBo1ikuXLuXTGYmIiEhhlu0gbrFY7tpYZrPZtNlMHhnlypXDwcEBq9VKjx49OHr0aI7Ge3h40K5dOywWC3Xr1sVqtXLlyhV7v2EYLF68mCFDhvDuu+8yevRoXnjhBT766KO8PhUREREpArIdxBs1asT8+fPtwTsjI4N33nmHRo0a5VtxIgXpwoUL9q+3b9/OX//61xyNb9u2LQcPHgTg1KlTpKWlUaZMGXv/+vXr8fPzw83NjZSUFKxWK1arleTk5Lw5ARERESlSsr1Zc8KECbz66qu0aNGCSpUqERcXR/ny5VmyZEl+1ieSL0aOHMm3337LlStX8PPzY9iwYXz77becOHECgMqVKxMeHg5AfHw8b7zxBu+///49x/bo0YPu3bszfvx4AgICKFasGG+99RYWiwWA5ORk1q5dy7///W8ABgwYwCuvvEKxYsWYPXu2CZ+AiIiImM1iGIaR3YMzMjI4cuQIcXFxeHp62n/9nh0RERFs3bqV33//naioKLy9vQHw9/fHyckJZ2dnAEaNGkXLli0B+OGHH5g4cSKpqalUrlyZWbNm2e9Ecb++7IiOjsbX1zfbx4uIiOTWj2cuMvqTvWaXkW2z+vhRr1p5s8sQeSTcL3Nm+4o4gNVqpX79+tSvXz/HRbRp04Z+/frx4osv3tW3YMECezC/IyMjg9GjRzNjxgwaNWrEokWLmD17NjNmzLhvn8ifXb+Wyo2kW2aXkSOlXJwo/YSz2WWIiIhIPstREH8YOV1LfuzYMZydne3jevXqRZs2bZgxY8Z9+0T+7EbSLbZE/WJ2GTnSMdBbQVxEROQxUGBB/H5GjRqFYRj4+voycuRISpcuTVxcHJUqVbIf4+7uTkZGBlevXr1vn5ubmwlnICIiIiKSM6YH8VWrVuHp6cmtW7eYNm0a4eHhBbZ5LTo6ukDeR8zj6uJpdgk5lpiUyPnoonUVX0TuL9m5zIMPKkQSExOJjo41uwyRR57pQdzT83ZQcnJyok+fPrz22mv29vPnz9uPu3z5MlarFTc3t/v25URh3aw5btw4du/eTdmyZe0PTJo3bx47duzAarVStmxZZsyYgYeHx11jZ86cyZ49e8jIyKB58+ZMmDDBfucOgMGDB3Pu3Dn7vLNmzWLv3r34+Pgwc+ZMACIjI7ly5Qr9+/fP/5PNZ3G/JwJxZpeRI64urnjXrPTgA0WkyPjxzEWzS8gRV1dX6tWpYXYZIo+E+134zfZ9xPPDzZs3SUxMBG4/7GTz5s34+PgAt5/amZKSwqFDhwBYvXo1HTt2fGDfo6Bbt24sW7YsU1twcDBRUVFERkby7LPPsnDhwrvGff/993z//fds2LCBjRs3cvToUb799lt7/7Zt2yhVqpT9dWJiIjExMURFRVGsWDF+/vlnUlJSWLt2bZabakVEREQk7xTYFfGpU6eybds2Ll26xIABA3Bzc2PJkiUMGzbM/oROLy8vwsLCgNt3aJk5cyZhYWGZblH4oL5HQePGjTl37lymNhcXF/vXycnJma5y32GxWLh16xZpaWkYhkFaWhrlypUD4MaNG6xYsYIpU6YwYsQI+/Hp6ekYhkFKSgqOjo4sX76cl156iWLFiuXfCYqIiIhIwQXxN954gzfeeOOu9vXr199zTMOGDYmKispx36Nq7ty5rF+/HldXV1auXHlXf4MGDWjSpAktWrTAMAz69u2Ll5cXAPPnz+fll1+mePHi9uNdXFzw8/OjS5cuNG3aFFdXV44cOcI///nPAjsnERERkceVqUtTJGf+9a9/sWfPHgIDA/n444/v6j9z5gwnT55kz5497N27l2+++YZDhw7x008/ERsbS7t27e4aM2jQICIjIwkNDWX+/PmEhISwZs0ahg8fzqJFiwritEREREQeSwriRVBgYCDbtm27q/3LL7+kXr16lCpVilKlStGyZUsOHz7M4cOHOXbsGP7+/vTp04fTp0/z0ksvZRobExODYRg8+eSTbNmyhfnz53P27FlOnz5dQGclIiIi8nhREC8i/hyId+zYQY0ad+9mr1SpEt999x3p6emkpaXx3Xff4eXlRZ8+fdi/fz87d+7kk08+oXr16nz00UeZxs6fP5/hw4eTnp6OzWYDbq8hT0lJydfzEhEREXlcmX77QrnbyJEj+fbbb7ly5Qp+fn4MGzaMvXv3curUKSwWC5UrV2by5MkAHD16lNWrVzNt2jQ6dOjAN998Q2BgIBaLhZYtW+Lv7//A99u+fTt16tSx3w7Rx8eHwMBAvL29+dvf/pav5yoiIiLyuLIYhmGYXYQZoqOjC+19xCXvxP2eWCQfce9Z2dXsMkQkD/145iKjP9lrdhnZNquPH/WqlTe7DJFHwv0yp66Imyg1Po5bCUXrIQ9OZcvj7FH0nlYpIiIiUtgoiJvoVsJFfpkWanYZOeI94S0FcREREZE8oM2aIiIiIiImUBAXERERETGBgriIiIiIiAkUxEVERERETKAgLiIiIiJiAgVxERERERETKIiLiIiIiJhAQVxERERExAQK4iIiIiIiJlAQFxERERExgYK4iIiIiIgJFMRFREREREygIC4iIiIiYgIFcREREREREyiIi4iIiIiYQEFcRERERMQECuIiIiIiIiZQEBcRERERMYGCuIiIiIiICRTERURERERMoCAuIiIiImICBXERERERybVx48bRtGlTAgIC7G1Xr15lwIABtG/fngEDBnDt2rV7jk9KSsLPz4/w8HD766CgIPufJk2aMG3aNAA+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m2nTpjFw4ED279/PgQMHmDx5Mt9//z1paWlml2dns9nMLkFExBQK4iIij6DExEQWLFhAWFgYHTt2xMXFBYvFQq1atXj77bdxcnLi1q1bRERE8Oyzz9KsWTMmTpxISkoKAAcPHsTPz49///vfNG3alBYtWvDFF1/Y579y5QqDBw+mYcOGPP/888TGxmZ6/5MnTzJgwACefvppOnTowObNm+19oaGhhIWFMWjQIOrXr8/BgwcL5kMRESlkFMRFRB5Bhw8f5tatW7Rp0+aex8yePZtTp06xfv16tm3bxoULF1i4cKG9/9KlSyQmJrJ3716mTZtGeHg4165dAyA8PBxnZ2f279/P9OnTM4X0mzdv8vLLLxMQEMCBAweYO3cukydP5v/+7//sx2zcuJHBgwfz/fff4+vrmw+fgIhI4acgLiLyCLpy5QplypTB0fH/bwXq1asXjRo1om7dunz77bd8/vnnjB8/Hjc3N1xcXHj11VfZtGmT/XhHR0f++c9/UqxYMVq1akXJkiU5deoUNpuNbdu2ERISQsmSJfH29qZr1672cbt376Zy5cp0794dR0dHatWqRYcOHdiyZYv9mDZt2uDr64vVasXZ2blgPhQRkUJGmzVFRB5Bbm5uXLlyhfT0dHsYX716NQB+fn5cunSJ5ORkunXrZh9jGAYZGRmZ5vhzkC9RogQ3b97k8uXLpKen4+npae+rVKmS/evff/+dI0eO0KhRI3ubzWajc+fO9td/Hisi8rhSEBcReQQ1aNAAJycnduzYQYcOHe7qL1OmDMWLF2fTpk14eHjkaG53d3ccHR2Ji4vDy8sLgLi4OHu/p6cnjRs3ZsWKFQ93EiIijzgtTREReQSVLl2af/7zn0yePJktW7aQlJRERkYGP/30E8nJyVitVnr06MH06dNJSEgAID4+nn379j1wbgcHB9q1a8e7775LcnIy//d//8e6devs/c8++yynT59m/fr1pKWlkZaWxpEjRzh58mS+na+ISFGkK+IiIo+oQYMG4eHhwbJlyxg7diwlSpSgatWqjBo1igYNGlC/fn0WLlzICy+8wJUrV/Dw8KB37960bNnygXNPnDiRcePG0bx5c2rUqEG3bt3sdz9xcXFh+fLlvPXWW7z11lsYhkHNmjUZN25cfp+yiEiRYjEMwzC7CBERERGRx42WpoiIiIiImEBBXERERETEBAriIiIiIiImUBAXERERETGBgriIiIiIiAkUxEVERERETKAgLiIiIiJiAgVxERERERETKIiLiIiIiJjg/wGqSdgZfq/DtAAAAABJRU5ErkJggg==
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Aqui é possível verificar a mais detalhadamente a distribuição de renda dos clientes.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[124]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">pltCountplotHueTarget</span><span class="p">(</span><span class="n">colunas</span><span class="p">,</span> <span class="n">alvo</span><span class="p">):</span>
    
    <span class="n">fig</span><span class="p">,</span> <span class="n">axis</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">colunas</span><span class="p">)</span> <span class="o">//</span> <span class="mi">3</span><span class="p">,</span><span class="mi">3</span><span class="p">,</span> <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">24</span><span class="p">,</span><span class="mi">12</span><span class="p">))</span>  

    <span class="n">index</span> <span class="o">=</span> <span class="mi">0</span>
    <span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="nb">len</span><span class="p">(</span><span class="n">colunas</span><span class="p">)</span> <span class="o">//</span> <span class="mi">3</span><span class="p">):</span>
        <span class="k">for</span> <span class="n">j</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">3</span><span class="p">):</span>
            
            <span class="n">ax</span> <span class="o">=</span> <span class="n">sns</span><span class="o">.</span><span class="n">countplot</span><span class="p">(</span><span class="n">colunas</span><span class="p">[</span><span class="n">index</span><span class="p">],</span> <span class="n">data</span><span class="o">=</span><span class="n">df</span><span class="p">,</span> <span class="n">hue</span><span class="o">=</span><span class="n">alvo</span><span class="p">,</span> <span class="n">ax</span><span class="o">=</span><span class="n">axis</span><span class="p">[</span><span class="n">i</span><span class="p">][</span><span class="n">j</span><span class="p">])</span>
            
            <span class="n">ax</span><span class="o">.</span><span class="n">legend</span><span class="p">(</span><span class="n">title</span><span class="o">=</span><span class="s1">&#39;Saída do cliente?&#39;</span><span class="p">,</span>
                      <span class="n">loc</span><span class="o">=</span><span class="s1">&#39;upper right&#39;</span><span class="p">,</span>
                      <span class="n">labels</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;Sim&#39;</span><span class="p">,</span> <span class="s1">&#39;Não&#39;</span><span class="p">])</span>
            
            <span class="k">if</span> <span class="n">colunas</span><span class="p">[</span><span class="n">index</span><span class="p">]</span> <span class="ow">in</span> <span class="p">[</span><span class="s1">&#39;Education_Level&#39;</span><span class="p">,</span> <span class="s1">&#39;Income_Category&#39;</span><span class="p">]:</span>
                <span class="k">for</span> <span class="n">item</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">():</span>
                    <span class="n">item</span><span class="o">.</span><span class="n">set_rotation</span><span class="p">(</span><span class="mi">15</span><span class="p">)</span>
                
            <span class="k">for</span> <span class="n">p</span> <span class="ow">in</span> <span class="n">ax</span><span class="o">.</span><span class="n">patches</span><span class="p">:</span>
                <span class="n">height</span> <span class="o">=</span> <span class="n">p</span><span class="o">.</span><span class="n">get_height</span><span class="p">()</span>
                <span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="n">p</span><span class="o">.</span><span class="n">get_x</span><span class="p">()</span><span class="o">+</span><span class="n">p</span><span class="o">.</span><span class="n">get_width</span><span class="p">()</span><span class="o">/</span><span class="mf">2.</span><span class="p">,</span>
                        <span class="n">height</span> <span class="o">+</span> <span class="mi">3</span><span class="p">,</span>
                        <span class="s1">&#39;</span><span class="si">{:1.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">height</span><span class="o">/</span><span class="nb">len</span><span class="p">(</span><span class="n">df</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">),</span>
                        <span class="n">ha</span><span class="o">=</span><span class="s2">&quot;center&quot;</span><span class="p">)</span> 
            <span class="n">index</span> <span class="o">+=</span> <span class="mi">1</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[125]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">pltCountplotHueTarget</span><span class="p">(</span><span class="n">colunas</span><span class="p">,</span><span class="s1">&#39;Attrition_Flag&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>posx and posy should be finite values
posx and posy should be finite values
posx and posy should be finite values
posx and posy should be finite values
posx and posy should be finite values
posx and posy should be finite values
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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GrNz584cOHAgT59DRETyzhdffIGbmxv169fPErvda84/HT16lNKlS1OnTp1M19PT03n55Zfp27cvNWvWBKBr165s2bKFuXPnsmbNGvr168eePXsYOXIkM2bMsOu2AcqvIve2GzduMHLkSMaPH0+5cuUwm81cu3aNDz/8kHHjxvHSSy9htVpzPN6aNWtYtWoVe/bs4cknn2TmzJlAwf4eEimqlGPvbSoA38O++eYbatSogZubGyVKlKBdu3Z8//33triDgwOdO3dmx44dWfo6Ojoyfvx4wsLCWL58OYmJidSuXTtTm5IlS9K6detMH48BiImJsR32sX37dhYtWsRvv/3GmTNn7LFMkSLr0KFD9OrVCx8fH/71r3/Rq1evbO9ayM6qVato2rQpbdu2tfMs7W/btm22LWnuxptvvmk7QCgntm/fTteuXWnSpAlBQUE5/tqLiBQ33333HVFRUfj7+/Pyyy+zf//+TL9v/+k155/+uv3DX7322mvUrl072wOF4+Li+OGHH2jTpg3vvPMOCxYswMXFhX379v3jfJVfMyi/SlGTlpbGyJEjCQwMpF27dkDG3bxt27bFYDDQoEEDjEYjV65cydTP3d2dixcv2h7HxcXh7u5OQkICx48fp2HDhgB06tQp0/vpP9vm5veQSFGlHJuhKOZYFYDvYdWqVePo0aMkJydjtVrZt28fnp6enD17FsjYtygqKooHHnggS9/k5GRu3rwJwNdff42DgwMPPvggN27c4NKlS0DGHRm7d+/O0n/RokWMGjWK9PR0zGYzAAaDIUd7v4lIhqSkJIYMGcIzzzzDt99+y549exg+fLht/7J/kp6eTunSpRk9enQ+zLTounz5Mq+//joHDx4kICCAkJCQgp6SiMg9afTo0ezZs4eoqCjmz5/Po48+ypw5c3L0mhMyDpH57LPPshSAFyxYQFJSEuPHj8+235+fOIOME63/PJciOTn5lnNVfi14yq9iD1arlQkTJvDAAw/Qv39/2/U2bdrY7sI7ffo0aWlpVKhQIVPfRx55hDNnzvDbb7+RmprKtm3b8Pf3x8XFhcTERE6fPg1kvC/+60GXkLvfQyJFlXJswbNnjlUB+B7WsGFD2rdvT7du3QgMDMRisdCzZ09eeeUVAgMDCQwM5NKlS7z44osA7Nq1i0WLFgEQHx9Pt27d6NixI//973+ZPXs2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chsTERGxJxWARURERERERP7CYDAwaNAgIiMjCQ8Pp2bNmsydOxeLxcLYsWOZNGkSkZGR+Pr6MnfuXIBcx0REROxNBWARERERERGRv3B1daVZs2a2x40aNeLChQscO3aMkiVL4uvrC0CvXr3Yvn07QK5jIiIi9uZY0BMQERERERERuVdZLBY2btyIv78/sbGxVKtWzRZzc3PDYrFw9erVXMdcXV1zPJfDhw/nyZoKE490k13GTUxM5GQx/HqKSPGkArCIiIiIiIjILbz++uuUKVOGZ555hs8//7xA5+Lj41Ogz18QEmOiibXDuM7OzlSr18AOI4uIFIx/+iOhCsAiIiIiIiIi2QgNDeXs2bOsWLECo9GIh4cHFy5csMUTEhIwGo24urrmOiYiImJv2gNYRERERERE5G/mz5/PsWPHWLp0KU5OTgDUr18fk8nEoUOHAHj//ffp0KHDXcVERETsTXcAi4iIiIiIiPzFzz//zMqVK6lduza9evUCoEaNGixdupTZs2czefJkUlJSqF69OnPmzAHAaDTmKiYiImJvKgCLiIiIiIiI/MVDDz3EiRMnso01adKE8PDwPI2JiIjYk7aAEBERERERERERESmiVAAWERERERERERERKaJUABYREREREREREREpolQAFhERERERERERESmiVAAWERERERERERERKaLyrQCckpLC5MmTadeuHYGBgbz22msAnD59mp49e9K+fXt69uzJmTNnbH1yGxMRERERERERERGRfCwAz5kzh5IlSxIZGUl4eDijRo0CYPLkyQQHBxMZGUlwcDCTJk2y9cltTERERERERERERETyqQB848YNtmzZwqhRozAYDABUqlSJ+Ph4YmJiCAgIACAgIICYmBgSEhJyHRMRERERERERERGRDI758SS//fYbrq6uLFmyhAMHDlC2bFlGjRpFqVKlcHd3x8HBAQAHBweqVKlCbGwsVqs1VzE3N7f8WJKIiIiIiIiIiIjIPS9fCsBms5nffvuNevXq8corr3D06FGGDBnCokWL8uPpb+nw4cN5Mo5HuilPximOEhMTOZlH3wcRERERERERERHJLF8KwB4eHjg6Otq2bGjYsCEVKlSgVKlSxMXFYTabcXBwwGw2c+nSJTw8PLBarbmK3QkfH588WV9iTDSxeTJS8ePs7Ey1eg0KehoiIlnk1R8JRURE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6GjS0tK47777MBqNuLm50a1bN4KCgjh37hwWiwVvb+/8WtJtqQAsIiIiIiIiIiIixYKDgwNhYWFcv36dF198kZMnT1KnTh1bvFWrVgQEBODk5MT777/PK6+8wrp162zxS5cuMXbsWEJDQzEaM45XmzBhgi0+ZMgQpk6dyvLlyzl+/DjNmzenR48e+bfAbOgQOBERERERERERESlWXFxcaNasGXv37s10vUKFCjg5OQHw9NNP8+OPP9piSUlJvPDCC/znP//Jsm8wwM6dO/H29ubmzZucO3eORYsWERkZSXJysl3XcjsqAIuIiIiIiIgUc6kWCxNjzhPy42+MPXaOlRs/yNomNZWXXnqJtm3b8vTTT3P+/HkAvv76a5588kkCAwN58skn2bdvn639wIEDCQgIYP369bZxXnvttUwFFRGR/JKQkMD169cBMJlMfPPNNzzwwAOZ2ly6dMn276ioKDw9PYGM32kvvvgiQUFBdOjQIcvYaWlprF27lkGDBpGSkmLbW9hsNpOWlmavJeWItoAQERERERERKeZKGAxMrFuNUg5G0i1WQr8/wpEjRzLd4bZp0yZcXFz4/PPP2bZtG3PnzmXhwoVUqFCB5cuX4+7uzsmTJxk4cCB79+5l7969+Pj4MGTIEHr37k2fPn04fvw4ZrP5ntobU0SKj0uXLhESEoLZbMZqtdKhQwdatWrFokWLqF+/Pq1bt+bdd98lKioKBwcHypcvz8yZMwH47LPPOHToEFevXuWTTz4BYNasWXh5eQGwfv16unXrRunSpalbty4mk4nAwED8/PxwcXEpsDWDCsAiIiIiIiIixZ7BYKCUw//frWa1km422+5e+1NUVBTDhw8HoH379kybNg2r1Uq9evVsbR566CFSUlJITU3F0dERk8lEeno6VqsVgIULFzJ16tR8WpWISGYPP/wwW7ZssT1OiYslMSaaAW1bAZAYE83gjm0Z3LHt/zql3CAxJhr/h+5n/6aNmQe0ppEYEw1A9381sY0BMPOVsZR0z3x4XEHJlwJwaGgokZGR/P7774SHh9s2Vj59+jQhISFcvXoVV1dXQkNDqV279l3FREREREREROTOWaxWJsSc52JKGj2DutCwYcNM8bi4ODw8MooZjo6OODs7c+XKFdzc3GxtIiMjqVevHk5OTjRv3pytW7fSo0cPBg4cyK5du/D29sbd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Z8aNG8ezzz6bbwXgE0kmvopPomZpJ1798TdK/mcMY8ZP4MKFCwD07t2byMhINm7ciIODA6VKlWL+/PkYDAYuXbpESEgIZrMZq9VKhw4daNWqlW3s9evX061bN0qXLk3dunUxmUwEBgbi5+eHi4tLvqxPxJ5UABYRERERERERKeRycofs2bNnue+++zAYDPz444+kpqZSoUIF212+AJs3b+bYsWOZir/Xrl1j9+7drF69mqioKAwGAwaDAZPJZO9l2TzsXJoNvp62x5XeWMFVY2lca9cDMg7UfqRlex5p2T5Tv6NnL0Ppikxd9N+s1/9f41adbdequJRm/vz59lqGSIFQAVhEREREREREpJDL6R2yYWFhODo6UqpUKRYsWJDpILhbWbp0KUOGDMFoNNKyZUs2bNhAYGAgvXr1sveybineZCZky548H3dOsB8eFbJunSFSmKkALCIiIiIiIiJSyOXkDtlm7bvRrH23TP3+eicsgKdPSzx9Wma63rnP87a2VVxK8/bbb9trGSJiByoAi4iIiIiIiIgUMbpDtvBZefoS31+7gYujA1uyiR84cIBhw4ZRo0YNIONAv+HDhxMbG8u4ceOIj4/HYDDQo0cPnn32WQDmzJnDnj178PLyYvbs2QCEhYVx5coVnnvuufxZmBQ4FYBFREREREREREQKmF8lZ9pVKc/y03G3bOPr68vKlSszXXNwcCAkJARvb2+SkpLo3r07zZs3x93dnZiYGMLDw5kwYQInTpygVq1abN68mbfeesvey5F7iLGgJyAiIiIiIiIiIlLceTmXppzjnZfqqlSpgre3NwDlypXjgQceIC4uDoPBQHp6OlarFZPJhKOjI6tXr6Zv376UKFEir6cv9zAVgEVERERERERERAqBI0eO0KVLFwYNGsTPP/+cJX7+/Hl++uknGjZsSLly5fDz86Nr165UrlwZZ2dnoqOjadOmTQHMXAqStoAQERERERERERG5x3l7exMVFUXZsmX58ssvefHFF9mxY4ctfuPGDUaOHMn48eMpVy5jn+bnn3+e55/POMRvwoQJjBw5kk2bNvHVV19Rt25dhg0bViBrkfylO4BFRERERERERETuceXKlaNs2bIAPP7446Snp5OQkABAWloaI0eOJDAwkHbt2mXpGxMTg9Vq5f7772f79u0sWrSI3377jTNnzuTnEqSAqAAsIiIiIiIiIiJyj7t8+TJWqxWA6OhoLBYLFSpUwGq1MmHCBB544AH69++fbd9FixYxatQo0tPTMZvNABgMBkwmU77Nvzg4eu0mo384x39+OMuajz/JEv/999959tlnCQwMpG/fvly8eDFTPCkpCT8/P6ZNmwZAamoqAwcOJCAggPXr19vavfbaa/z44485npe2gBARERERERERESlgb/4ax0+JySSmm+nw/FCe6juIdHM6AO0CurI97GN2RHyCg4MDTk4lGTZuEtHn/uD4saOEhYVx3/2efNmxMwC9B7xAk389BsC3X++hUo37uWgygimFmvd7EhgYSJ06dXj44YfzdY1Hr91k3bk/cBg6nJ59nmHw4MGZ4r///jvjx48nISEBV1dX5syZQ9WqVQEYOHAgR48excfHh5UrV9r6jB49mpMnT9KqVStefvllAJYtW0adOnXydb9ji9XKO+cu82qdalQs4cjrX31Nx19+4cEHH7S1CQ0NpWvXrnTr1o19+/Yxb9485syZY4svXLiQpk2b2h7v3bsXHx8fhgwZQu/evenTpw/Hjx/HbDbbDv7LCRWARURERERERERECtiIB9xt/zZMXErIlu9sjz/fsAeojEOrjIJpKvDW0StwdA8AtZ6bkWmsjb+ksfGXPf+74PgQBzdkPJ7z3BBen/yafRbxD/5aIH30tVk899pU/P39c1wgHTRoEMnJyXzwwQe29sePH6dUqVKEh4fTv39/EhMTSU5OJjo6Ot/3N/7lRgruJUvgXrIEAO1aNGfXrl2Z1nfq1CleffVVAB599FFefPFFW+zYsWPEx8fTsmVLjh07BoCjoyMmk4n09HTb3d8LFy5k6tSpdzQ3bQEhIiIiIiIiIiIidvXXAmmJEiXo3Lkzu3btytTm1KlTPProo0BGgfSv8ccee8y2B/KfSpQogclkwmKxkJ6ejtFoZPHixYwYMcL+C/qbK6npVHT63722VSq6ERcXl6nNww8/bDu47/PPP+fGjRtcuXIFi8VCaGgor7zySqb2zZs35/fff6dHjx707duXXbt24e3tjbu7O3dCBWARERERERERERGxq78XSN3d3XNcIL0VT09P3Nzc6NatG61ateLcuXNYLJY72h4hP40bN46DBw/StWtXvv32W9zd3XFwcGDDhg34+fnZtrv4k6OjI/PmzWPLli106NCBtWvX0r9/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iMizp3fv3nh6erJw4ULeffddHB0dKViwIMOHD6dSpUpUrFiROXPm8MorrxAeHo6npyedOnWiTp06D9332LFjee+996hVqxbFihWjffv2xmStLi4uLFq0iKlTpzJ16lQsFgslS5bkvffeS+9TFpGnWO3atVmwYAFhYWFGibQqVaowYsQIPDw8sLe3TzHzvL29PZcvX6ZatWoMHTqUnDlzZlbXhWe3Bq48XRo2bMiiRYsoVKgQv/32G/nz5+ftt99OMaF8mTJlmDlzJs7OzoSGhnLjxg3+/vtvdu7cSevWrTGbzZQuXZovvvgCb2/vTK8RLo/OZLk7ZS8i8pT4888/GT9+PH/88Udmd0VEREREJNMMHTqUIUOGULBgQeDeMg7Jl/RZbQTes+Lvv/9mx44dlCpV6pmpgStPl5iYGGrXrk3lypWpWbMmTZo0wd7engYNGrBkyRLKlCnDqVOnGD9+PPPnz+fy5ct8+umneHh4UKNGDRo1aoS9vf1TXzNc/psSwCLyVIiJiWH37t3UqlWL0NBQ3nrrLSpUqMDo0aMzu2siIiIiIk8VJWJE5FG89NJLfPjhhynqac+bN48TJ05w9epVIiIiGDZsGI0aNUoxZ5BkH0oAi8hD7du3j969e9+37cCBA0/kGNHR0XTp0oWzZ8/i4OBA/fr1GT16tDHrqIiIiIjIsyoxMVGl0UQkzb766isiIiIYOnRoigTv6dOnSUxMpFSpUpncQ0lvSgCLiIiIiIiIiIhkU6dPn+arr75i8uTJGt37jFICWERERERERERERCSbUtpfREREREREREREJJtSAlhEREREREREREQkm1ICWERERERERERERCSbUgJYREREREREREREJJtSAlhEREREREREREQkm1ICWERERERERERERCSbUgJYRERERERERETu6/Lly5QsWZKEhIQMPe7q1avp2bNnhh4zvfn5+bFjx47M7oY8g5QAFhERERERERF5xvj5+VG+fHkqVapk/Ddx4sRM6cv9ksytW7fmq6++ytBjimRXNpndARERERERERERyXjz5s2jZs2amd0NEUlnGgEsIiIiIiIiIiIAJCYmMm3aNKpXr06DBg34888/U7T/u4zB559/zvDhw43X+/bto2PHjvj6+lKvXj1++eUXALZs2ULbtm2pXLky9erV4/PPPze26dKlCwBVq1alUqVKHDhwgF9++YVOnToZ6/z111+89NJLVKlShZdeeom//vrLaOvatSuffPIJHTt2pFKlSvTs2ZOwsLA0vweRkZGMGjWK2rVrU6dOHT7++GMSExOJi4vD19eXU6dOGeuGhYVRvnx5QkNDAfjjjz9o06YNvr6+dOzYkRMnTqS5HyJPihLAIiIiIiIiIiICwLJly/jjjz9YtWoVK1as4Ndff031tleuXKF379506dKFnTt3smrVKkqXLg2Ao6Mj06ZNY9++fcyfP58ff/yR33//HYDvv/8egL1793LgwAEqVaqUYr8RERH07duXrl27snv3bnr06EHfvn0JDw831lm7di1Tpkxh586dxMfHP1b5iJEjR2JjY8PGjRtZtWoV27dvZ/ny5djZ2dGoUSPWrVtnrLthwwaqVq2Kh4cHx44dY9SoUUycOJHdu3fz6quv0r9/f+Li4tLcF5EnQQlgEREREREREZFn0IABA/D19TX+W7ZsGRs2bOD111/Hy8sLNzc3+vbtm+r9rV27lpo1a9KyZUtsbW3JlSuXkQCuXr06JUuWxMrKilKlStGiRQv27NmTqv1u2bKFwoUL07ZtW2xsbGjZsiXFihXjjz/+MNZp3749RYsWxcHBgaZNm3L8+PFHezP+340bN/jzzz8ZNWoUTk5OeHh40L17dyPp26pVqxQJ4DVr1tCqVSsAfvrpJ1599VUqVKiAtbU17dq1w9bWloMHD6apLyJPimoAi4iIiIiIiIg8g+bMmXNPDeCvvvoKLy8v43X+/PlTvb/g4GAKFSp037ZDhw4xc+ZMTp8+TXx8PHFxcTRt2jRV+7127do9/cifPz8hISHG6zx58hg/Ozo6cufOnVT3+25BQUEkJCRQu3ZtY5nZbDbek+rVqxMTE8OhQ4fw8PDgxIkTNGzY0Nh21apVxohmgPj4eK5du5amvog8KUoAi4iIiIiIiIgIkJRIDQ4ONl7f/TMkJVejo6ON19evXzd+9vLy4vDhw/fd77Bhw+jSpQsLFy7E3t6eyZMnGyUcTCbTf/Ypb968BAUFpVgWHBxMnTp1UndSjyBfvnzY2dmxa9cubGzuTZtZW1vTtGlT1q5dS+7cualfvz4uLi5A0vn369ePN99884n3S+RxqASEiIiIiIiIiIgA0KxZM7777juuXr3KzZs3WbBgQYr2UqVKsX79euLj4zly5AgBAQFGW6tWrdixYwfr168nISGB8PBwoxTD7du3yZkzJ/b29hw+fJi1a9ca27m7u2NlZcWlS5fu26d69epx/vx51qxZQ0JCAuvXr+eff/6hfv36j32+cXFxxMbGGv/lzp2bWrVqMXXqVKKiojCbzVy8eDFFuYpWrVqxYcMG1qxZQ8uWLY3lHTp0YOnSpRw6dAiLxcKdO3fYsmULUVFRj91PkcehEcAiIiIiIiIiIs+gfv36YW1tbbyuWbMmn376KefPn6dNmzY4OzvzxhtvsGvXLmOdt99+m6FDh1KtWjWqVq1Kq1atiIiIAJLKMnz55ZdMmzaN999/H1dXV95++21Kly7NuHHjmDZtGhMnTqRatWo0a9aMW7duAUmjivv160enTp1ISEhg4cKFKfqZK1cu5s2bx4cffsj48eMpXLgw8+bNw93d/bHfg39POLd48WKmT5/OzJkzad68Obdv36ZgwYL07t3bWKdChQo4Ojpy7do16tatayx//vnnmTRpEhMnTuTChQs4ODhQuXJlfH19H7ufIo/DZLFYLJndCRERERERERERERF58lQCQkRERERERERERCSbUgkIERERERERERHJdlavXs24cePuWZ4/f37WrVuXCT0SyRwqASEiIiIiIiIiIiKSTT2zI4D379+f2V0QEZGnXJUqVTK7C1mO4quIiDyM4mvaKMaKiMjDPCjGPrMJYNAfHiIi8mC6yEo7xVcREXkQxdfHoxgrIiIP8l8xVpPAiYiIiIiIiIiIiGRTSgCLiIiIiIiIiIiIZFNKAIuIiIiIiIiIiIhkU0oAi4iIiIiIiIiIiGRTz/QkcCIiT8qdO3eIiorCZDJldlfkEVhZWeHu7p7lP7f+/ftz+fJlrKyscHJyYsyYMZQuXZpz584xcuRIIiIicHNzY9q0aRQpUgQgzW0iIhnJYrEQFhaG2WzO7K7II8ouMVZEJLtSjM2a0hpflQBOhdjYWF577TXi4uJITEykSZMmDBo0iJ07dzJ9+nTi4+MpW7YskydPxsYm5Vt6/Phxxo8fT1RUFFZWVrz55ps0b94cwNjebDbj5OTE1KlTKVy4MN999x0//fQTXl5ezJkzBzs7O/bt28fGjRsZNWpUZrwFIvIfIiIiAMiTJ48ucrKYmJgYwsLC8PDwyOyuPJZp06bh6uoKwO+//86oUaNYuXIl48aNo3PnzrRp0wZ/f3/Gjh3Lt99+C5DmNkm94OBg3nnnHUJDQzGZTLzyyiu8/vrrnDhxgnHjxnHnzh28vb2ZOXMmLi4u92z/3nvvsWXLFjw8PFi7dq2xfNq0afzxxx/Y2tpSqFAhpkyZQo4cOdi/fz/jx4/H1taWWbNmUaRIEW7dusXbb7/NwoULsbLSg1+S9YSFheHs7IyDg0Nmd0UeUXaJsVnV2bNnGTJkiPH60qVLDBo0iOrVqzNu3DhiY2OxtrZm/PjxlC9f/p7t33jjDQ4dOkSVKlWYP3++sVzXsCLZh2Js1pTm+Gp5Ru3bty/V65rNZktUVJTFYrFY4uLiLC+//LJl//79lrp161rOnj1rsVgslk8++cSybNmye7Y9e/as5dy5cxaLxWK5evWqpVatWpabN29aLBaLpXHjxpZ//vnHYrFYLN9//73l3XfftVgsFkuHDh0siYmJljlz5lg2bdpkMZvNlp49e1rCw8PTeroiko6uXbuW2V2Qx/Cgz+9R4sTTZOXKlZZ27dpZbty4YalSpYolISHBYrFYLAkJCZYqVapYQkND09yWGln1fUsPISEhlqNHj1osFoslMjLS0rhxY8vp06ct7du3t+zevdtisVgsy5cvt3z88cf33X7Pnj2Wo0ePWlq0aJFi+datWy3x8fEWi8VimT59umX69OkWi8ViGTBggCU4ONiyd+9ey5QpUywWi8UydepUy65du9Lj9EQyhGJs1na/zy8rxYnNmzdb2rRpY2ndurWlVatWloCAAIvFknSN98orr1gaN25seeWVV4zrvcdpS420vncJCQmWmjVrWi5fvmzp0aOHZcuWLRaLxWLZsmWLpUuXLvfdZseOHZZNmzZZ+vTpk2K5rmFFsg/F2KwrLdewGgGcCiaTCWdnZwASEhJISEjA2toaW1tbihYtCkCtWrWYP38+HTp0SLFtcjuAp6cn7u7uhIWFkSNHDgCioqKM/+fNmxdIGoafkJBATEwMNjY2+Pv7U6dOHdzc3NL7VEVEJIsaPXo027dvx2KxsHDhQoKDg/H09MTa2hoAa2tr8ubNS3BwMBaLJU1t7u7uqerL/v370+cks6jk98PDw4Nt27Zx5swZrKys2L9/Pzly5GD16tXUqVPnnu2srKy4dOkS0dHRKd5TR0dHDh06BICrqyu7d+9m//79REZGsm/fPq5fv86NGzdYv349x44do2HDhvpMJMtycXHByckps7shaRQWFsbFixczuxtpYrFYeOedd1iyZAklSpTgxIkTdOrUiYYNG2a5J2x27txJwYIF8fb2xmQycfv2bQAiIyONa9B/q1GjBrt3775vm65hRUSyngxPAM+ePZvPP/+cNWvWUKJECQ4ePMjYsWOJjY3F29ubGTNmGMOY09qWHhITE2nfvj0XL16kc+fOlC9fnsTERI4cOcLzzz/Pr7/+ytWrV/9zH4cPHyY+Pp5ChQoBMHnyZPr06YO9vT0uLi4sW7YMgNdee41XXnmF4sWLU7lyZfr378+iRYvS7dxERCTrmzx5MgCrVq1i+vTpDB48ONP6UqVKlUw79tPq8uXLBAUF8fLLL/Prr78SERFBw4YNWbx4MeHh4Q98zy5fvoyjo+MD27/88kvatm1LlSpVGDlyJOPGjcPe3p4ZM2Ywbdo0JkyYoPrNkqVdv37dGIghWY+7uzslS5ZMsSwr3ZCysrIiMjIS+F+yNDw8nGPHjrF48WIAWrZsyaRJkwgLC8NisaSpLbU3WNNq3bp1tGzZEoBRo0bxxhtvMG3aNMxmM0uXLn2kfekaVkQka8rQBPDff//NwYMH8fb2BsBsNjNixAimTJmCr68vc+fOZebMmUyZMiXNbenF2toaf39/bt26xYABAzh9+jSzZs1iypQpxMXFUatWrf+srXft2jVGjBjBtGnTjPW+/vprFixYQIUKFVi4cCFTpkxh8uTJtG3blrZt2wJJCfNu3boRGBiIv78/+fLlY+TIkarjJ5LNJSYm0rFjR/r06UOjRo1StO3evZsRI0YQGBj42Md5kvt60D5btGjB2LFjqV69+hM7hjxY27ZtGTt2LPny5SMkJITExESsra1JTEzk2rVreHl5YbFY0tQmaXP79m0GDRrEqFGjcHFxYfLkyUyePJm5c+fi5+eHnZ1dmvb7xRdfYG1tTevWrQEoXbq0cSG+d+9e8uTJg8Vi4e2338bGxoaRI0eSO3fuJ3ZeIlmR4quklslk4pNPPqF///44OTlx+/ZtFixYkKlP2MCjJ9ATEhLYuHEjjRo1Yv/+/XzzzTe8+uqrVKtWjV27dvHWW28xevTo+2576tQpbt68meKYn3zyCUOHDqV48eKsWbOGYcOG0adPHwoWLMiYMWMAmDJlCjVr1mTx4sVs3boVDw8PXnvtNV3DijxlnvRTNomJifTo0YPu3bvj5+eXom3fvn28//77/Prrr499nCe5rwft8+WXX2bkyJH4+vo+sWM8SWl5wibDEsBxcXFMnDiRjz76iG7dugFw9OhR7O3tjTe0Y8eONGjQgClTpqS5Lb3lyJGD6tWrs3XrVt544w1++OEHALZt28b58+fvu01UVBR9+/ZlyJAhVKxYEUj6sE6cOEGFChUAaN68Ob169UqxXUhICEeOHGHgwIF06dKFb775hi+++IKdO3dSq1atdDtHEXky9u3bx8yZMzl9+jTW1tYUK1aMUaNG3XeijX9bsGABVatWvefiNCtat27dE9nP559/zoULF5g5c2aq1v/111+ZN28eFy9epGDBgkyaNClV731Wc/v2bW7dumUkaDdv3kzOnDnx8PCgdOnSrF27ljZt2rB27VpKly5tXGSmtU0eTXx8PIMGDaJVq1Y0btwYAB8fH7766isAzp07x5YtWx55v7/88gtbtmzh66+/vmfySYvFwhdffMGsWbOYNGkSI0aM4MqVK3z33XcpJgQSyaoUX5MovqavhIQE5s+fz9y5c6lSpQr79+/n7bffZvr06Znar0d9yub333+nQoUKRjKmT58+fPrpp5hMJipXrsyiRYseuM+EhAS2bdtmtIeFhXH16lVeffVVALy8vOjVq1eK7UNCQrhx4waTJ09OcQ2bPGhKRJ4e93vK5nFi7BdffEH16tVp1arVPW0ODg4pyqs+jie5rwftc8OGDU9kv+kVY+/3hA38903CDEsAf/rpp7Ru3ZoCBQoYy4KDg8mfP7/x2t3dHbPZTERERJrbHqXGUGrvnt66dQtra2ucnZ2Ji4tj48aNtGrVyrjIjo+PZ9asWbRt2/aefSYkJDBt2jSqVKlCnjx5jPbExETCw8NZu3YtXl5e/PHHH7i7u6fYfsGCBcad2tDQUP766y+Cg4OxtbXVLI0iT5H73TlNvvEzatQoGjVqRHx8PAcOHCAxMdGou/YgyXXG+/Xrd991Y2JisFgsD91PajzJfaXnPiHpRmJCQkKq93vlyhVGjx5NyZIl+e6773jnnXdYsWLFPetl5fqEANHR0QwePJjo6GisrKzImTMn8+bNw2QyMX78eEaOHMncuXPJkSMH06ZNM7ZLa5uknsViYfTo0RQrVowePXoYy0NDQ/Hw8MBsNvPFF1/QsWPHR9pvYGAgCxcu5Pvvv8fR0fGe9lWrVlG3bl3c3NyIiYnBysoKKysroqOjH/ucRDJbVFQU/fr1Y/z48TRr1oz4+Hj27duXqpH0CQkJODo60qdPnwzoafZ1/fp1Jk2aRJkyZfjqq68YOXIk69evz+xuPXHHjx/n2rVrRnKzSpUqODo6Ym9vn6WesFm3bh0tWrQwXufNm5c9e/ZQvXp1du3a9UhlgnLkyEFkZCTnzp2jaNGibN++HR8fnxTrfPrppwwaNAhI+pvQZDJhMpkUg0SyAMXYzJeeMTZDEsAHDhzg6NGjDB8+PCMOl2qpuXsaGxLM3/uDGPfZbMxmM2azhUa1atCxVnU+/fpbtu77C7PFzMtNm9DOtyIAx/45w4qAjYwZ8Cbrt+zkxIkTxN+OYvfWpMe1xg0aQOmiRRk3oB9zP/0EKysrXJ2dGTuwPwUcbQE4cfYcOaxNNClTAoC29esy9r2ReOb2YOgr7bGztcXOIw/2nnokVySz3e/O6dmzZzGZTLz00kvGsoYNGxo/X7x4kffff5+TJ08CULt2bcaNG2dMELl06VLKlStHzZo1iYmJYfz48WzatIk8efLQvn37FHcnFyxYwLJlywgNDcXLy4shQ4Y8cGTTw/Z15swZxo8fz/Hjx/H09GTo0KE0aNDgvvuKiIhg2rRpbN26ldjYWKpWrcrcuXPvuXvq5+fHBx98QM2aNTGbzSxcuJBly5YRGRnJCy+8wIQJE3Bzc+Py5cs0aNCAqVOn8umnnxIdHU337t158803CQwMZPHixVgsFv78808KFizI6tWriYyMZMqUKQQGBmIymWjfvj2DBg3C2tqaN954w+hrzZo1+fbbb+97lzgtd0+fJrlz5zYe+/83Hx8fli9f/kTbJPX279+Pv78/JUqUoE2bNgAMHTqUf44cZunPSTcjXnyhGo1LP0fkscNcDwtj0px5fDZmFACjPvqE/X//TcStSOrUrEGfjq/QtmEDJox5n/j4BF7vlJQ4LleiBKPeTPpjOyY2luXff8ecce8TGxJMjx496NOnD7a2tqkeeSDyNDt37hyAUc/U2tqa2rVrG+3/FV9tbGz49ttvKVGixAPj690eN77e7UnE1397UvF1/vz5WCwWNm3alKr42rVrV6MPvr6+LFy48GEfW5aUL18+rl69ytmzZylWrBhnzpwhNDSUwoULP/VP2MSGBBMXep3omBi2BwbyTudXiDx2GIBRb3Tnw/HjSDSbsbO1ZWTfXkQeO5ziGhag16gxnL9yheiYGOrUrMGYAW9So1JFRvftxYA+vVNcwybv+8TZc8RHhFHIlEjkscM0qlqFFo0b4Znbg461XyDy2GFdw4o8xRRj/yc7xtgMSQDv3buXM2fOGB/A1atXeeONN+jatStBQUHGemFhYVhZWeHm5oaXl1ea2p60uNDrWJZ8wXgPayCpXhP/7OfU5P00A5p5/f9I3MNbOXV4K5D0pr4KnJo8kuLAd5WKpNzpD/M5BXgDk/Im30mJ5c6ijzn1/6+sgI7/vw8AX8DX0x6I4vz0pNpKJUZPVfAUeUoVLVoUa2tr3n33XZo3b07FihXJmTOn0W6xWOjbty9Vq1YlKiqKt956i88///y+Ndhmz57NxYsX+e2334iOjqZ3794p2gsWLMiSJUvIkycPv/76KyNGjGDjxo33ndX5v/YVHx9Pv379eOmll1i0aBH79++nf//+rFixgmLFit2zr3feeQcnJyfWrVuHk5MTBw4ceOj78t133/H777/z/fff4+7uzgcffMDEiROZNWuWsc7+/fv59ddfOX/+PC+//DKNGzembt269O3b957HZ0aOHImHhwcbN24kOjqavn374uXllWJE5Z07d5g6dSrt2rV7aP9EniRfX1/jD+S7Vc6Ti4o7//+xsktHOf3he0bbQKv/xf7uQHcfD+D/J7nd/Rundv/G9AIuKXcYdtbYBmCYA5yd9j4lRk/F19eXNWvWPMGzEslciq/3p/j65OXJk4fx48czePBgo9TOhx9+iJub21P/hE1c6HUjLnxRypOgTyYZbU7AWHcrkq44LbD0S06R8hoW4B1noMRd3/X1Szm1fqmuYUWyMcXY+8suMTZDqrD36dOHbdu2sXnzZjZv3ky+fPlYtGgRvXr1IiYmhn379gFJI96aNm0KQLly5dLUJiLyNHBxceGHH37AZDIxZswYatSoQb9+/bhx4wYAhQsXplatWtjZ2eHu7k6PHj3Yu3fvffe1YcMG+vXrZ9wAu/uuIECzZs3w9PTEysqK5s2bU7hwYQ4fPvzI+zp06BB37tyhT58+2NnZUaNGDV588cX71hi8du0agYGBTJgwgZw5c2Jra0u1atUe+r4sXbqUIUOGkC9fPuzs7Bg4cCABAQEkJCQY6wwcOBAHBwdKlSpFqVKlOHHixH33dePGDf78809GjRqFk5MTHh4edO/e/Z7+vv322+TNm/epewpFREQeneLr/Sm+po/WrVuzZs0aVq9ezerVq42nuZKflAkICGD58uUpkgxpbRMRyWyKsfeXXWJshtUAvh8rKyumT5/OuHHjiI2NxdvbmxkzZjxWm4jI08LHx4epU6cCSY+ljBgxgg8//JBZs2YZk2Ps27eP27dvY7FYjPIP//bv+nB310CHpHqfixcv5sqVK0DS3cLw8PBH3te1a9fIly9fihma8+fPT0hIyD37uXr1Kjlz5kxxRzg1goKCGDBgQIpjWFlZERoaarzOnTu38bOjoyN37tx54L4SEhJSPJZkNptTnN+5c+fYu3cvO3bswMYmU0OeiIg8IYqv91J8FRGRJ0Ex9l7ZJcZmSrTevHmz8XPlypUf+GhiWttERJ42Pj4+tG/fnp9++gmAWbNmYTKZWLNmDW5ubvz+++9MnDjxvtvmyZOH4OBgnnvuOSBpAs1kV65c4f333+frr7+mUqVKWFtbG7VGH3VfefPm5erVq5jNZiO4BQcH33dykHz58nHz5k1u3br1wKB/P/ny5ePDDz+8bw32y5cv/+e2yY9f3r0vOzs7du3a9cDAeP36dVxdXe87UZaIiGR9iq//207xVUREniTF2P9tlx1ibIaUgBARedacOXOGr776iqtXrwJJQWjt2rVUqFABgNu3b+Pk5ISrqyshISH/Wdy9WbNmLFiwgJs3b3L16lW+++47oy06OhqTyWRMILJixQpOnz6dpn2VL18eBwcHFi5cSHx8PLt372bz5s00b978nv3kzZuXunXrMmHCBG7evEl8fPwDH/+5W6dOnfjkk0+MO71hYWH8/vvvD90OwMPDgytXrmA2m40+1KpVi6lTpxIVFYXZbObixYvs2bPH2KZixYqsWrUqVfsXEZGnn+Lr/Sm+iojI41KMvb/sEmOVABYRSQcuLi4cOnSIDh06ULFiRV555RVKlCjByJFJk2IMHDiQY8eO4evrS58+fWjcuPED9zVw4EDy589PgwYN6NmzZ4q7o8WLF6dnz5507NiRmjVrcurUKSpXrpymfdnZ2TFv3jwCAwONmU2nT5+Oj4/Pffc1ffp0bGxsaNasGTVr1uSbb7556PvSrVs3/Pz86NmzJ5UqVeKVV155YK2nf0uu9V69enWjGP706dOJj4+nefPmVK1alUGDBnH9+nVjm8OHD9OpU6dU7V9ERJ5+iq/3p/gqIiKPSzH2/rJLjDVZLBbLE99rFrB///77Dt/+t8hjh1PMrP00KTF6Kq5lymd2N0SeedevXydPnjyZ3Q1Jowd9fqmNE5KS3reHy6i/LfR3gmQHirFZ2/0+P8WJtNM1rIg8SYqxWVdarmE1AlhEREREREREREQkm1ICWERERERERERERCSbUgJYREREREREREREJJtSAlhEREREREREREQkm1ICWERERERERERERCSbUgJYREREREREREREJJtSAlhEREREREREREQkm7LJ7A6IiEjaxIYEExd6/Ynv184jD/aeXqlad8OGDcyfPx+LxUJsbCxly5blo48+ok2bNvz00084ODg88f6JiIikt8yOsYqvIiKSHWV2fIVnN8YqASwikkXFhV7n1OSRT3y/JUZPTVXwvHbtGhMmTGDlypV4eXlhsVg4fvw4AP7+/k+8XyIiIhklM2Os4quIiGRXuobNPEoAi4hImty4cQMbGxvc3NwAMJlMlClTBoCSJUvy119/4ezsjJ+fH61atWLXrl2EhIQwbNgwQkNDWbt2LTdv3uTDDz+katWqmXgmIiIiTw/FVxERkfTxLMdY1QAWEZE0KVWqFOXLl6d+/foMGjSIr7/+mvDw8PuuGxcXx08//cRnn33GmDFjsLW15eeff2bIkCHMmjUrg3suIiLy9FJ8FRERSR/PcoxVAlhERNLEysqKuXPn8t1331G9enX+/PNPWrduTURExD3rNm/eHICyZcsSHR1Ns2bNAChXrhwXL17MyG6LiIg81RRfRURE0sezHGOVABYRkcdSokQJXnvtNRYvXoyrqyt79uy5Zx17e3sArK2tU7y2srIiISEh4zorIiKSRSi+ioiIpI9nMcYqASwiImkSEhLCgQMHjNdXr14lLCyMAgUKZGKvREREsjbFVxERkfTxLMdYTQInIiJpkpCQwOeff86VK1dwcHDAbDbz9ttvG0X0RURE5NEpvoqIiKSPZznGKgEsIpJF2XnkocToqemy39Tw9vbmq6++um/byZMnjZ83b978wLYCBQqwe/fuNPRSREQk/WRmjFV8FRGR7ErXsJlHCWARkSzK3tMLe0+vzO6GiIhItqMYKyIi8uQpvmYe1QAWERERERERERERyaaUABYRERERERERERHJppQAFhER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bNmy+7YpeIqIiIiIiIiIiIikj0ypASwiIiIiIiIiIiIi6U8JYBEREREREREREZFsSglgERERERERERERkWxKCWARERERERERERGRbEoJYBEREREREREREZFsSglgERERERERERERkWxKCWARERERERERERGRbEoJYBEREREREREREZFsSglgERERERERERERkWxKCWARERERERERERGRbEoJYBEREREREREREZFsSglgERERERERERERkWxKCWAREZEsLDw8nN69e9OkSRNatWrFwIEDCQsLA+DgwYO0bt2aJk2a0LNnT0JDQ43t0tomIiIiIiIiWYsSwCIiIlmYyWSiV69eBAQEsGbNGgoWLMjMmTMxm82MGDGCsWPHEhAQgK+vLzNnzgRIc5uIiIiIiIhkPUoAi4iIZGFubm5Ur17deF2xYkWCgoI4evQo9vb2+Pr6AtCxY0d+/fVXgDS3iYiIiIiISNZjk9kdEBERkSfDbDbz448/4ufnR3BwMPnz5zfa3N3dMZvNREREpLnNzc0tVf3Yv3//Ezun7MgrISZDjhMZGckpfRYiIiIiIs88JYBFRESyiUmTJuHk5ESXLl347bffMq0fVapUybRjZwWRxw4TnAHHcXV1JX+Z8hlwJBGR1NNNQhERkYynBLCIiEg2MG3aNC5cuMC8efOwsrLCy8uLoKAgoz0sLAwrKyvc3NzS3CYiIiIiIiJZj2oAi4iIZHGzZs3i6NGjzJkzBzs7OwDKlStHTEwM+/btA2Dp0qU0bdr0sdpEREREREQk69EIYBERkSzs9OnTzJ8/nyJFitCxY0cAChQowJw5c5g+fTrjxo0jNjYWb29vZsyYAYCVlVWa2kRERERERCTrUQJYREQkC3vuuec4efLkfdsqV67MmjVrnmibiIiIiIiIZC0qASEiIiIiIiIiIiKSTSkBLCIiIiIiIiIiIpJNKQEsIiIiIiIiIiIikk0pASwiIiIiIiIiIiKSTWkSOBEREREREZF/8fPzw87ODnt7ewCGDx9OnTp1OHjwIGPHjiU2NhZvb29mzJiBh4cHQJrbRERE0lOGjAAODw+nd+/eNGnShFatWjFw4EDCwsIAKFmyJK1ataJNmza0adMmxUzmmzdvpmnTpjRq1Ii3336b6OjoVLWJiIiIiIiIPK7PPvsMf39//P39qVOnDmazmREjRjB27FgCAgLw9fVl5syZAGluExERSW8ZkgA2mUz06tWLgIAA1qxZQ8GCBVMEu6VLlxpBtWTJkgDcvn2bMWPGMG/ePH777TecnZ1ZtGjRQ9tERERERERE0sPRo0ext7fH19cXgI4dO/Lrr78+VpuIiEh6y5ASEG5ublSvXt14XbFiRX788cf/3CYwMJBy5cpRpEgRIClAjhw5koEDB/5nm4iIiIiIiMiTMHz4cCwWC1WqVGHo0KEEBweTP39+o93d3R2z2UxERESa29zc3FLdn/379z90Ha+EmFTvL6NFRkZyKhXnICIiT1aG1wA2m838+OOP+Pn5Gcu6du1KYmIidevW5a233sLOzu6eAJk/f36Cg4MB/rPtUSh4Zh36HEREREREJCMtWbIELy8v4uLimDx5MhMnTqRRo0aZ2qcqVao8dJ3IY4d59KvjjOHq6kr+MuUzuxsiItnSf+U5MzwBPGnSJJycnOjSpQsAW7ZswcvLi6ioKEaMGMGcOXMYMmRIhvRFwTPr0OcgIhktNTcJRUREJPvy8vICwM7Ojs6dO/Pmm2/SrVs3goKCjHXCwsKwsrLCzc0NLy+vNLWJiIiktwypAZxs2rRpXLhwgU8++QQrq6RDJwdVFxcXOnTowF9//WUsvztABgUFGev+V5uIiIiIiIjI47hz5w6RkZEAWCwW1q9fT+nSpSlXrhwxMTHs27cPSJrPpmnTpgBpbhMREUlvGTYCeNasWRw9epQFCxZgZ2cHwM2bN7G3t8fBwYGEhAQCAgIoXbo0AHXq1GHSpEmcP3+eIkWKsHTpUpo1a/bQNhEREREREZHHERoayltvvUViYiJmsxkfHx/GjRuHlZUV06dPZ9y4ccTGxuLt7c2MGTMA0twmIiKS3jIkAXz69Gnmz59PkSJF6NixIwAFChSgV69ejB07FpPJREJCApUqVWLw4MFA0ojgiRMn0rdvX8xmM6VLl2b06NEPbRMRERERERF5HAULFmTVqlX3batcuTJr1qx5om0iIiLpKUMSwM899xwnT568b9t/BcCGDRvSsGHDR24TERERERERERERkQyuASwiIiIiIiIiIiIiGUcJYBEREREREREREZFsSglgERERERERERERkWxKCWARERERERERERGRbEoJYBEREREREREREZFsSglgERERERERERERkWxKCWARERERERERERGRbEoJYBEREREREREREZFsSglgERERERERERERkWwq1QngRYsW3Xf54sWLn1hnREREnjWKryIiIulDMVZERCRJqhPAc+bMue/yL7744ol1RkRE5Fmj+CoiIpI+FGNFRESS2DxshZ07dwJgNpvZtWsXFovFaLt8+TLOzs7p1zsREZFsSvFVREQkfSjGioiIpPTQBPDo0aMBiI2NZdSoUcZyk8lEnjx5eP/999OvdyIiItmU4quIiEj6UIwVERFJ6aEJ4M2bNwPwzjvvMH369HTvkIiIyLNA8VVERCR9KMaKiIik9NAEcLK7A6fZbE7RZmWV6lLCIiIichfFVxERkfShGCsiIpIk1Qngv//+m4kTJ3Ly5EliY2MBsFgsmEwmjh8/nm4dFBERyc4UX0VERNKHYqyIiEiSVCeAR44cyYsvvsiHH36Ig4NDevZJRETkmaH4KiIikj4UY0VERJKkOgF85coVhgwZgslkSs/+iIiIPFMUX0VERNKHYqyIiEiSVBc+atSoEdu2bUvPvoiIiDxzFF9FRETSh2KsiIhIklSPAI6NjWXgwIFUqVKF3Llzp2jTzKoiIiJpo/gq8mx477332LJlCx4eHqxduxaAzz//nGXLluHu7g7A0KFDqVev3j3bBgYGMnnyZMxmMx06dKBPnz4AXLp0iaFDhxIREUHZsmWZPn06dnZ2fPfdd/z00094eXkxZ84c7Ozs2LdvHxs3bmTUqFEZd9IimUwxVkREJEmqE8DFixenePHi6dkXERGRZ47iq8izoX379nTp0oV33303xfLu3bvzxhtvPHC7xMREJk6cyOLFi/H09OTll1/Gz8+P4sWLM3PmTLp3706LFi0YO3YsP//8M507d2bNmjWsXr2aefPmsW3bNl588UW++OILPvroo/Q+TZGnimKsiIhIklQngAcOHJie/RAREXkmKb6KPBuqVq3K5cuXH3m7w4cPU7hwYQoWLAhAixYt2LRpEz4+PuzatctI6rZr147Zs2fTuXNnLBYLCQkJxMTEYGNjg7+/P3Xq1MHNze1JnpLIU08xVkREJEmqE8A7d+58YFuNGjWeSGdERESeNYqvIs+2JUuWsGrVKsqVK8fIkSPJmTNnivaQkBDy5ctnvPb09OTw4cOEh4eTI0cObGyS/pzPly8fISEhALz22mu88sorFC9enMqVK9O/f38WLVqUcScl8pRQjBUR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UOVfUQ4ePEhSUhInT56krKwMo9HI0KFDGTNmDAD5+fmMHz+eixcv4uvrS3JyMosXLyYlJQWDwcCgQYM4duwYERERDBs2jLKyMmJiYjh06BAGg4EDBw5w5coVJk2aRE5ODl26dCEgIIB9+/aRkpJCVlYWn3/+ORcuXMDR0ZHAwEDi4+Ofyotgkfrm/Pnztnq1f3XvAmi1WWhoKAkJCXh6etq2FRQUMGbMGAwGA0ajke7duxMSEoKPj0+ltmVlZbbP444dOzJt2jSMRiN+fn688sorVS56Upfl5eWxYMECioqKqKiooFOnTkyfPv2BpTSeFlar1Vaj+UHJzrr0nhAREakvFixYQHFxMfPnz692H3/88Qd+fn5s3ry50s19kZqiBLCIiIjUiDt37jw08VXbvf/++3h7e9tuisHdeu5r1qzB39/ftso03L1pZzQa2bBhA3v27KGoqIiOHTsye/ZsGjZsWCfPv7pKSkooLi5+4MxeJTvvJoStVutTPQYiIiJPWl5eHhaLhS5dunDkyBHGjBnD3Llzq7WY+Z9WrlzJzp07WbNmzb8YqUj1aRE4ERERqREPWqW5rvDz8yMrK4uRI0dib2+PnZ0dHh4euLu7880339C1a1dOnDjBrl27MBqNzJgxAzc3N95++2169epFw4YNK/X3tCQ//7oI4J07dzAYDLZzru/n/ihU9kBERJ4WAwYMeOCicHFxcU+8bEJpaSkff/wxhYWFtGzZktGjR9+3wO7jCAkJwWq18tVXX/2LUYr8M5oBLPIUS0tL49NPP71vu5ubG+np6TUQkYhI3fDrr78SExNDRkYGcPfCISsrCy8vL3766Se2bNmCq6srvXr1om/fvjRv3rxS+4qKCiX7RERERETkiVACWERERKQaQkJC6NSpE7///jtXr17FycmJpKQknn322ZoOTURERERExEYJYBEREZFqWLFiBUVFRfTt25devXrdt1+zfEVEREREpDZQAlhERETkX6CEr4iIiIiI1EZKAIuIiIhUk5K+IiIiIiJS2ykBLCIiIiIiIiIiIlJPPVPTAYiIiIiIiIiIiIjIf0MJYBEREREREREREZF6SglgERERERERERERkXpKCWARERERERERERGRekoJYBERERGpVUJCQti3b19Nh/GPbdu2jddffx1PT08CAwOJiori559/fqS2Xbp0oaCg4D+OUERERESeBvY1HYCIiIiISH2zcuVKvv76a+Li4ggMDMTBwYEff/yRzMxMvL29azq8hyovL8feXpcIIiIiIvWJZgCLiIiISK2UmprKm2++yfz58/Hx8SEkJITdu3fb9peUlDBt2jQCAwPx8fFh7Nixtn0bN24kNDQUX19foqOjuXz5sm1fly5dWLduHWFhYXh6epKYmMi5c+cYPnw4Xl5ejB8/nrKyMtvxO3fuJCIiAm9vb4YPH87JkyerjPvGjRssWbKEWbNmERYWRuPGjXFwcCAkJISpU6cCkJubS2RkJN7e3gQGBhIfH297zhEjRgAQERGBp6cnGRkZfxvHsWPHGDRoEJ6enowbN44JEyawePHixx6PsLAw4uLimDdvXqVzio6OZtWqVVW/YCIiIiJSKykBLCIiIiK1Vm5uLs8//zz79+8nKiqKTz75BKvVCsCUKVMwm82kp6ezb98+3nnnHQCysrJYtGgRiYmJ7N27l7Zt2zJx4sRK/e7du5fU1FQ2btzI8uXLmTlzJgsWLGD37t2cPn2a9PR0AI4fP8706dOJj4/nwIEDREZGMnbs2EoJ4nvl5ORw+/ZtQkNDH3rMM888w7Rp09i/fz/r168nKyuLb7/9FoB169YBsHXrVnJycggPD68yjrKyMmJiYhg8eDDZ2dkMHDgQk8lke65HGQ+TycTGjRvJyMhg8ODBbN++nYqKCgCuXLlCVlYWAwcOfJSXTERERERqGSWARURERKTWcnNz44033sDOzo7BgwdTVFREcXExhYWF7Nmzh7i4OJo1a4aDgwO+vr7A3dq7Q4YMoVu3bjg6OjJx4kQOHTrEhQsXbP1GRUXRpEkTOnXqROfOnQkICKB9+/Y4OzvTp08fjh8/DsCGDRuIjIzEw8PDFoODgwOHDh16aMwlJSU0b968ylIK3bt3p2fPntjb29OuXTsiIyM5ePDgQ4+vKo7Dhw9TXl7OyJEjcXBwICwsDHd3d1vbRxmP9957DxcXFxo2bEiPHj1wdnYmKysLgIyMDHx9fXF1da36xRIRERGRWkkFvkRERESk1vpr0rFRo0YA3Lp1i2vXrtGsWTOaNWt2X5vCwkK6detme+zk5ISLiwuXL1+mXbt29/XboEGD+x4XFxcDcOnSJbZs2cLatWtt+y0WC4WFhQ+N2cXFhatXr1ZZT/fs2bPMmzePo0ePYjabuXPnTqWY71VVHAaDgVatWmEwGGz72rRp81jj8dfjAQYPHkxaWhoBAQGkpaUxcuTIh8YmIiIiIrWbEsAiIiIiUue0bt2aa9eucf36dZo2bVppn9Fo5OLFi7bHt27doqSkhFatWj3287Rp04bo6Gg++OCDR27j6emJo6MjJpOJ/v37P/CYzz77jK5du7Jo0SKaNGnCqlWr2LFjR7XiyM7O5vLly1itVlsS+LfffqN9+/bAo43HX5PHAK+99hoDBw7k5MmT5OXl0a9fv0c+fxERERGpXVQCQkRERETqHKPRSJ8+fYiLi+PatWtYLBZbCYWBAweSmprKiRMnKCsr48svv6RHjx622a6PY9iwYaxfv57Dhw9jtVq5desWu3bt4ubNmw9t4+zszLhx44iPj8dkMmE2m7FYLOzevZuEhAQASktLcXJywsnJiby8PFJSUir14erqyvnz5x8pjp49e2JnZ8fatWspLy/HZDJx5MgRW9vqjEfr1q1xd3dn8uTJhIWF0bBhw8ceOxERERGpHZQAFhEREZE6KSEhAXt7e1599VX8/f1ZvXo1AP7+/owfP56PPvqIwMBAzp8/z+LFi6v1HO7u7syePZv4+Hh8fHwICwsjNTX1b9uNHj2a2NhYkpOT8fPzIzg4mHXr1tlm0k6dOpXt27fj5eXFzJkzCQ8Pr9Q+JiaG2NhYvL29ycjIqDIOR0dHli5dyqZNm/Dx8SEtLY3g4GAcHR3/0XgMGjSIX375hYiIiMcdNhERERGpRQzWP5dRFhERERGRemHYsGEMHz6cIUOGVLuPgwcPMnnyZHbu3HlfiQgRERERqTs0A1hEREREpI7Lzs6mqKiI8vJyNm/ezKlTp+jdu3e1+7NYLKxZs4ahQ4cq+SsiIiJSx2kROBERERGRx3Tp0iUGDBjwwH3p6em4ubk90XjOnj3LhAkTMJvNtGvXjiVLlmA0GqvVV15eHkOGDOGFF17giy+++JcjFREREZEnTSUgREREREREREREROoplYAQERERERERERERqaeUABYRERERERERERGpp5QAFhEREREREREREamnlAAWERERERERERERqaeUABYRERERERERERGpp/4PJWwNmrxdZCQAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[138]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">num_col</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Customer_Age&#39;</span><span class="p">,</span><span class="s1">&#39;Credit_Limit&#39;</span><span class="p">,</span><span class="s1">&#39;Months_on_book&#39;</span><span class="p">,</span><span class="s1">&#39;Avg_Utilization_Ratio&#39;</span><span class="p">,</span><span class="s1">&#39;Avg_Open_To_Buy&#39;</span><span class="p">,</span><span class="s1">&#39;Total_Trans_Amt&#39;</span><span class="p">,</span><span class="s1">&#39;Dependent_count&#39;</span><span class="p">,</span>
                  <span class="s1">&#39;Total_Relationship_Count&#39;</span><span class="p">,</span><span class="s1">&#39;Months_Inactive_12_mon&#39;</span><span class="p">,</span><span class="s1">&#39;Contacts_Count_12_mon&#39;</span><span class="p">,</span><span class="s1">&#39;Total_Revolving_Bal&#39;</span><span class="p">,</span>
                  <span class="s1">&#39;Total_Amt_Chng_Q4_Q1&#39;</span><span class="p">,</span><span class="s1">&#39;Total_Trans_Ct&#39;</span><span class="p">,</span><span class="s1">&#39;Total_Ct_Chng_Q4_Q1&#39;</span><span class="p">]</span>

<span class="n">corr_data</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">loc</span><span class="p">[:,</span> <span class="n">num_col</span><span class="p">]</span><span class="o">.</span><span class="n">corr</span><span class="p">()</span>

<span class="n">mask</span> <span class="o">=</span> <span class="n">np</span><span class="o">.</span><span class="n">zeros_like</span><span class="p">(</span><span class="n">corr_data</span><span class="p">)</span>

<span class="n">mask</span><span class="p">[</span><span class="n">np</span><span class="o">.</span><span class="n">triu_indices_from</span><span class="p">(</span><span class="n">mask</span><span class="p">)]</span> <span class="o">=</span> <span class="kc">True</span>

<span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">20</span><span class="p">,</span><span class="mi">12</span><span class="p">))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">heatmap</span><span class="p">(</span><span class="n">corr_data</span><span class="o">.</span><span class="n">abs</span><span class="p">(),</span> <span class="n">annot</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span> <span class="n">fmt</span><span class="o">=</span><span class="s1">&#39;.3f&#39;</span><span class="p">,</span><span class="n">cmap</span><span class="o">=</span><span class="s1">&#39;coolwarm&#39;</span><span class="p">,</span><span class="n">square</span><span class="o">=</span><span class="kc">True</span><span class="p">,</span><span class="n">mask</span><span class="o">=</span><span class="n">mask</span><span class="p">,</span> <span class="n">vmax</span><span class="o">=.</span><span class="mi">3</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAA6kAAAMzCAYAAABEIlSWAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjMuMiwgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy8vihELAAAACXBIWXMAAAsTAAALEwEAmpwYAAEAAElEQVR4nOzdd3RU1drH8e/MpEFCIJ3eu/ReRYJKNxQR9FIUxSuviBcboIiIqKBYKIKCcBEVRQgkBBAVUARpgvQOhh7Se8/MvH+Md3CkBHBIRv191spaM+fsfc4zm2PMM88++xisVqsVERERERERERdgLO4ARERERERERP5HSaqIiIiIiIi4DCWpIiIiIiIi4jKUpIqIiIiIiIjLUJIqIiIiIiIiLkNJqoiIiIiIiLgMJakiIiIiIiJyVdHR0QwcOJCuXbsycOBATp8+fUWb8PBwevfuTVhYGL1792bx4sX2fWazmVdffZW7776be+65h2XLlhV6ToOekyoiIiIiIiJXM3ToUPr3709YWBiRkZGEh4c7JKEAGRkZeHt7YzAYyMjIoHfv3sydO5e6desSERFBVFQU8+fPJyUlhT59+rBkyRIqVqx4zXOqkioiIiIiIiJXSExM5PDhw/Tq1QuAXr16cfjwYZKSkhza+fj4YDAYAMjJySE/P9/+fu3atQwYMACj0Yi/vz93330369atu+553W7DZxEREREREREXlZaWRlpa2hXbfX198fX1tb+PiYkhJCQEk8kEgMlkIjg4mJiYGPz9/R36btiwgXfffZezZ8/y7LPPUqdOHfsxypcvb29Xrlw5Ll26dN34lKSKiIiIiIgUkTXudYo7BH59dxSzZ8++YvuoUaN46qmnbumYXbp0oUuXLly8eJEnn3ySO++8k+rVq9/SsZSkioiIiIiI/IMMGzaMvn37XrH991VUsFU9Y2NjMZvNmEwmzGYzcXFxlCtX7prHLl++PA0bNuSHH36gevXqlCtXjosXL9KoUSPgysrq1eieVBERERERkX8QX19fKlaseMXPH5PUgIAA6tWrx+rVqwFYvXo19erVu2Kq76lTp+yvk5KS2LFjB7Vr1wagW7duLFu2DIvFQlJSEuvXr6dr167XjU+VVBERERERkSJicDcUdwg3ZdKkSYwbN445c+bg6+vLtGnTABgxYgSjR4+mYcOGLF26lJ9++gk3NzesViuDBw+mQ4cOAISFhbFv3z7uvfdeAJ588kkqVap03XPqETQiIiIiIiJFZG3JusUdAj2yjhZ3CNelSqqIiIiIiEgRMbr9tSqpxUH3pIqIiIiIiIjLUJIqIiIiIiIiLkPTfUVERERERIqIwV11wsJohERERERERMRlqJIqIiIiIiJSRLRwUuFUSRURERERERGXoSRVREREREREXIam+4qIiIiIiBQRg7um+xZGlVQRERERERFxGUpSRURERERExGVouq+IiIiIiEgR0eq+hVMlVURERERERFyGKqkiIiIiIiJFRAsnFU6VVBEREREREXEZqqT+QX5+PnPmzGHt2rV4eHhgMplo06YNzz77LO7u7jd1rBUrVtC0aVOqVat2m6L9c8xmM3fddRcNGjRg7ty5xR2OiIiIiIiIktQ/Gj9+PLm5uYSHh+Pj40NBQQHh4eHk5eXddJK6cuVK/Pz8ii1JLSgowM3t2v/EmzdvJjg4mF9++YWEhAQCAwOLMDoRERERkX8eLZxUOIPVarUWdxCu4vTp0/Tp04dNmzZRunRph32zZs0iKyuLsWPHXvF+/fr1zJgxA6PRiNls5uWXX+b8+fNMmTIFf39/fHx8GDt2LK1bt2b69Ols3rwZgI4dO/Lcc89hMpkYN24cHh4enD59mnPnznHPPffQuXNnZs2axaVLlxg2bBjDhg0D4Ndff+WNN94gOTmZ/Px8hg0bRv/+/QGoU6cOo0aN4ocffqBjx4785z//uebnfeqpp7jzzjvZu3cv1apV47HHHgMgLy+P1157jZ07d+Lv70+9evVISEhg5syZAMybN49vv/0Ws9lMSEgIr732GkFBQU79txARERER+TvaVK9JcYdApyN7izuE61Il9XcOHz5MlSpVrkhQCzNz5kwmT55M06ZNMZvNZGdn07p1ayIiIhg+fDidO3cGYMmSJRw5coQVK1YAMGLECJYuXcpDDz0EwIkTJ/jkk08wm82EhoaSnp7OZ599Rnx8PN26deP+++/H09OT5557jrfffpsaNWqQkZFB//79adKkCTVq1ADA09OT8PDw68aclJTE9u3befPNN6levTovv/yyPUldunQpFy9eZM2aNZjNZoYMGULZsmUBiIyM5Ny5c3z11VcYjUaWLFnC1KlTeeedd25qzERERERE/okMJlVSC6Mk1QnatGnDm2++yb333sud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LO4QREREROQv7sS/ehR3CNT6fG1xh3BdSuNFRERERETEZWi679/AxIkT2bdvn8M2k8nEihUriikiERERERG5GqNJCycVRknq38DkyZOLOwQRERERERGnUJIqIiIiIiJSRPQImsLpnlQRERERERFxGUpSRURERERExGVouq+IiIiIiEgR0XNSC6cREhEREREREZehSqqIiIiIiEgR0cJJhVMlVURERERERFyGklQRERERERFxGZruKyIiIiIiUkQ03bdwqqSKiIiIiIiIy1AlVUREREREpIjoETSF0wiJiIiIiIiIy1CSKiIiIiIiIi5D032lSI1b+1hxh3BLpvddTOcHdhR3GLfs+69aF3cIIiIiIoIWTroRqqSKiIiIiIiIy1CSKiIiIiIiIi5D031FRERERESKiFb3LZxGSERERERERFyGKqkiIiIiIiJFxaCFkwqjSqqIiIiIiIi4DCWpIiIiIiIi4jI03VdERERERKSI6DmphVMlVURERERERFyGKqkiIiIiIiJFRI+gKZxGSERERERERFyGklQRERERERFxGZruKyIiIiIiUkT+agsnRUdHM27cOFJSUihTpgzTpk2jatWqDm0++OAD1q5di9FoxN3dnTFjxtCxY0cAxo0bx9atW/Hz8wOgW7dujBw58rrnVJIqIiIiIiIiV/XKK6/w0EMPERYWRmRkJBMnTmTx4sUObRo1asTw4cMpUaIER48eZfDgwWzZsgUvLy8AHn/8cQYPHnzD59R0XxERERERkSJiMBqL/edGJSYmcvjwYXr16gVAr169OHz4MElJSQ7tOnbsSIkSJQCoU6cOVquVlJSUWx4jVVJFRERERET+QdLS0khLS7tiu6+vL76+vvb3MTExhISEYDKZADCZTAQHBxMTE4O/v/9Vjx0REUHlypUpW7asfdt///tfli5dSqVKlXj22WepUaPGdeNTkioiIiIiIvIP8sknnzB79uwrto8aNYqnnnrqlo+7c+dOZsyYwcKFC+3bxowZQ1BQEEajkYiICB577DHWr19vT3yvRkmqiIiIiIhIEXGFhZOGDRtG3759r9j++yoqQLly5YiNjcVsNmMymTCbzcTFxVGuXLkr+u7Zs4fnn3+eOXPmUL16dfv2kJAQ++s+ffrw5ptvcunSJSpUqHDN+JSkioiIiIiI/IP8cVrvtQQEBFCvXj1Wr15N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JCYmcvjwYXr16gVAr169OHz4MElJjrfkdezYkRIlSgBQp04drFYrKSkpAHz99dcMHDgQgKpVq9KgQQN+/NHxNq0/+stP970VdevWtS+y9HsTJ05k3759DttMJhMrVqwo9JhPPfWU0+L7s7H8z+zZs/nuu++u2L5w4UICAgJuKa433njjlvqJiIiIiAgu8ZzUtLQ00tKufPqFr68vvr6+9vcxMTGEhIRgMpkAWz4SHBxMTEwM/v7+Vz12REQElStXpmxZ2yMCL1686LCAbbly5bh06foLl/4jk9RrmTx5cnGHYOeMWEaNGsWoUaOcEI2IiIiIiPxdfPLJJ8yePfuK7aNGjfpTxbedO3cyY8YMFi5c+GfCU5IqIiIiIiJSZFzgETTDhg2jb9++V2z/fRUVbFXP2NhYzGaz/VGZcXFxV33Cx549e3j++eeZM2eOw62U5cuX58KFC/bKa0xMDK1bt75ufMU/QiIiIiIiIlJkfH19qVix4hU/f0xSAwICqFevHqtXrwZg9erV1KtX74qpvvv372fMmDHMnDmTO+64w2Fft27d7I/tPH36NAcOHLCv/HstSlJFRERERETkqiZNmsRnn31G165d+eyzz3j11VcBGDFiBAcOHADg1VdfJScnh4kTJxIWFkZYWBjHjtmedPDoo4+SlpbGPffcw7///W8mT55c6OM/Nd1XRERERESkqLjAwkk3o0aNGixbtuyK7fPnz7e/Dg8Pv2b/kiVLMnPmzJs6pyqpIiIiIiIi4jJUSRURERERESkqRtUJC6MREhEREREREZehJFVERERERERchqb7ioiIiIiIFBHrX2zhpOKgSqqIiIiIiIi4DCWpIiIiIiIi4jI03VdERERERKSoGFQnLIxGSERERERERFyGKqlSpBp3alzcIdyStq9/XNwh3LIakTWLO4RbcvaxY8Udwi27v/JO4g/vLO4wbklQ/VbFHYKIiMjfmyqphdIIiYiIiIiIiMtQkioiIiIiIiIuQ9N9RUREREREioiek1o4VVJFRERERETEZaiSKiIiIiIiUlS0cFKhNEIiIiIiIiLiMpSkioiIiIiIiMvQdF8REREREZGiooWTCqVKqoiIiIiIiLgMVVJFRERERESKilF1wsJohERERERERMRlKEkVERERERERl6HpviIiIiIiIkXEqoWTCqVKqoiIiIiIiLgMVVJF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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[140]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.preprocessing</span> <span class="k">import</span> <span class="n">LabelEncoder</span>
<span class="n">cat_data</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">select_dtypes</span><span class="p">(</span><span class="n">include</span> <span class="o">=</span> <span class="s1">&#39;object&#39;</span><span class="p">)</span>
<span class="n">num_data</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">select_dtypes</span><span class="p">(</span><span class="n">exclude</span> <span class="o">=</span> <span class="s1">&#39;object&#39;</span><span class="p">)</span>

<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="n">cat_data</span><span class="o">.</span><span class="n">columns</span><span class="p">:</span>
    <span class="n">cat_data</span><span class="p">[</span><span class="n">i</span><span class="p">]</span> <span class="o">=</span> <span class="n">LabelEncoder</span><span class="p">()</span><span class="o">.</span><span class="n">fit_transform</span><span class="p">(</span><span class="n">cat_data</span><span class="p">[</span><span class="n">i</span><span class="p">])</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[141]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">concat</span><span class="p">([</span><span class="n">cat_data</span><span class="p">,</span> <span class="n">num_data</span><span class="p">],</span> <span class="n">axis</span> <span class="o">=</span> <span class="mi">1</span><span class="p">)</span>
<span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[141]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Attrition_Flag</th>
      <th>Gender</th>
      <th>Education_Level</th>
      <th>Marital_Status</th>
      <th>Income_Category</th>
      <th>Card_Category</th>
      <th>Customer_Age</th>
      <th>Dependent_count</th>
      <th>Months_on_book</th>
      <th>Total_Relationship_Count</th>
      <th>Months_Inactive_12_mon</th>
      <th>Contacts_Count_12_mon</th>
      <th>Credit_Limit</th>
      <th>Total_Revolving_Bal</th>
      <th>Avg_Open_To_Buy</th>
      <th>Total_Amt_Chng_Q4_Q1</th>
      <th>Total_Trans_Amt</th>
      <th>Total_Trans_Ct</th>
      <th>Total_Ct_Chng_Q4_Q1</th>
      <th>Avg_Utilization_Ratio</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1</td>
      <td>1</td>
      <td>3</td>
      <td>1</td>
      <td>2</td>
      <td>0</td>
      <td>45</td>
      <td>3</td>
      <td>39</td>
      <td>5</td>
      <td>1</td>
      <td>3</td>
      <td>12691.0</td>
      <td>777</td>
      <td>11914.0</td>
      <td>1.335</td>
      <td>1144</td>
      <td>42</td>
      <td>1.625</td>
      <td>0.061</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>0</td>
      <td>2</td>
      <td>2</td>
      <td>4</td>
      <td>0</td>
      <td>49</td>
      <td>5</td>
      <td>44</td>
      <td>6</td>
      <td>1</td>
      <td>2</td>
      <td>8256.0</td>
      <td>864</td>
      <td>7392.0</td>
      <td>1.541</td>
      <td>1291</td>
      <td>33</td>
      <td>3.714</td>
      <td>0.105</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>1</td>
      <td>2</td>
      <td>1</td>
      <td>3</td>
      <td>0</td>
      <td>51</td>
      <td>3</td>
      <td>36</td>
      <td>4</td>
      <td>1</td>
      <td>0</td>
      <td>3418.0</td>
      <td>0</td>
      <td>3418.0</td>
      <td>2.594</td>
      <td>1887</td>
      <td>20</td>
      <td>2.333</td>
      <td>0.000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>0</td>
      <td>3</td>
      <td>3</td>
      <td>4</td>
      <td>0</td>
      <td>40</td>
      <td>4</td>
      <td>34</td>
      <td>3</td>
      <td>4</td>
      <td>1</td>
      <td>3313.0</td>
      <td>2517</td>
      <td>796.0</td>
      <td>1.405</td>
      <td>1171</td>
      <td>20</td>
      <td>2.333</td>
      <td>0.760</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>1</td>
      <td>5</td>
      <td>1</td>
      <td>2</td>
      <td>0</td>
      <td>40</td>
      <td>3</td>
      <td>21</td>
      <td>5</td>
      <td>1</td>
      <td>0</td>
      <td>4716.0</td>
      <td>0</td>
      <td>4716.0</td>
      <td>2.175</td>
      <td>816</td>
      <td>28</td>
      <td>2.500</td>
      <td>0.000</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[199]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.linear_model</span> <span class="k">import</span> <span class="n">LogisticRegression</span>
<span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="k">import</span> <span class="n">train_test_split</span>
<span class="n">x_treino</span><span class="p">,</span><span class="n">x_teste</span><span class="p">,</span><span class="n">y_treino</span><span class="p">,</span><span class="n">y_teste</span><span class="o">=</span><span class="n">train_test_split</span><span class="p">(</span><span class="n">df</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="s1">&#39;Attrition_Flag&#39;</span><span class="p">,</span><span class="n">axis</span><span class="o">=</span><span class="mi">1</span><span class="p">),</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;Attrition_Flag&#39;</span><span class="p">],</span><span class="n">test_size</span><span class="o">=</span><span class="mf">0.42</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[200]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="nb">print</span><span class="p">(</span><span class="s1">&#39;O dataset de treino possui </span><span class="si">{}</span><span class="s1"> clientes e o de teste </span><span class="si">{}</span><span class="s1"> clientes.&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">x_treino</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">0</span><span class="p">],</span> <span class="n">x_teste</span><span class="o">.</span><span class="n">shape</span><span class="p">[</span><span class="mi">0</span><span class="p">]))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>O dataset de treino possui 5873 clientes e o de teste 4254 clientes.
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[209]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">modelo_log</span><span class="o">=</span><span class="n">LogisticRegression</span><span class="p">(</span><span class="n">max_iter</span><span class="o">=</span><span class="mi">2000</span><span class="p">,</span><span class="n">solver</span><span class="o">=</span><span class="s1">&#39;liblinear&#39;</span><span class="p">)</span>
<span class="n">modelo_log</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x_treino</span><span class="p">,</span><span class="n">y_treino</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[209]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>LogisticRegression(max_iter=2000, solver=&#39;liblinear&#39;)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[210]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">acc_logReg</span> <span class="o">=</span> <span class="nb">round</span><span class="p">(</span><span class="n">modelo_log</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">x_treino</span><span class="p">,</span><span class="n">y_treino</span><span class="p">)</span> <span class="o">*</span> <span class="mi">100</span><span class="p">,</span> <span class="mi">2</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Acurácia do modelo de Regressão Logística: </span><span class="si">{}</span><span class="s2">&quot;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">acc_logReg</span><span class="p">))</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Acurácia do modelo de Regressão Logística: 90.11
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[203]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.tree</span> <span class="k">import</span> <span class="n">DecisionTreeClassifier</span>
<span class="c1"># criar um modelo de árvore de decisão</span>
<span class="n">modelo_tree</span> <span class="o">=</span> <span class="n">DecisionTreeClassifier</span><span class="p">(</span><span class="n">max_depth</span><span class="o">=</span><span class="mi">3</span><span class="p">)</span>
<span class="n">modelo_tree</span><span class="o">.</span><span class="n">fit</span><span class="p">(</span><span class="n">x_treino</span><span class="p">,</span><span class="n">y_treino</span><span class="p">)</span>

<span class="c1"># verificar a acurácia do modelo</span>
<span class="n">acc_tree</span> <span class="o">=</span> <span class="nb">round</span><span class="p">(</span><span class="n">modelo_tree</span><span class="o">.</span><span class="n">score</span><span class="p">(</span><span class="n">x_treino</span><span class="p">,</span><span class="n">y_treino</span><span class="p">)</span> <span class="o">*</span> <span class="mi">100</span><span class="p">,</span> <span class="mi">2</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;Acurácia do modelo de Árvore de Decisão: </span><span class="si">{}</span><span class="s2">&quot;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">acc_tree</span><span class="p">))</span>
<span class="n">predicao_tree</span><span class="o">=</span><span class="n">modelo_tree</span><span class="o">.</span><span class="n">predict</span><span class="p">(</span><span class="n">x_teste</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Acurácia do modelo de Árvore de Decisão: 92.27
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[215]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">sklearn.model_selection</span> <span class="k">import</span> <span class="n">cross_val_score</span>
<span class="n">SEED</span> <span class="o">=</span> <span class="mi">50</span>
<span class="n">np</span><span class="o">.</span><span class="n">random</span><span class="o">.</span><span class="n">seed</span><span class="p">(</span><span class="n">SEED</span><span class="p">)</span>
<span class="n">cv</span> <span class="o">=</span> <span class="n">StratifiedKFold</span><span class="p">(</span><span class="n">n_splits</span> <span class="o">=</span> <span class="mi">5</span><span class="p">,</span> <span class="n">shuffle</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">results_tree</span> <span class="o">=</span> <span class="n">cross_val_score</span><span class="p">(</span><span class="n">modelo_tree</span><span class="p">,</span> <span class="n">x_treino</span><span class="p">,</span> <span class="n">y_treino</span><span class="p">,</span> <span class="n">cv</span><span class="o">=</span><span class="n">cv</span><span class="p">,</span> <span class="n">scoring</span> <span class="o">=</span> <span class="s1">&#39;accuracy&#39;</span><span class="p">)</span>
<span class="n">results_log</span> <span class="o">=</span> <span class="n">cross_val_score</span><span class="p">(</span><span class="n">modelo_log</span><span class="p">,</span> <span class="n">x_treino</span><span class="p">,</span> <span class="n">y_treino</span><span class="p">,</span> <span class="n">cv</span><span class="o">=</span><span class="n">cv</span><span class="p">,</span> <span class="n">scoring</span> <span class="o">=</span> <span class="s1">&#39;accuracy&#39;</span><span class="p">)</span>
<span class="k">def</span> <span class="nf">intervalo</span><span class="p">(</span><span class="n">results</span><span class="p">):</span>
    <span class="n">mean</span> <span class="o">=</span> <span class="n">results</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
    <span class="n">dv</span> <span class="o">=</span> <span class="n">results</span><span class="o">.</span><span class="n">std</span><span class="p">()</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Acurácia média: </span><span class="si">{:.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">mean</span><span class="o">*</span><span class="mi">100</span><span class="p">))</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Intervalo de acurácia: [</span><span class="si">{:.2f}</span><span class="s1">% ~ </span><span class="si">{:.2f}</span><span class="s1">%]&#39;</span>
           <span class="o">.</span><span class="n">format</span><span class="p">((</span><span class="n">mean</span> <span class="o">-</span> <span class="mi">2</span><span class="o">*</span><span class="n">dv</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span> <span class="p">(</span><span class="n">mean</span> <span class="o">+</span> <span class="mi">2</span><span class="o">*</span><span class="n">dv</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">))</span>
    
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;DecisionTreeClassifier&quot;</span><span class="p">)</span>
<span class="n">intervalo</span><span class="p">(</span><span class="n">results_tree</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;LogisticRegression&quot;</span><span class="p">)</span>
<span class="n">intervalo</span><span class="p">(</span><span class="n">results_log</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>DecisionTreeClassifier
Acurácia média: 91.61%
Intervalo de acurácia: [91.24% ~ 91.97%]


LogisticRegression
Acurácia média: 89.51%
Intervalo de acurácia: [88.54% ~ 90.48%]
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[216]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="k">def</span> <span class="nf">intervalo_prec</span><span class="p">(</span><span class="n">results</span><span class="p">):</span>
    <span class="n">mean</span> <span class="o">=</span> <span class="n">results</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
    <span class="n">dv</span> <span class="o">=</span> <span class="n">results</span><span class="o">.</span><span class="n">std</span><span class="p">()</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Precisão média: </span><span class="si">{:.2f}</span><span class="s1">%&#39;</span><span class="o">.</span><span class="n">format</span><span class="p">(</span><span class="n">mean</span><span class="o">*</span><span class="mi">100</span><span class="p">))</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Intervalo de Precisão: [</span><span class="si">{:.2f}</span><span class="s1">% ~ </span><span class="si">{:.2f}</span><span class="s1">%]&#39;</span>
          <span class="o">.</span><span class="n">format</span><span class="p">((</span><span class="n">mean</span> <span class="o">-</span> <span class="mi">2</span><span class="o">*</span><span class="n">dv</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">,</span> <span class="p">(</span><span class="n">mean</span> <span class="o">+</span> <span class="mi">2</span><span class="o">*</span><span class="n">dv</span><span class="p">)</span><span class="o">*</span><span class="mi">100</span><span class="p">))</span>
<span class="n">np</span><span class="o">.</span><span class="n">random</span><span class="o">.</span><span class="n">seed</span><span class="p">(</span><span class="n">SEED</span><span class="p">)</span>
<span class="n">cv</span> <span class="o">=</span> <span class="n">StratifiedKFold</span><span class="p">(</span><span class="n">n_splits</span> <span class="o">=</span> <span class="mi">5</span><span class="p">,</span> <span class="n">shuffle</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
<span class="n">model</span> <span class="o">=</span> <span class="n">LogisticRegression</span><span class="p">(</span><span class="n">solver</span><span class="o">=</span><span class="s1">&#39;liblinear&#39;</span><span class="p">)</span>
<span class="n">results</span> <span class="o">=</span> <span class="n">cross_val_score</span><span class="p">(</span><span class="n">model</span><span class="p">,</span> <span class="n">x_treino</span><span class="p">,</span> <span class="n">y_treino</span><span class="p">,</span> <span class="n">cv</span> <span class="o">=</span> <span class="n">cv</span><span class="p">,</span> 
                          <span class="n">scoring</span> <span class="o">=</span> <span class="s1">&#39;precision&#39;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;DecisionTreeClassifier&quot;</span><span class="p">)</span>
<span class="n">intervalo_prec</span><span class="p">(</span><span class="n">results_tree</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;</span><span class="se">\n</span><span class="s2">&quot;</span><span class="p">)</span>
<span class="nb">print</span><span class="p">(</span><span class="s2">&quot;LogisticRegression&quot;</span><span class="p">)</span>
<span class="n">intervalo_prec</span><span class="p">(</span><span class="n">results_log</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>DecisionTreeClassifier
Precisão média: 91.61%
Intervalo de Precisão: [91.24% ~ 91.97%]


LogisticRegression
Precisão média: 89.51%
Intervalo de Precisão: [88.54% ~ 90.48%]
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

    </div>
</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
