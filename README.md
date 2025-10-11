<div class="typing-container">
  <div class="typing-text line1">Hello Wrld!</div>
</div>

<style>
.typing-text {
  font-family: 'Inconsolata', monospace;
  color: #A7A459;
  overflow: hidden;
  border-right: 2px solid #A7A459;
  white-space: nowrap;
  margin: 0;
  opacity: 0;
}


.line1 {
  animation: typing 5s steps(40, end) forwards;
}

@keyframes typing {
  from { width: 0; opacity: 1; }
  to { width: 100%; opacity: 1; }
}

@keyframes blink {
  50% { border-color: transparent; }
}
</style>
