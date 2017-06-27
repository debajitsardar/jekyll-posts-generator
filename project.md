---
layout: post
title:  "ANGULAR JSON VIEWER"
date:   2015-01-30 12:00:00
categories: project
description: JSON in HTML with syntax highlight like Chrome DevTools.
img: pic02.png
link: "https://github.com/gofynd/angular-json-viewer"
---


<p>Angular JSON Viewer component. JSON in HTML with syntax highlight like Chrome DevTools.</p>

<h2 id="install">Install</h2>

<pre><code>npm install @gofynd/angular-json-viewer --save
</code></pre>

<h2 id="usage">Usage</h2>

<p>import FyAngularJsonViewerModule to use in angular app. </p>

<pre><code class="js language-js">import { FyAngularJsonViewerModule } from '@gofynd/angular-json-viewer';

@NgModule({
    ...,
    imports: [
        ...,
        FyAngularJsonViewerModule,
        ...
    ],
    ...
})
export class AppModule { }
</code></pre>

<pre><code class="html language-html">&lt;fy-angular-json-viewer [json]="object"&gt;&lt;/fy-angular-json-viewer&gt;
</code></pre>
