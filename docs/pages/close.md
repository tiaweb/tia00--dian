<!DOCTYPE html>
<html>
    <head>
        <title>Title</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
<script src="https://cdnjs.cloudflare.com/ajax/libs/prism/0.0.1/prism.min.js"></script>

<link rel="stylesheet" href="https://tiaweb.github.io/tiadian/theme.css">

 <link rel="stylesheet" href="https://tiaweb.github.io/tiadian/style.css">
 <script  src="https://tiaweb.github.io/tiadian/script.js"></script>
	</head>
	<body>
<div class="tiadian-card tiadian-card-default tiadian-card-body">
    <div class="tiadian-card-badge tiadian-label">V1.0</div>
    <h3 class="tiadian-card-title"><a class="navbar-brand logo-image" href="https://tiaweb.github.io/tiadian/index.html"><img src="https://tiaweb.github.io/images/logo.svg" alt="alternative"></a></h3>
    <p>

<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="Close_0"></a>Close</h1>
<p class="has-line-data" data-line-start="2" data-line-end="3">&lt;p class=“tiadian-text-lead”&gt;Create a close icon that can be combined with different components.&lt;/p&gt;</p>
<h2 class="code-line" data-line-start=4 data-line-end=5 ><a id="Usage_4"></a>Usage</h2>
<p class="has-line-data" data-line-start="6" data-line-end="7">To apply this component, add the <code>tiadian-close</code> attribute to an <code>&lt;a&gt;</code> or <code>&lt;button&gt;</code> element.</p>
<pre>
<code class="language-java">
<span class="hljs-tag">&lt;<span class="hljs-title">button</span> <span class="hljs-attribute">type</span>=<span class="hljs-value">"button"</span> <span class="hljs-attribute">tiadian-close</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-title">button</span>&gt;</span>

<span class="hljs-tag">&lt;<span class="hljs-title">a</span> <span class="hljs-attribute">href</span>=<span class="hljs-value">""</span> <span class="hljs-attribute">tiadian-close</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-title">a</span>&gt;</span>
</code></pre>


<pre>
<code class="language-java">
&lt;button type=&quot;button&quot; tiadian-close&gt;&lt;/button&gt;
</code></pre>
<hr>
<h2 class="code-line" data-line-start=21 data-line-end=22 ><a id="Large_modifier_21"></a>Large modifier</h2>
<p class="has-line-data" data-line-start="23" data-line-end="24">Add the <code>.tiadian-close-large</code> class for a larger close button.</p>
<pre>
<code class="language-java">
<span class="hljs-tag">&lt;<span class="hljs-title">button</span> <span class="hljs-attribute">class</span>=<span class="hljs-value">"tiadian-close-large"</span> <span class="hljs-attribute">type</span>=<span class="hljs-value">"button"</span> <span class="hljs-attribute">tiadian-close</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-title">button</span>&gt;</span>
</code></pre>
<pre>
<code class="language-java">
&lt;button class=&quot;tiadian-close-large&quot; type=&quot;button&quot; tiadian-close&gt;&lt;/button&gt;
</code></pre>
<hr>
<h2 class="code-line" data-line-start=36 data-line-end=37 ><a id="Close_in_alerts_36"></a>Close in alerts</h2>
<p class="has-line-data" data-line-start="38" data-line-end="39">This is an example of how this component is used with an alert box from the <a href="alert.md">Alert component</a>.</p>
<pre>
<code class="language-java">
<span class="hljs-tag">&lt;<span class="hljs-title">div</span> <span class="hljs-attribute">tiadian-alert</span>&gt;</span>
    <span class="hljs-tag">&lt;<span class="hljs-title">button</span> <span class="hljs-attribute">class</span>=<span class="hljs-value">"tiadian-alert-close"</span> <span class="hljs-attribute">type</span>=<span class="hljs-value">"button"</span> <span class="hljs-attribute">tiadian-close</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-title">button</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-title">div</span>&gt;</span>
</code></pre>
<div tiadian-alert>
    <button class="tiadian-alert-close" type="button" tiadian-close></button>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
</div>
<pre>
<code class="language-java">
&lt;div tiadian-alert&gt;
    &lt;button class=&quot;tiadian-alert-close&quot; type=&quot;button&quot; tiadian-close&gt;&lt;/button&gt;
    &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.&lt;/p&gt;
&lt;/div&gt;
</code></pre>
<hr>
<h2 class="code-line" data-line-start=55 data-line-end=56 ><a id="Close_in_drops_55"></a>Close in drops</h2>
<p class="has-line-data" data-line-start="57" data-line-end="58">This is an example of how this component is used with the <a href="drop.md">Drop component</a>.</p>
<pre>
<code class="language-java">
<span class="hljs-tag">&lt;<span class="hljs-title">div</span> <span class="hljs-attribute">tiadian-drop</span>&gt;</span>
    <span class="hljs-tag">&lt;<span class="hljs-title">button</span> <span class="hljs-attribute">class</span>=<span class="hljs-value">"tiadian-drop-close"</span> <span class="hljs-attribute">type</span>=<span class="hljs-value">"button"</span> <span class="hljs-attribute">tiadian-close</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-title">button</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-title">div</span>&gt;</span>
