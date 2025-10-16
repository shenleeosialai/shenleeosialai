<h1 align="center">
  <a href="#" style="text-decoration: none; color: inherit;">
    <span id="typewriter"></span>
  </a>
</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Code-Python-blue?logo=python" />
  <img src="https://img.shields.io/badge/Code-Go-00ADD8?logo=go" />
  <img src="https://img.shields.io/badge/Code-C++-00599C?logo=cplusplus" />
  <img src="https://img.shields.io/badge/OS-Linux-FCC624?logo=linux&logoColor=black" />
</p>

<div align="center">
  <pre>
  ~ currently working on backend projects
  ~ Learning GO, still trying to understand C++
  ~ I love Python, JavaScript not that much
  ~ Always open to collaborate and learn
  ~ ooh and a hardcore Linux user!!
  </pre>
</div>

<style>
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}
@keyframes blink {
  50% { border-color: transparent }
}
#typewriter {
  display: inline-block;
  overflow: hidden;
  border-right: .15em solid orange;
  white-space: nowrap;
  letter-spacing: .05em;
  animation: typing 3.5s steps(30, end), blink .75s step-end infinite;
  font-family: monospace;
  font-size: 1.5em;
  color: #ff8c00;
}
</style>

<script>
const text = "Hi, I'm Shen Lee ";
let i = 0;
function typeWriter() {
  if (i < text.length) {
    document.getElementById("typewriter").innerHTML += text.charAt(i);
    i++;
    setTimeout(typeWriter, 100);
  }
}
typeWriter();
</script>
