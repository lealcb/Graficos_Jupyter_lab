<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>Untitled</title>

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

<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Total-de-Atendimento">Total de Atendimento<a class="anchor-link" href="#Total-de-Atendimento">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[24]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">pyodbc</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>


<span class="n">conn</span> <span class="o">=</span> <span class="n">pyodbc</span><span class="o">.</span><span class="n">connect</span><span class="p">(</span><span class="s1">&#39;Driver={SQL Server};&#39;</span>
                      <span class="s1">&#39;Server=HP-PC\SQLEXPRESS;&#39;</span>
                      <span class="s1">&#39;Database=helpdesk;&#39;</span>
                      <span class="s1">&#39;Trusted_Connection=yes;&#39;</span><span class="p">)</span>

<span class="n">cursor</span> <span class="o">=</span> <span class="n">conn</span><span class="o">.</span><span class="n">cursor</span><span class="p">()</span>

<span class="n">sql_query3</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;&#39;&#39;</span>
<span class="s1">SELECT </span>
<span class="s1">    tblAtendimento.data_atendimento as DATA, </span>
<span class="s1">    COUNT(tblAtendimento.IDatendimento) as total </span>
<span class="s1">from </span>
<span class="s1">    helpdesk.dbo.tblAtendimento</span>
<span class="s1">WHERE</span>
<span class="s1">    tblAtendimento.data_atendimento BETWEEN &#39;2020-11-30&#39; AND &#39;2020-12-04&#39;</span>
<span class="s1">group by </span>
<span class="s1">    tblAtendimento.data_atendimento </span>
<span class="s1">order by </span>
<span class="s1">    tblAtendimento.data_atendimento asc&#39;&#39;&#39;</span><span class="p">,</span><span class="n">conn</span><span class="p">)</span>

<span class="n">sql_query4</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;&#39;&#39;</span>
<span class="s1">SELECT </span>
<span class="s1">    tblAtendimento.data_atendimento as DATA, </span>
<span class="s1">    COUNT(tblAtendimento.IDatendimento) as total </span>
<span class="s1">from </span>
<span class="s1">    helpdesk.dbo.tblAtendimento</span>
<span class="s1">WHERE</span>
<span class="s1">    tblAtendimento.data_atendimento BETWEEN &#39;2020-12-01&#39; AND &#39;2020-12-30&#39;</span>
<span class="s1">group by </span>
<span class="s1">    tblAtendimento.data_atendimento </span>
<span class="s1">order by </span>
<span class="s1">    tblAtendimento.data_atendimento asc&#39;&#39;&#39;</span><span class="p">,</span><span class="n">conn</span><span class="p">)</span>


<span class="n">sql_query</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;&#39;&#39;</span>
<span class="s1">SELECT </span>
<span class="s1">    tblAtendimento.data_atendimento as DATA, </span>
<span class="s1">    COUNT(tblAtendimento.IDatendimento) as total </span>
<span class="s1">from </span>
<span class="s1">    helpdesk.dbo.tblAtendimento </span>
<span class="s1">group by </span>
<span class="s1">    tblAtendimento.data_atendimento </span>
<span class="s1">order by </span>
<span class="s1">    data_atendimento asc&#39;&#39;&#39;</span><span class="p">,</span><span class="n">conn</span><span class="p">)</span>

<span class="n">sql_query2</span><span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_sql_query</span><span class="p">(</span><span class="s1">&#39;&#39;&#39;</span>
<span class="s1">SELECT	</span>
<span class="s1">	</span>
<span class="s1">	tblcliente.base,</span>
<span class="s1">	tblcliente.razao,</span>
<span class="s1">	count(tblatendimento.idcliente) as TOTAL</span>
<span class="s1">FROM </span>
<span class="s1">	helpdesk.dbo.tblatendimento</span>


<span class="s1">INNER JOIN </span>
<span class="s1">	tblcliente </span>
<span class="s1">	on  </span>
<span class="s1">	tblatendimento.idcliente = tblcliente.idcliente</span>

<span class="s1">	</span>
<span class="s1">GROUP BY </span>
<span class="s1">	tblcliente.base,</span>
<span class="s1">	tblcliente.razao</span>

<span class="s1">HAVING COUNT(idatendimento) &gt; 8</span>



<span class="s1">ORDER BY total desc </span>



<span class="s1">&#39;&#39;&#39;</span><span class="p">,</span><span class="n">conn</span><span class="p">)</span>
<span class="n">df4</span> <span class="o">=</span> <span class="n">sql_query4</span>
<span class="n">df3</span> <span class="o">=</span> <span class="n">sql_query3</span>
<span class="n">df2</span> <span class="o">=</span> <span class="n">sql_query2</span>
<span class="n">df</span> <span class="o">=</span> <span class="n">sql_query</span>

<span class="c1"># Total Geral</span>

<span class="n">x</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s2">&quot;total&quot;</span><span class="p">]</span>
<span class="n">y</span> <span class="o">=</span> <span class="n">df</span><span class="p">[</span><span class="s2">&quot;DATA&quot;</span><span class="p">]</span>
<span class="c1">#df_mean = np.mean(df[&#39;total&#39;])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">style</span><span class="o">.</span><span class="n">use</span><span class="p">(</span><span class="s1">&#39;fivethirtyeight&#39;</span><span class="p">)</span>
<span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">6</span><span class="p">,</span> <span class="mi">8</span><span class="p">))</span>
<span class="n">DATA</span><span class="o">=</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;DATA&#39;</span><span class="p">]</span>
<span class="n">total</span><span class="o">=</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;total&#39;</span><span class="p">]</span>
<span class="n">soma_total</span> <span class="o">=</span> <span class="nb">sum</span><span class="p">(</span><span class="n">total</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">barh</span><span class="p">(</span><span class="n">DATA</span><span class="p">,</span><span class="n">total</span><span class="p">)</span>
<span class="n">labels</span> <span class="o">=</span> <span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">setp</span><span class="p">(</span><span class="n">labels</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">horizontalalignment</span><span class="o">=</span><span class="s1">&#39;right&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="sa">f</span><span class="s1">&#39;Total de Atendimento: </span><span class="si">{</span><span class="n">soma_total</span><span class="si">}</span><span class="s1">                    &#39;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s1">&#39;DATA&#39;</span><span class="p">,</span>
       <span class="n">title</span><span class="o">=</span><span class="s1">&#39;SETCOMP&#39;</span><span class="p">)</span>
<span class="c1">#ax.axvline(df_mean, ls=&#39;--&#39;, color=&#39;r&#39;)</span>


<span class="c1"># Total por Cliente</span>

    

    
<span class="c1">## Total por Semana</span>

<span class="c1">#df_mean = np.mean(df[&#39;total&#39;])</span>
<span class="n">plt</span><span class="o">.</span><span class="n">style</span><span class="o">.</span><span class="n">use</span><span class="p">(</span><span class="s1">&#39;fivethirtyeight&#39;</span><span class="p">)</span>
<span class="n">fig</span><span class="p">,</span> <span class="n">ax</span> <span class="o">=</span> <span class="n">plt</span><span class="o">.</span><span class="n">subplots</span><span class="p">(</span><span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">6</span><span class="p">,</span> <span class="mi">8</span><span class="p">))</span>
<span class="n">DATA</span><span class="o">=</span><span class="n">df3</span><span class="p">[</span><span class="s1">&#39;DATA&#39;</span><span class="p">]</span>
<span class="n">total</span><span class="o">=</span><span class="n">df3</span><span class="p">[</span><span class="s1">&#39;total&#39;</span><span class="p">]</span>
<span class="n">total_max</span> <span class="o">=</span> <span class="n">total</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>

<span class="n">ax</span><span class="o">.</span><span class="n">barh</span><span class="p">(</span><span class="n">DATA</span><span class="p">,</span><span class="n">total</span><span class="p">)</span>
<span class="n">labels</span> <span class="o">=</span> <span class="n">ax</span><span class="o">.</span><span class="n">get_xticklabels</span><span class="p">()</span>
<span class="n">plt</span><span class="o">.</span><span class="n">setp</span><span class="p">(</span><span class="n">labels</span><span class="p">,</span> <span class="n">rotation</span><span class="o">=</span><span class="mi">0</span><span class="p">,</span> <span class="n">horizontalalignment</span><span class="o">=</span><span class="s1">&#39;right&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set</span><span class="p">(</span><span class="n">xlabel</span><span class="o">=</span><span class="sa">f</span><span class="s1">&#39;Total de Atendimento:</span><span class="si">{</span><span class="n">total_max</span><span class="si">}</span><span class="s1">                     &#39;</span><span class="p">,</span> <span class="n">ylabel</span><span class="o">=</span><span class="s1">&#39;DATA&#39;</span><span class="p">,</span>
       <span class="n">title</span><span class="o">=</span><span class="s1">&#39;SETCOMP&#39;</span><span class="p">)</span>
<span class="k">for</span> <span class="n">i</span><span class="p">,</span> <span class="n">v</span> <span class="ow">in</span> <span class="nb">enumerate</span><span class="p">(</span><span class="n">total</span><span class="p">):</span>
    <span class="n">ax</span><span class="o">.</span><span class="n">text</span><span class="p">(</span><span class="n">v</span> <span class="o">+</span> <span class="mi">0</span><span class="p">,</span> <span class="n">i</span> <span class="o">+</span> <span class="o">.</span><span class="mi">000002</span><span class="p">,</span> <span class="nb">str</span><span class="p">(</span><span class="n">v</span><span class="p">),</span> <span class="n">color</span><span class="o">=</span><span class="s1">&#39;RED&#39;</span><span class="p">)</span>

<span class="nb">print</span><span class="p">(</span><span class="n">total_max</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>57
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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GTjdB2+++SY2b94MPz8/vPzyyzh37hw2bdqEU6dOoaCgAD179kRUVBSqq6tx7dq1VmctALB27Vp4e3sjKCgIenp6yMvLQ2RkJKRSKV566aUOt2nr1q2YP38+3NzcMHv2bFy/fh1z585ts9DAwoULsWXLFoSGhmL27NkoLy/H+vXrcfLkSRw5ckRlwYmWtm/fDnd3dzz66KMICgrCokWLkJWVhblz5wIATE1NER8fj+joaDzzzDOKoiKDBw8GAFy/fh3e3t5oamrCiy++CIlEguPHjyM2Nha///47VqxYoXS8Xbt2obKyEuHh4ejVqxdSUlIwffp0nD17VnH2VlJSgqCgIPTr1w9RUVEwMDBAamoq+vTpo/HrmJOTg4aGBsycORN1dXVITExEWFgYgoODkZubi1deeQXXrl1DUlISFi5ciK1btyr+9ujRowgODoaTkxOio6NhYGCAnJwcTJs2DWlpaQgMDFQ6VkxMDHr37o033ngDlZWVSEpKwpw5c7Bv3z4AUPsekslkmDFjBvbv34/nn38eHh4eOHHiBD766COcO3dOaY5GXl4eXn31VSQnJyMsLEzj10KuoaEBNTVilr4bAAAKeElEQVQ1GDBgQKt1paWlGDhwIG7fvg1TU1OEhYUhJiZGo+pU8uvqbe2XqC1M4NQlxcXF2Lx5M5577jmsX79esdze3h5LlizBtm3b8MILL8DLywsSiQS1tbVtDjGeOnUKhoaGit9ffvllBAUFYc2aNR1O4E1NTVi2bBkcHBywd+9e9OrVCwDw5JNPYsqUKbC2tlZse/LkSWzevLnVf+YBAQF46qmnsH79erz11ltqj1dVVYX9+/crrl32798fXl5eyMzMVCTwPn36IDAwENHR0XB2dm71GsjPFI8dOwZzc3MAQHh4OCQSCZKSkjBv3jzY2toqtv/1119x6tQpxZnck08+iXHjxmHnzp2IiIgAAHz44YdobGzE559/rviiEBYWBjc3N41fyytXruD06dOKLzE9evRAXFwcbt26haKiIkViqqurw6effoqKigqYmppCJpPhjTfewOjRo7Fr1y706HF3sC8iIgI+Pj545513WiVwQ0ND5OXlKbZ95JFHEBMTg3PnzsHR0VHte6igoAD79+9HVFQUli5dCgCYPXs2zMzMkJKSgsOHD+Opp57SOG511q5di/r6ekyePFlp+eDB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
"
>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAfAAAAIdCAYAAADCni8nAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nOzde1zW9f3/8eclBCJomCIe0YF4iMlUEpBSEw+NWHlIQ7PDDIX4uVaaDu1WmZlfZ2nNNptOs9VXaiBSYha6JUsUFbdmlFbztjVyhpjIVVwcROD6/WFdXy85e7p45+N+u3ELPp/35329Xn689fRzxGK1Wu0CAABGaePqAgAAQMsR4AAAGIgABwDAQAQ4AAAGIsABADAQAQ4AgIEIcAAADOTu6gIAuEZtba02bdqktLQ0HT58WKWlpbr++uvVpUsXDR48WGPHjtVdd90lSSooKNBPfvKTJufcvXu3Pv74Y82ZM6dFtVitVsf3hw4d0h//+Efl5uaqsLBQZ86cUadOnfSTn/xEP/vZzzR16lR5enrWmSM/P1/r16/X3r17VVhYqDZt2qhnz54aOXKkkpKSFBgYWGeb8/vy8vLSZ599puuvv77eGsPCwvSvf/1LkpSenq6xY8c61sXGxmrv3r1O4729vdW7d2/FxMTo4Ycflq+vb4v+TICmEODANai2tlbTp0/Xjh071KFDB/30pz9V9+7d9c033+iLL75QZmam/va3vzkC/HsdOnRQUlJSg/P6+/tLkpKTk52Wf/PNN1q7dm2j21dXV2vRokVav3692rRpo+HDhys6Olrt2rXTiRMnlJOTo6ysLG3YsEF//etfHdvZ7XYtW7ZMq1atUps2bTRq1CjFxsaqtrZWH374odavX69XX31Vv/71rzVr1qx6P9vd3V0VFRXavHlzvWNycnL0r3/9S+7u7qqurm6w/+nTpysgIEB2u11FRUV67733tGrVKr399tt6//33CXFcVgQ4cA1KT0/Xjh079OMf/1jbt2+vc9RZWVmpffv21dnu+uuv16JFixqd29/fX6GhoU7LCgoKtHbt2ka3/9WvfqWNGzdq4MCBevXVVzVgwACn9Xa7Xe+9957WrFnjtHzVqlVauXKlevbsqTfeeKPOZ+/evVv333+/5s+frw4dOujuu++u89mDBg1SUVGRXnvttXoD/PXXX5eHh4duvfVW7dy5s8He77nnHo0YMcLx87PPPqsxY8bon//8p/7whz/oV7/6VYPbAi3FNXDgGnTgwAFJ5wKnvlPGbdu21ejRo69aPXl5edq4caN8fX21ZcuWOuEtSRaLRbfffrsyMjIcy7788kutWLFC7u7uevPNN+uEtySNHDlS69atkyQtXLhQNputzhg3NzfNmDFDH3/8sf7xj384rSspKdG2bdsUGxurTp06taiv9u3b65577pEk/f3vf2/RtkBTCHDgGnTDDTdIkuOarqu9+uqrkqQHHnhA3bt3b3Ts+de/N23apLNnzyo2NlaDBg1qcJvbbrtNgwcP1unTp7V169Z6x9x3331q06aNXn/9daflf/rTn1RZWakHHnigue0AVwWn0IFr0B133KHf/OY32rhxo7799lvFxMRo8ODB+tGPfiSLxdLgdt98842WL19e77rrr79e/+///b+Lquf70/UtPerfv3+/JCk6OrrJsdHR0Tp06JD279+vGTNm1FkfEBCg0aNHKz09Xc8++6y8vb0lnTt93rt3b40aNUqpqaktqs9ms+lPf/qTJGno0KEt2hZoCgEOXINCQ0P1hz/8QQsXLtTmzZu1efNmSedCODIyUtOnT9eECRPqhPm3336rFStW1Dtnr169LjrAi4qKJKnJo++GtuvRo0eTY78fc+LEiQbH3H///Xr//feVkZGh++67TwcOHNCnn36qJ598stF/2HzvjTfe0J49e2S323Xy5EllZWXpxIkT6tOnjxITE5vZFdA8BDhwjZo0aZJ+9rOfKScnR/v27dPhw4e1f/9+7dixQzt27ND48eO1adMmeXh4OLbp1auXPv744ytWU3NC8nx2u73F2zU29vbbb1eXLl30+uuv67777tNrr70md3f3eo/Y6/Pmm286vm/Xrp369OmjadOm6ZFHHuEOdFx2BDhwDbvuuusUHR3tOAVdW1urzMxMzZkzRzt37tTGjRv10EMPXfE6/P399Z///EfHjx9XcHBwi7b75z//qf/+979Njj1+/Lhjm4Zcd911mj59ulavXq0DBw7o7bff1vjx49W1a9dm1bNt2zanu9CBK4mb2AA4tGnTRhMnTnQ8q33+89ZX0vDhwyVJH3zwQYu2i4yMlCRlZ2c3Ofb7Xr7fpiEPPPCALBaLHnzwQZWXl+vnP/95i2oCrhYCHEAd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b2/vRue5lD6+76E+VVVVOnTokFNf0rngP7+e6upqzZo1S/Pnz1f//v0ve50AgCvL8+mn5ZabK0tBgdocPizPJUvktmePzk6dKtlsavvEE3LLy5OloEBuOTlqN22a7H5+OvuznzVr/lZzE9vChQs1aNAghX93d15RUZEkyc/Pz2mcn5+fCgsL653DarVq2bJluv/+++Xufq61kydPqlOnTrJYLI5xFotFnTt31smTJy9rD+vXr9dXX32luLi4BscUFxerpqam3r7Or2f58uXq2LFjncsBAAAz2I4eVfs//UnXFRerxsdHFX376svVq/Vtnz6yfPGF+v7tb2qXkiK30lKd7dxZ1rAwHX/qKZ09cUI6caLJM8StIsAff/xx7d+/X1lZWXJzc3Nad37wSudubLtwmSSVlZVp+vTp6tatm5555plG57hwnsjISMf15+HDhys9Pb3FPWzdulVPPfWUXnnlFQUEBEiScnNzNXXqVMeYF198USNGjGiyrz179uiNN95QTk5Oi+sAALQO16WkqFJS5XnL/L/7kiRlZan8/PGS+rRgfpcH+KJFi5SRkaFt27apT58+juX+3z3YfvLkSfXs2dOx/NSpU3WOXm02myMoU1NT1bZtW8e6Ll266NSpU04BabfbVVxc7JgnLS1N1dXVkuS0bXNt3bpVDz30kNauXavbb7/dsXzIkCFOIezn5ydPT0+5ubnVOfo/v6+cnBydOHHC6dR5TU2NFi9erN///vd17tYHAFx7XBrgycnJysjI0DvvvKN+/fo5revdu7f8/f2VnZ2toUOHSjr3aNe+ffucjrBLS0s1depU2e12paeny8fHx2me8PBw2Ww25eXlOa6D5+XlqayszPHz90fMF+Ott95SUlKSfv/732vChAlO67y8vBQYGFhnm8GDBys7O1sTJ050LMvOztadd94p6dxd8xfOddddd+muu+7SAw88cNG1AgB+OFwW4PPnz1dqaqo2bdokX19fxzVvb29v+fj4yGKxKCkpSatWrVJwcLD69u2rlStXytvbW1OmTJF0LrwnT56s0tJSpaSkqLy8XOXl505IdOzYUR4eHurfv7/Gjh2ruXPnavXq1bLb7Zo7d65uu+22Jq8vfPbZZ6qqqlJxcbHKysqUn58vSQoNDZUkbdmyRYmJiVq6dKmioqIcPXh4eKhjx44NzjtnzhwlJiYq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YmJiZLfbNWDAAM2ePVvz58+XJFVUVCg4OFhLly7VzJkz651n586diouLU0FBgTp06KDPP/9cERERysrKUmRkpCRp3759iomJ0cGDBxUcHNxkbQsWLNCRI0e0ffv2JsdGR0dr+PDhjQbvmDFjFBISopdeesmxbOjQoZowYYIWL17sNLa4uFhBQUHatm2bRowY0ehn+756vMn6XMU6s4dktarNV185LfeaM0e1QUE6M2+eagcOlCwWHT16tFn7xQT00jrRS+tELy3Tam5is9lsqq2tle93dyUXFBSoqKhI0dHRjjFeXl6KiorSgQMHGpyntLRUnp6eateunSQpLy9PPj4+ioiIcIyJjIyUt7d3o/NcSh++jdxZXVVVpUOHDjn1JZ0L/itRT6vi66vaG290+lK7drJ37Hjue4vF1RUCgDFazU1sCxcu1KBBgxQeHi5JKioqkiT5+fk5jfPz81NhYWG9c1itVi1btkz333+/3N3PtXby5El16tRJlvPCwWKxqHPnzjp58uRl7WH9+vX66quvFBcX1+CY4uJi1dTU1NvX5a6nNTl69Gi9y/tXVKjCatWXF6xvaLyJ6KV1opfWiV7+T1NH8K0iwB9//HHt379fWVlZcnNzc1pnueCozG6311kmSWVlZZo+fbq6deumZ555ptE5LpwnMjLScf15+PDhSk9Pb3EPW7du1VNPPaVXXnlFAQEBkqTc3FxNnTrVMebFF190nAZvbl8/FA39RazdtUueks5fy2m01oleWid6aZ2uRi8uD/BFixYpIyND27ZtU58+fRzL/f39JZ07gu7Zs6dj+alTp+ocvdpsNkdQpqamqm3bto51Xbp00alTp5wC0m63q7i42DFPWlqaqqurJclp2+baunWrHnroIa1du1a33367Y/mQIUOc7h738/OTp6en3Nzc6hxt19cXAAANcek18OTkZKWnpyszM1P9+vVzWte7d2/5+/srOzvbsayyslL79u1zup5dWlqqKVOmqLa2VmlpafLx8XGaJzw8XDabTXl5eY5leXl5Kisrc8wTEBCgwMBABQYGqnv37i3q4a233lJiYqJefvllTZgwwWmdl5eXY97AwEC1b99eHh4eGjx4sFNfkpSdne3UFwAAjXHZEfj8+fOVmpqqTZs2ydfX13HN29vbWz4+PrJYLEpKStKqVasUHBysvn37auXKlfL29taUKVMknQvvyZMnq7S0VCkpKSovL1d5ebkkqWPHjvLw8FD//v01duxYzZ07V6tXr5bdbtfcuXN12223NXl647PPPlNVVZWKi4tVVlam/Px8SVJoaKgkacuWLUpMTNTSpUsVFRXl6MHDw0MdO3ZscN45c+YoMTFRYWFhioiI0MaNG3XixAmnO+tLSkp07NgxffPNN5KkL774Qtdff738/f0dZycAANculwX4hg0bJKnOUWtycrIWLVokSXrkkUdUUVGhBQsWyGq1KiwsTBkZGWrfvr0k6dChQzp48KAkKSwszGme8x+7Wr9+vZKTkzV58mRJUkxMjJ577rkma7zw2eyRI0dKkuMlMBs3blR1dbUWLVrkqFmSbr755kYfOZs8ebJOnz6t559/XkVFRRo4cKDS0tIc184l6d1339WcOXMcP//yl7+s8+cDALh2tZrnwHHpWv1z4M3EjSytE720TvTSOl1Tz4EDAIDmI8ABADAQAQ4AgIEIcAAADESAAwBgIAIcAAADEeAAABiIAAcAwEAEOAAABiLAAQAwEAEOAICBCHAAAAxEgAMAYCACHAAAAxHgAAAYiAAHAMBABDgAAAYiwAEAMBABDgCAgQhwAAAMRIADAGAgAhwAAAMR4AAAGIgABwDAQAQ4AAAGIsABADAQAQ4AgIEIcAAADESAAwBgIHdXF4DLxzqzh6tLAABcJRyBAwBgIAIcAAADEeAAABiIAAcAwEAEOAAABiLAAQAwEAEOAICBCHAAAAxEgAMAYCACHAAAAxHgAAAYiAAHAMBABDgAAAYiwAEAMBABDgCAgQhwAAAM5O7qAnD5+L563NUlXCbtpD2XrxfrzB6XbS4AaC04AgcAwEAEOAAABiLAAQAwEAEOAICBCHAAAAxEgAMAYCACHAAAAxHgAAAYiAAHAMBABDgAAAYiwAEAMBABDgCAgQhwAAAMRIADAGAgAhwAAAMR4AAAGIgABwDAQAQ4AAAGIsABADAQAQ4AgIEIcAAADESAAwBgIAIcAAADEeAAABiIAAcAwEDuri4AuBraDxqkNseO1Vl+dvx4laeluaAiALg0BDiuCbbsbKmmxvGz5cQJ+dx6q85OnOjCqgDg4hHguCbYO3d2+tnjf/9Xat+eAAdgLK6B49pjt8vjf/9XVXFxUrt2rq4GAC4KAY5rjnt2ttoUFKjqvvtcXQoAXDQCHNccj9deU/XQoaoNDXV1KQBw0VwW4C+88IJGjx6tXr16KSgoSHFxcTpy5IjTGLvdruXLl2vAgAHq2rWrYmNj9emnnzrWl5SUaMGCBRo2bJi6du2qkJAQzZs3T6dPn3aax2q1KiEhQQEBAQoICFBCQoKsVmuj9VVWViopKUlRUVHq3LmzYmNj64w5ceKEZs2apWHDhumGG25QUlJSs3pfv369oqKi1KtXL/Xq1Uvjxo3Tjh07WtQ7Lo7l66/l/u67qnrgAVeXAgCXxGUBvmfPHsXHx2vHjh3KzMyUu7u7Jk6cqJKSEseY1atXa82aNVqxYoV27dolPz8/TZo0SaWlpZKkwsJCFRYWasmSJcrNzdW6deuUm5ur+Ph4p8+aNWuW8vPztXnzZqWnpys/P1+JiYmN1ldTU6O2bdsqISFB48ePr3fMmTNndMMNN+jRRx/VTTfd1Ozeu3fvriVLluiDDz5Qdna2Ro4cqRkzZuiTTz5pdu+4ONelpEienjo7ebKrSwGAS2KxWq12VxchSTabTQEBAUpJSVFMTIzsdrsGDBig2bNna/78+ZKkiooKBQcHa+nSpZo5c2a98+zcuVNxcXEqKChQhw4d9PnnnysiIkJZWVmKjIyUJO3bt08xMTE6ePCggoODm6xtwYIFOnLkiLZv397gmLi4ON1www36/e9/fxHdS3369NHixYs1c+bMi+7d99XjF/XZP3TWmT3OfWO3yycsTDW33KKKl166Kp999OjRZv0dMwG9tE700jpdjV5azTVwm82m2tpa+fr6SpIKCgpUVFSk6OhoxxgvLy9FRUXpwIEDDc5TWloqT09Ptfvu7uK8vDz5+PgoIiLCMSYyMlLe3t6NznO11NTUaMuWLSorK1N4eLiki+8djXPLyZHbv//N6XMAPwit5jnwhQsXatCgQY4QKyoqkiT5+fk5jfPz81NhYWG9c1itVi1btkz333+/3N3PtXby5El16tRJFovFMc5isahz5846efLklWilWQ4fPqzx48ersrJS3t7e2rRpk0JCQiRdXO9o2NGjR899062bdPDg9wuv/uf/ANBL60QvrdOl9tLUEXyrCPDHH39c+/fvV1ZWltzc3JzWnR+80rmbuy5cJkllZWWaPn26unXrpmeeeabROS6cJzIyUse+e83m8OHDlZ6efkn9fC83N1dTp051/Pziiy/q7rvvlnRux+Tk5Oibb75RZmamkpKS9M477+jGG29ssO6GekfjXHlKjlOCrRO9tE700jIuD/BFixYpIyND27ZtU58+fRzL/f39JZ07gu7Zs6dj+alTp+ocmdpsNkdQpqamqm3bto51Xbp00alTp5zCz263q7i42DFPWlqaqqurJclp20s1ZMgQ5eTkOH4+v24PDw8FBgY6xn344Yd6+eWX9bvf/a5FvQMArk0uvQaenJys9PR0ZWZmql+/fk7revfuLX9/f2VnZzuWVVZWat++fU7Xs0tLSzVlyhTV1tYqLS1NPj4+TvOEh4fLZrMpLy/PsSwvL09lZWWOeQICAhQYGKjAwEB17979svXn5eXlmDcwMFDt27dvcGxtba2qqqokNb93AMC1y2VH4PPnz1dqaqo2bdokX19fx3Vfb29v+fj4yGKxKCkpSatWrVJwcLD69u2rlStXytvbW1OmTJF0LrwnT56s0tJSpaSkqLy8XOXl5ZKkjh07ysPDQ/3799fYsWM1d+5crV69Wna7XXPnztVtt93W5OmNzz77TFVVVSouLlZZWZny8/MlSaHnvQDk+2XffvutLBaL8vPz5eHhoQEDBjQ479NPP63x48erR48estlsSk9P1549e5T23W/Fak7vAIBrm8sCfMOGDZKkCRMmOC1PTk7WokWLJEmPPPKIKioqtGDBAlmtVoWFhSkjI8NxJHvo0CEd/O6mpLCwMKd5tm3bphEjRkg69+KU5ORkTf7u2d+YmBg999xzTdY4depUx7VxSRo5cqQkOb0E5vtl38vKylKvXr308ccfNzhvUVGREhISdPLkSXXo0EEhISFKT0/XmDFjHGOa6h0AcG1rNc+B49LxHHj9HM+BuwA35bRO9NI60UvLtJrnwAEAQPMR4AAAGIgABwDAQAQ4AAAGIsABADAQAQ4AgIEIcAAADESAAwBgIAIcAAADEeAAABiIAAcAwEAEOAAABiLAAQAwEAEOAICBCHAAAAxEgAMAYCACHAAAAxHgAAAYiAAHAMBABDgAAAYiwAEAMBABDgCAgQhwAAAMRIADAGAgAhwAAAMR4AAAGIgABwDAQAQ4AAAGcnd1Abh8rDN7uLqEy+Lo0aMKDg52dRkA0KpxBA4AgIEIcAAADESAAwBgIAIcAAADEeAAABiIAAcAwEAEOAAABiLAAQAwEAEOAICBCHAAAAxEgAMAYCACHAAAAxHgAAAYiAAHAMBABDgAAAYiwAEAMBABDgCAgQhwAAAMRIADAGAgi9Vqtbu6CAAA0DIcgQMAYCACHAAAAxHgAAAYiAAHAMBABDgAAAYiwA2yYcMGhYaGyt/fX6NGjVJubq6rS7ooy5cvl6+vr9NXv379XF1Wvfbu3atp06Zp4MCB8vX1VUpKitN6u92u5cuXa8CAAeratatiY2P16aefuqjaxjXVS1JSUp39MnbsWBdV27AXXnhBo0ePVq9evRQUFKS4uDgdOXLEaYwp+6U5vZiyXyRp/fr1ioqKUq9evdSrVy+NGzdOO3bscKw3Zb9ITffSGvYLAW6IjIwMLVy4UI899ph2796t8PBwTZ06VceOHXN1aRclODhYn3/+ueOrtf5jpKysTDfeeKN+/etfy8vLq8761atXa82aNVqxYoV27dolPz8/TZo0SaWlpS6otnFN9SJJt956q9N+2bx581Wusml79uxRfHy8duzYoczMTLm7u2vixIkqKSlxjDFlvzSnF8mM/SJJ3bt315IlS/TBBx8oOztbI0eO1IwZM/TJJ59IMme/SE33Irl+v/AcuCHGjBmjkJAQvfTSS45lQ4cO1YQJE7R48WIXVtZyy5cvV2Zmpvbt2+fqUlqkR48eeu655zRjxgxJ544mBgwYoNmzZ2v+/PmSpIqKCgUHB2vp0qWaOXOmK8tt1IW9SOeOKE6fPq3U1FQXVtZyNptNAQEBSklJUUxMjNH75cJeJHP3y/f69OmjxYsX6+c//7mx++V73/cyc+bMVrFfOAI3QFVVlQ4dOqTo6Gin5dHR0Tpw4ICLqro0//nPfzRw4ECFhobqwQcf1H/+8x9Xl9RiBQUFKioqctovXl5eioqKMna/7Nu3T3379lVYWJh++ctf6uuvv3Z1SU2y2Wyqra2Vr6+vJLP3y4W9fM/E/VJTU6MtW7aorKxM4eHhRu+XC3v5nqv3i/tV/TRclOLiYtXU1MjPz89puZ+fn06ePOmiqi7eTTfdpJdfflnBwcE6deqUnn/+eY0fP1779+/XDTfc4Orymq2oqEiS6t0vhYWFrijpkowdO1Z33HGHevfurS+//FLPPvus7rzzTv31r3+Vp6enq8tr0MKFCzVo0CDH/1hN3i8X9iKZt18OHz6s8ePHq7KyUt7e3tq0aZNCQkIcIW3SfmmoF6l17BcC3CAWi8XpZ7vdXmeZCcaNG+f080033aTBgwfrjTfe0C9+8QsXVXXxfij75a677nJ8HxISosGDB2vQoEH/v717D4qy6gM4/l124DVEQAV2NYVUHJVLKZCVpmkyoKIMipccpPKGYaJjQQaSME6JioUXkJE08FayiAThBUfU8X4Ju+ioo2beKkiIhVBRYff9o9lnWHcXWMNg63xm+GPPc/Y55zznYX/POc+NoqIigoODW7FmpsXFxXHy5En27t2LXC7XW2Zp/WKqLZbWL7179+bIkSNUVVVRUFBAZGQkhYWF0nJL6hdTbfHw8GgT/SKm0C1A586dkcvlBqPt8vJyg6NZS2RnZ0ffvn25du1aa1fFLAqFAuBf2y9dunSha9eubbZfYmNjyc3NpaCggOeee05Kt8R+MdUWY9p6v9jY2NCzZ08GDBhAQkIC3t7erFu3ziL7xVRbjGmNfhEBU7KntgAAEEJJREFU3ALY2NjQv39/Dh48qJd+8OBBXnrppVaqVcupra3lypUr0j+4pXBzc0OhUOj1S21tLSdOnPhX9EtFRQW//fZbm+yXhQsXsmPHDgoKCgxuQbS0fmmsLca05X4xRqPR8PDhQ4vrF2N0bTGmNfpF/uGHHyb+Y6UJT6xDhw4kJSWhVCpp164dycnJHD9+nNTUVBwcHFq7emaJj4/HxsYGjUbD1atXiYmJ4dq1a6SkpLS5ttTU1HDp0iXKysrYsmULHh4e2Nvb8/DhQxwcHKivryclJQV3d3fq6+tZtGgRZWVlrFq1qs2dn2ysLXK5nCVLlmBnZ0ddXR3nzp0jKiqK+vp6kpOT21RboqOj2b59O1lZWXTr1o27d+9y9+5d4K+DXZlMZjH90lRbampqLKZfABITE6X/7V9++YX09HRUKhWJiYn06tXLYvoFGm+LQqFoE/0ibiOzIBs2bGD16tWUlZXRr18/li5dyuDBg1u7WmabPn06x48fp6KiAicnJ/z8/Fi0aBF9+/Zt7aoZOHLkCGPHjjVInzJlCunp6Wi1WpYtW0ZWVhZqtRpfX19WrlyJh4dHK9S2cY215bPPPiMsLIwff/yRqqoqFAoFQ4YMYdGiRXTr1q0Vamva41do6yxcuJDY2FgAi+mXptpy//59i+kX+OuWtyNHjvD7779jb2+Pp6cn8+bNY8SIEYDl9As03pa20i8igAuCIAiCBRLnwAVBEATBAokALgiCIAgWSARwQRAEQbBAIoALgiAIggUSAVwQBEEQLJAI4IIgCIJggUQAFyxeUFAQQUFBT/z9yMhIvL29W7BGlmfbtm04Ojpy48YNKe3vbldBEJ4uEcAFszk6Ojbrb9u2bU2uKzs72+Szhf8Njh49iqOjI926dePevXsGy2tqakhKSuLIkSOtULt/h6e5D3l7exvdtyMiIvTyJSUlNfq/oFKpnkr9hP828TYywWzr16/X+5yVlcW3335LamqqXnpznm+sUqm4fPkyc+bMadE6thUqlYru3btz+/Ztdu/ezYQJE/SW3717l+XLlwMwZMiQ1qiiSXl5ea1dhWZ52vuQ7glcDT3+wpGxY8fSs2dPg++mpKRw5coVXnvttadSN+G/TQRwwWyTJ0/W+3zo0CHOnj1rkP5f9+DBA/Lz85k3bx7FxcWoVCqDAN6W2djYtHYV2gSlUtnkvu3l5YWXl5demlqtZt68eQwbNsxiXjwiWBYxhS48FRqNhlWrVuHr64uLiwv9+vUjJiaGqqoqKU9QUBDFxcXcunVLb7pRZ+3atQQGBtKzZ08UCgWDBg1i8+bNf6teW7duxdfXF4VCweDBg9mzZ4/RfFqtloyMDAYNGoRCoaBHjx7MmjWLX375pdll7d27l6qqKkJDQ5kwYQIHDhygvLxcWn7jxg369OkDwPLly6X2R0ZGSnlKS0uZP38+ffv2xcXFBR8fH1avXo1Wq9Vbj6OjIykpKXz11Ve8+OKLuLi4MGjQIA4dOmRQrzNnzhAQEIBCocDLy4uUlBS99ek8fg68YTmbNm1iwIABdOnShbFjx3L9+nUAUlNT8fb2RqlUEhoaSmlpqcF6v/vuOyZPnoyrqytKpZLXX3+dvXv36uXRnZM/fvw4S5YsoU+fPiiVSsaNGyeVpatjY/vQ/fv3SUxMxNvbGxcXF55//nk+/vhjHjx4oFdeVVUVly9f1ts/G3r06JH0kpHmys/P58GDB0yaNMms7wlCc4kRuPBUvP/++2RmZjJq1CjeeecdLl68yMaNGykpKaGoqAhra2uio6NRq9WUlpaydOlSg3WsW7cOf39/QkJCkMlkFBYWMm/ePDQaDW+//bbZdfryyy+ZO3cuPj4+zJw5kzt37jB79myjLx9477332Lx5M5MnT2bmzJmUlZWRkZHBqVOnOHz4sMmXUDSUnZ2Nr68vzz33HCEhISxcuJDc3Fxmz54NgJOTE8nJycTExDBmzBjpRSM9evQA4M6dO/j7+1NXV8dbb72FUqnkxIkTJCQk8Ntvv7Fs2TK98vLz86moqGDatGm0a9eO9PR0pk6dyrlz5+jYsSMAly5dIiQkhA4dOhAdHY2NjQ1ZWVm0b9++2dsxLy+P+/fvM336dGpqali9ejVhYWGEhoZSUFDAnDlzKC0tJTU1lffee48vv/xS+u7Ro0cJDQ3Fw8ODmJgYbGxsyMvLY8qUKWzatIng4GC9suLi4njmmWdYsGABFRUVpKamEhERwb59+wAa3Ye0Wi3h4eHs37+fN954Az8/P06ePMnKlSu5ePGi3jUahYWFvPvuu6SlpREWFqa3nmPHjtGlSxfq6up49tlniYiIICoqCiurxsc/2dnZtG/fnjFjxjR72wqCOUQAF1rchQsXyMzMZNKkSWRkZEjpvXv3JjY2lq+++oo333yT4cOHo1Qqqa6uNjpFWVJSgq2trfT5nXfeISQkhDVr1pgdwOvq6khMTKRv377s3r2bdu3aAfDqq68yfvx4unfvLuU9deoUmZmZBj/mY8eOZdiwYWRkZPDBBx80Wl5lZSX79+8nISEBgE6dOjF8+HBUKpUUwNu3b09wcDAxMTF4enoabAPdSPHYsWO4uLgAMG3aNJRKJampqURGRuLm5ibl//nnnykpKcHJyUlq29ChQ9mxYwezZs0C4JNPPuHhw4fs2bNHOlAICwvDx8en2dvy9u3bnD17VjqIsbKyIikpidraWo4fPy69SrGmpoYvvviC8vJynJyc0Gq1LFiwgIEDB5Kfny8FwFmzZhEYGMjixYsNAritrS2FhYVS3o4dOxIXF8fFixfp169fo/tQUVER+/fvJzo6mvj4eABmzpyJs7Mz6enpHDp0iGHDhjXaVk9PT1555RXc3d35448/2L59OwkJCdy6dYuVK1c2uo1OnDjBxIkTzTo4EgRziCl0ocUVFRUBGFz4M336dOzt7aXlTdEF70ePHlFZWUlFRQVDhw7l2rVrJqc6TTl79iy///67NDrVef311w1eY5qXl4ednR0BAQFUVFRIf126dKFXr14cPny4yfLy8vKoq6tj3LhxUtqECRMoKSnhp59+avL7Wq2W/Px8AgMDkcvlevUYMWIEGo2GY8eO6X0nJCRECt4Azz//PPb29tKUc319PcXFxYwcOVIK3vDXTIA507zBwcF6MxB+fn5S+xq+B9nX1xetVivdmnbu3DmuXLnCpEmTpP6sqKigsrISf39/rl+/zs2bN/XKmjZtmt5IV/f63IbT6KYUFRUhk8mYO3euXvr8+fOl5TphYWGo1WqD0ff27duZP38+QUFBhIeHU1hYSGBgIBs3buTq1asmy87JyUGr1YrrQoSnSozAhRZ38+ZNZDIZvXv31kv/3//+h5ubm8GPtCm7du0iOTmZc+fOUV9fr7esuroaBweHZtfp1q1bAAZ1AnB3d+eHH36QPv/000/U1NQYzQsgk8maLC87Oxtvb28ePXokBTAvLy+sra3Jzs4mLi6u0e+Xl5ejVqvZunUrW7duNZmnoYazCDoODg5UVlZK+e/du2dyGzTX46cc7O3tAXj22WeNpqvVagDpwCUqKoqoqCij6y4vL8fV1VX6/HibdAcOujY15ubNmygUCoPTHUqlEgcHh2bvhw3JZDLeffddioqKOHz4sMntlpOTg0KhaHKELwh/hwjgwj9Kq9U2KwCePHmSqVOn8vLLL5OSkoJSqcTGxoZ9+/axbt06NBqN2eWC8eD7+AVcGo2GTp068cUXXxhdV8NpfWOuX7/OqVOnAHjhhRcMlufk5DQZwHXtmzBhAlOnTjWa5/HbluRyudF8uvaZsw0aY6qcpsrXtSkxMZH+/fsbzft4QGxqnU/q73xfd4Bh6iDixx9/5MKFC0RGRpqsvyC0BBHAhRbn6uqKVqvlypUrerfWPHz4kJs3b+rd72wqmH/99de0a9eOvLw8vSnvJ33gie5H9/LlywwfPlxv2eNT2j169ODgwYP4+vrSoUMHs8tSqVTI5XI2bNiAtbW13rILFy6wdOlSTp8+zcCBA02238nJCXt7e+rq6lpsFOfs7IytrS2XL182WNacaf2/Szdtb2dn16IjU1Pb0NXVlQMHDqBWq/VG4WVlZVRXV+uN9M2hm75veLqioZycHMDwdktBaGniHLjQ4gICAgBIS0vTS8/MzKS6uprAwEApzdbW1uj5bLlcjkwm0xtp66aUn8SAAQNwdnYmKyuL2tpaKf3AgQNcunRJL+/48ePRaDQGV3nDXyO3ioqKRstSqVQMHDiQcePGMWbMGL2/uXPn8swzz0hP5tKN5nXTzDpyuZzg4GAKCwv5/vvvDcqoqqri0aNHzWt8g3Xqbtn6+eefpfTy8nIp6DxN/fv3p1evXqxdu9Zonz9+SqC5TO1DgYGBaLVag6e0rVmzRlquY+w2MrVabTBSr6ur47PPPkMulxt9OItGoyE3N5c+ffqYnGUQhJYiRuBCi/P09GTatGlSwB4+fDgXL14kMzMTHx8fpkyZIuUdMGAABQUFLFy4ED8/P6ysrAgNDWXkyJGkpaUxbtw4Jk+eTGVlJZs2bcLFxYWysjKz62Rtbc3ixYuJiopi9OjRTJw4kfLycj7//HP69etHTU2NlHfQoEHMnj2btLQ0zp8/j7+/P7a2tty4cYPCwkLCw8NZsGCB0XJKSkq4evUqb775ptHltra2DB06lJ07d5KUlISdnR29e/dm586duLu706lTJ9zc3PDz8yMxMZFjx44xcuRIwsPD8fDw4M8//+TChQt88803nD171uwHhMTFxXHgwAFGjRrFzJkzsba2Jisri+7du5t9YaC5rKysSE1NJTQ0lJdffpmwsDBcXV0pLS3lzJkz3Lp1i5MnT5q9XlP7UGBgIP7+/qxYsYLbt2/j4+PD6dOnUalUjB49Wm8WwNhtZLt27SItLY2AgADc3NxQq9Xk5uZy/vx53n//fYOnscFfM0S//vorH3300ZNuJkFoNhHAhafi008/xc3Njc2bN7Nv3z46d+7MjBkziI+P15tWjoiI4NKlS6hUKjIyMtBqtYSGhjJkyBDS09NJSUkhNjaWrl27EhERgaOjo8FVxc0VHh6OVqtl1apVJCQk4O7uzvr16ykoKODo0aN6eZcvX07//v3ZuHEjSUlJWFlZ0bVrV0aMGNHofb3Z2dkAjBo1ymSekSNHSrc4jRo1irS0NGJjY4mPj+fBgwdMmTIFPz8/nJycKC4uJjk5mV27dpGVlYWDgwPu7u58+OGH0r3d5vDw8CAvL4/4+HiSk5NxdnZmxowZODs7P/F2Nccrr7xCcXExK1asICsri+rqapydnfHy8iI2NvaJ1mlqH5LJZGzZsoVly5aRm5tLTk4OSqWS6OhoYmJimlyvp6cnbm5u5OTkcOfOHWxsbPDw8CAjI8PkVfsqlQqZTMbEiROfqC2CYA6ZWq3+e1eDCIIgCILwjxPnwAVBEATBAokALgiCIAgWSARwQRAEQbBAIoALgiAIggUSAVwQBEEQLJAI4IIgCIJggUQAFwRBEAQLJAK4IAiCIFggEcAFQRAEwQKJAC4IgiAIFuj/Ct7uI7qrYJcAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
