<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>♡The maids coffee♡</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="a573ba66-5394-44c1-b2fb-90e04e195242" class="page sans"><header><img class="page-cover-image" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/LOGO_OFICIAL_copia2.jpg" style="object-position:center 50%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">☕</span></div><h1 class="page-title"><strong><strong>♡</strong></strong>The maids coffee<strong><strong>♡</strong></strong></h1><p class="page-description"></p></header><div class="page-body"><h1 id="9f6a9763-6421-4bc4-b9d6-a779760f3fd9" class="">🍒🍓🥝<strong><strong>♡</strong></strong>Menú de comidas<strong><strong>♡</strong></strong>🍒🍓🥝</h1><div id="ebe8fb8e-e861-4182-abf6-c0d42506427b" class="column-list"><div id="4cd6a8b8-eeb2-4500-9ceb-7041d81c7dbe" style="width:37.5%" class="column"><blockquote id="18f37ed8-591e-431f-bb86-3bda8cf17f35" class="">Alimentos </blockquote><ul id="b115bd2a-0331-4292-b307-b8a41b272eb9" class="bulleted-list"><li style="list-style-type:disc">Hotcakes Babys: $10</li></ul><ul id="7a168f4a-f3ea-45fb-9f49-e5501eac6e64" class="bulleted-list"><li style="list-style-type:disc">Alitas veganas: $25</li></ul><ul id="e4bbaf75-8cdf-4c0d-a261-086f6f4250d4" class="bulleted-list"><li style="list-style-type:disc">Donas: $10</li></ul><ul id="478bbd34-8d7a-4822-ba32-f20121a5e11d" class="bulleted-list"><li style="list-style-type:disc">Ramen dulce: $70</li></ul><ul id="e51ef1be-5276-4569-8b64-85d9e7c27011" class="bulleted-list"><li style="list-style-type:disc">Ramen picante: $70</li></ul><ul id="ceb1a09f-646a-481a-9071-871f74b48488" class="bulleted-list"><li style="list-style-type:disc">Curry: $70</li></ul><ul id="4558c302-0395-41b7-bf8c-918a5224c9ef" class="bulleted-list"><li style="list-style-type:disc">Fresas con crema: $25</li></ul><blockquote id="83973f56-d762-4030-bbb8-4c41ea9a907a" class="">Bebidas</blockquote><ul id="eaacb2f1-56c4-4c5d-ad6b-d3e5c71d9127" class="bulleted-list"><li style="list-style-type:disc">Tapioca $40</li></ul><ul id="dbe2a084-caf9-4bc4-80d7-2d733834cc91" class="bulleted-list"><li style="list-style-type:disc">Ice coffee $25</li></ul><ul id="5977034b-bf84-4e22-b5db-17e415803629" class="bulleted-list"><li style="list-style-type:disc">Coffee $20</li></ul><ul id="2f072668-c84c-4efd-8850-98ff4fce8702" class="bulleted-list"><li style="list-style-type:disc">Coca Cola $30</li></ul><hr id="e8f4e58f-0e9f-4108-9680-c0a61c8fd4c1"/></div><div id="e62df0ac-907e-424f-ade7-dd2fbf3f4ab0" style="width:62.5%" class="column"><figure id="fa69797a-f7e3-4ba6-8ce1-05f32c431af0" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/LOGO_OFICIAL.png"><img style="width:576px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/LOGO_OFICIAL.png"/></a></figure><p id="4aa4ea93-a3b1-43f6-ad4f-8017b5858a55" class="">
</p></div></div><h1 id="a7d1f936-8167-4a31-94d4-1c9dc561a1e1" class=""><strong><strong>♡♡♡♡♡♡</strong></strong> Explicaciones de los alimentos: <strong><strong>♡♡♡♡♡♡</strong></strong></h1><p id="1b29c339-94c6-42f9-ab82-14a17d29b386" class="">Aquí están fotitos de los alimentos</p><div id="b193d71d-c308-4263-97c6-e046f0ed09af" class="column-list"><div id="edfb86e2-89dd-4385-b67f-e9622c1a977e" style="width:50%" class="column"><figure id="c915735d-6ba3-4cb8-a8b3-77207b820820" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/31.jpeg"><img style="width:736px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/31.jpeg"/></a></figure><h1 id="a69aef29-eeb7-4b8e-87c1-e006838a3f36" class=""><strong><strong>♡</strong></strong><mark class="highlight-orange_background">Ramen picante: </mark></h1><ul id="0f07d89a-968e-47eb-b4af-e6c990276e7f" class="toggle"><li><details open=""><summary><mark class="highlight-orange_background"><strong>Envoltorio negro</strong></mark><mark class="highlight-orange_background">: </mark></summary><p id="6f59d87e-49de-4158-87c4-d8eeef1c76fa" class="">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo.</p></details></li></ul><figure id="d4183a0f-775d-42e7-9bd2-96f5798fad08" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/descarga_(3).jpeg"><img style="width:675px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/descarga_(3).jpeg"/></a></figure><h1 id="e3f130ef-d9ef-43b0-a925-e3696651f4af" class=""><strong><strong>♡</strong></strong><mark class="highlight-teal_background">Alitas veganas: </mark></h1><ul id="9c18a9a8-720f-403a-b9f5-d2665ffd8bdb" class="toggle"><li><details open=""><summary><mark class="highlight-teal_background">Alitas de coliflor: </mark></summary></details></li></ul><figure id="0fc5279d-ee31-4082-a22f-327c49d181ec" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/Alitas_de_Coliflor.jpeg"><img style="width:640px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/Alitas_de_Coliflor.jpeg"/></a></figure></div><div id="59de7ab0-9a55-4c68-9284-0d993daa425e" style="width:50%" class="column"><h1 id="dae3c8c9-d95e-4d99-8119-ba1b7f7a57ee" class=""><strong><strong>♡</strong></strong><mark class="highlight-red_background"><strong>Ramen dulce: </strong></mark></h1><ul id="49743648-80a2-4f3e-bf79-ed533db32e49" class="toggle"><li><details open=""><summary><mark class="highlight-red_background"><strong>Envoltorio rosado: </strong></mark></summary><p id="028dd9ee-5388-4ad9-9597-adac1a8b4af2" class="">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo.</p></details></li></ul><figure id="e082539e-10ab-4635-be77-4a469e154033" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/descarga_(1).jpeg"><img style="width:336px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/descarga_(1).jpeg"/></a></figure><h1 id="7c307797-bc68-417f-9e94-fec79394a1b3" class=""><strong><strong>♡</strong></strong><mark class="highlight-yellow_background">Ramen de curry: </mark></h1><ul id="c13fd86e-953c-4e0d-9135-228ae93d0d16" class="toggle"><li><details open=""><summary><mark class="highlight-yellow_background"><strong>Envoltorio amarillo</strong></mark><mark class="highlight-yellow_background">: </mark></summary><p id="d329743a-feae-4f1e-a682-b5a0f837b1e4" class="">Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam eaque ipsa, quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt, explicabo.</p></details></li></ul><figure id="2109d5c6-c18e-4b55-8d89-724cf79a7165" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/descarga_(2).jpeg"><img style="width:490px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/descarga_(2).jpeg"/></a></figure><h1 id="9ff3b489-81d9-49cf-8b9e-b8f43398c60b" class=""><strong><strong>♡</strong></strong><mark class="highlight-purple_background">Fresas con crema: </mark></h1><ul id="e41852d5-5c90-43db-bccb-0b6a8c02734e" class="toggle"><li><details open=""><summary><mark class="highlight-purple_background">Fresas congeladas : </mark></summary></details></li></ul><figure id="5341b2e6-a0ce-42f8-92c1-b70255b86477" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/Fresas_con_crema.jpeg"><img style="width:736px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/Fresas_con_crema.jpeg"/></a></figure></div></div><figure id="e371c8aa-6d39-4729-b75b-e8a8801f7b46" class="image"><a href="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/LOGO_OFICIAL_copia3.jpg"><img style="width:2620px" src="%E2%99%A1The%20maids%20coffee%E2%99%A1%20a573ba66539444c1b2fb90e04e195242/LOGO_OFICIAL_copia3.jpg"/></a></figure></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
