---
title: Progress
desc: Progress bar can be used to show the progress of a task or to show the passing of time.
published: true
---

<script>
  import Component from "@components/Component.svelte"
  import ClassTable from "@components/ClassTable.svelte"
</script>

<ClassTable
data="{[

]}"
/>

<Component title="Progress">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress w-56" value="0" max="100"></progress>
  <progress class="progress w-56" value="10" max="100"></progress>
  <progress class="progress w-56" value="40" max="100"></progress>
  <progress class="progress w-56" value="70" max="100"></progress>
  <progress class="progress w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress w-56" value="0" max="100"></progress>
<progress class="progress w-56" value="10" max="100"></progress>
<progress class="progress w-56" value="40" max="100"></progress>
<progress class="progress w-56" value="70" max="100"></progress>
<progress class="progress w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Primary color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-primary w-56" value="0" max="100"></progress>
  <progress class="progress progress-primary w-56" value="10" max="100"></progress>
  <progress class="progress progress-primary w-56" value="40" max="100"></progress>
  <progress class="progress progress-primary w-56" value="70" max="100"></progress>
  <progress class="progress progress-primary w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-primary w-56" value="0" max="100"></progress>
<progress class="progress progress-primary w-56" value="10" max="100"></progress>
<progress class="progress progress-primary w-56" value="40" max="100"></progress>
<progress class="progress progress-primary w-56" value="70" max="100"></progress>
<progress class="progress progress-primary w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Secondary color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-secondary w-56" value="0" max="100"></progress>
  <progress class="progress progress-secondary w-56" value="10" max="100"></progress>
  <progress class="progress progress-secondary w-56" value="40" max="100"></progress>
  <progress class="progress progress-secondary w-56" value="70" max="100"></progress>
  <progress class="progress progress-secondary w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-secondary w-56" value="0" max="100"></progress>
<progress class="progress progress-secondary w-56" value="10" max="100"></progress>
<progress class="progress progress-secondary w-56" value="40" max="100"></progress>
<progress class="progress progress-secondary w-56" value="70" max="100"></progress>
<progress class="progress progress-secondary w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Accent color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-accent w-56" value="0" max="100"></progress>
  <progress class="progress progress-accent w-56" value="10" max="100"></progress>
  <progress class="progress progress-accent w-56" value="40" max="100"></progress>
  <progress class="progress progress-accent w-56" value="70" max="100"></progress>
  <progress class="progress progress-accent w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-accent w-56" value="0" max="100"></progress>
<progress class="progress progress-accent w-56" value="10" max="100"></progress>
<progress class="progress progress-accent w-56" value="40" max="100"></progress>
<progress class="progress progress-accent w-56" value="70" max="100"></progress>
<progress class="progress progress-accent w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Success color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-success w-56" value="0" max="100"></progress>
  <progress class="progress progress-success w-56" value="10" max="100"></progress>
  <progress class="progress progress-success w-56" value="40" max="100"></progress>
  <progress class="progress progress-success w-56" value="70" max="100"></progress>
  <progress class="progress progress-success w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-success w-56" value="0" max="100"></progress>
<progress class="progress progress-success w-56" value="10" max="100"></progress>
<progress class="progress progress-success w-56" value="40" max="100"></progress>
<progress class="progress progress-success w-56" value="70" max="100"></progress>
<progress class="progress progress-success w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Info color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-info w-56" value="0" max="100"></progress>
  <progress class="progress progress-info w-56" value="10" max="100"></progress>
  <progress class="progress progress-info w-56" value="40" max="100"></progress>
  <progress class="progress progress-info w-56" value="70" max="100"></progress>
  <progress class="progress progress-info w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-info w-56" value="0" max="100"></progress>
<progress class="progress progress-info w-56" value="10" max="100"></progress>
<progress class="progress progress-info w-56" value="40" max="100"></progress>
<progress class="progress progress-info w-56" value="70" max="100"></progress>
<progress class="progress progress-info w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Warning color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-warning w-56" value="0" max="100"></progress>
  <progress class="progress progress-warning w-56" value="10" max="100"></progress>
  <progress class="progress progress-warning w-56" value="40" max="100"></progress>
  <progress class="progress progress-warning w-56" value="70" max="100"></progress>
  <progress class="progress progress-warning w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-warning w-56" value="0" max="100"></progress>
<progress class="progress progress-warning w-56" value="10" max="100"></progress>
<progress class="progress progress-warning w-56" value="40" max="100"></progress>
<progress class="progress progress-warning w-56" value="70" max="100"></progress>
<progress class="progress progress-warning w-56" value="100" max="100"></progress>`
}</pre>
</Component>

<Component title="Error color">
<div class="flex flex-col gap-2 items-center">
  <progress class="progress progress-error w-56" value="0" max="100"></progress>
  <progress class="progress progress-error w-56" value="10" max="100"></progress>
  <progress class="progress progress-error w-56" value="40" max="100"></progress>
  <progress class="progress progress-error w-56" value="70" max="100"></progress>
  <progress class="progress progress-error w-56" value="100" max="100"></progress>
</div>
<pre slot="html">{
`<progress class="progress progress-error w-56" value="0" max="100"></progress>
<progress class="progress progress-error w-56" value="10" max="100"></progress>
<progress class="progress progress-error w-56" value="40" max="100"></progress>
<progress class="progress progress-error w-56" value="70" max="100"></progress>
<progress class="progress progress-error w-56" value="100" max="100"></progress>`
}</pre>
</Component>