</code></pre>
<div class="tiadian-inline">
    <button class="tiadian-button tiadian-button-default" type="button">Click</button>
    <div tiadian-drop="mode: click">
        <div class="tiadian-card tiadian-card-body tiadian-card-default">
            <button class="tiadian-drop-close" type="button" tiadian-close></button>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.</p>
        </div>
    </div>
</div>
<pre>
<code class="language-java">
&lt;div class=&quot;tiadian-inline&quot;&gt;
    &lt;button class=&quot;tiadian-button tiadian-button-default&quot; type=&quot;button&quot;&gt;Click&lt;/button&gt;
    &lt;div tiadian-drop=&quot;mode: click&quot;&gt;
        &lt;div class=&quot;tiadian-card tiadian-card-body tiadian-card-default&quot;&gt;
            &lt;button class=&quot;tiadian-drop-close&quot; type=&quot;button&quot; tiadian-close&gt;&lt;/button&gt;
            &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.&lt;/p&gt;
        &lt;/div&gt;
    &lt;/div&gt;
&lt;/div&gt;
</code></pre>
<hr>
<h2 class="code-line" data-line-start=79 data-line-end=80 ><a id="Close_in_modals_79"></a>Close in modals</h2>
<p class="has-line-data" data-line-start="81" data-line-end="82">This is an example of how this component is used with the <a href="modal.md">Modal component</a>.</p>
<pre>
<code class="language-java">
<span class="hljs-tag">&lt;<span class="hljs-title">div</span> <span class="hljs-attribute">id</span>=<span class="hljs-value">"modal"</span> <span class="hljs-attribute">tiadian-modal</span>&gt;</span>
    <span class="hljs-tag">&lt;<span class="hljs-title">div</span> <span class="hljs-attribute">class</span>=<span class="hljs-value">"tiadian-modal-dialog tiadian-modal-body"</span>&gt;</span>
        <span class="hljs-tag">&lt;<span class="hljs-title">button</span> <span class="hljs-attribute">class</span>=<span class="hljs-value">"tiadian-modal-close-default"</span> <span class="hljs-attribute">type</span>=<span class="hljs-value">"button"</span> <span class="hljs-attribute">tiadian-close</span>&gt;</span><span class="hljs-tag">&lt;/<span class="hljs-title">button</span>&gt;</span>
    <span class="hljs-tag">&lt;/<span class="hljs-title">div</span>&gt;</span>
<span class="hljs-tag">&lt;/<span class="hljs-title">div</span>&gt;</span>
</code></pre>

<a class="tiadian-button tiadian-button-default" href="#modal" tiadian-toggle>Open modal</a>
<div id="modal" tiadian-modal>
    <div class="tiadian-modal-dialog tiadian-modal-body">
        <button class="tiadian-modal-close-default" type="button" tiadian-close></button>
        <h2 class="tiadian-modal-title">Headline</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        <p class="tiadian-text-right">
            <button class="tiadian-button tiadian-button-default tiadian-modal-close" type="button">Cancel</button>
            <button class="tiadian-button tiadian-button-primary" type="button">Save</button>
        </p>
    </div>
</div><pre>
<code class="language-java">
&lt;a class=&quot;tiadian-button tiadian-button-default&quot; href=&quot;#modal&quot; tiadian-toggle&gt;Open modal&lt;/a&gt;
&lt;div id=&quot;modal&quot; tiadian-modal&gt;
    &lt;div class=&quot;tiadian-modal-dialog tiadian-modal-body&quot;&gt;
        &lt;button class=&quot;tiadian-modal-close-default&quot; type=&quot;button&quot; tiadian-close&gt;&lt;/button&gt;
        &lt;h2 class=&quot;tiadian-modal-title&quot;&gt;Headline&lt;/h2&gt;
        &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.&lt;/p&gt;
        &lt;p class=&quot;tiadian-text-right&quot;&gt;
            &lt;button class=&quot;tiadian-button tiadian-button-default tiadian-modal-close&quot; type=&quot;button&quot;&gt;Cancel&lt;/button&gt;
            &lt;button class=&quot;tiadian-button tiadian-button-primary&quot; type=&quot;button&quot;&gt;Save&lt;/button&gt;
        &lt;/p&gt;
    &lt;/div&gt;
&lt;/div&gt;
</code></pre>
</p>
</div>
<style>
table, td, th {  
  border: 1px solid #ddd;
  text-align: left;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  padding: 15px;
}
</style>

</body>
</html>
