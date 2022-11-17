<template>
  <div id="legend" class="container">
    <div class="row">
      <div class="col" id="leftInstr">
        <strong>How to Label Points</strong></br>
        <strong>Click</strong> a point to toggle it as labeled</br>
        <strong>Click & Drag</strong> over a selection of points to label them</br>
        <strong><kbd>SHIFT</kbd> + Click & Drag </strong> over a selection of points to unlabel them</br>
      </div>
      <div class="col" id="rightInstr">
        <strong>How to Navigate the Graph</strong></br>
        <kbd>1</kbd> ~ <kbd>9</kbd> : <strong>Label</strong> Corresponding to the number</br>
        <kbd>D</kbd> or <kbd>A</kbd> : pan</br>
        <kbd>SHIFT</kbd> + <kbd>D</kbd> or <kbd>A</kbd> : fast pan</br>
        <kbd>W</kbd> or <kbd>S</kbd>: zoom</br>
        <strong>Click & Drag</strong> the bottom context bar to adjust focus region</br>
        <strong> Work on Progress </strong>
        <kbd>←</kbd> Previous Active Series </br>
        <kbd>→</kbd> Next Active Series </br>
        <kbd>↑</kbd> Previous Reference Series </br>
        <kbd>↓</kbd> Next Reference Series </br>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "LabelerInstruction"
};
</script>