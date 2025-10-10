

<pre class="mermaid">
graph TD
A([Inizio]) --> B[/'Buongiorno!'/] --> Z[/input: nomeutente /] --> Y[/input: password /] --> X{nomeutente = nomeGiusto?} --sì--> C{password = passGiusta?} --> F([Fine])
X -- no -->Z

</pre>


<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.10.0-rc.1/dist/katex.min.css" integrity="sha384-D+9gmBxUQogRLqvARvNLmA9hS2x//eK1FhVb9PiU86gmcrBrJAQT8okdJ4LMp2uv" crossorigin="anonymous">
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.10.0-rc.1/dist/katex.min.js" integrity="sha384-483A6DwYfKeDa0Q52fJmxFXkcPCFfnXMoXblOkJ4JcA8zATN6Tm78UNL72AKk+0O" crossorigin="anonymous"></script>
<script defer src="https://cdn.jsdelivr.net/npm/katex@0.10.0-rc.1/dist/contrib/auto-render.min.js" integrity="sha384-yACMu8JWxKzSp/C1YV86pzGiQ/l1YUfE8oPuahJQxzehAjEt2GiQuy/BIvl9KyeF" crossorigin="anonymous"></script>
<script>
  window.onload = () => {
    renderMathInElement(document.body, {
      delimiters: [
        {left: "$$", right: "$$", display: true},
        {left: "$", right: "$", display: false}
      ],
      macros: {
        "\\\n": "\\\\",
      }
    });
  };
</script>

<script type="module" src="https://unpkg.com/mermaid@9.4.0/dist/mermaid.min.js"></script>




