---
layout: default
title: Contacto
---
[Início](index.md) · [Livros](livros.md) · [Contos](contos.md) · [Videojogos](videojogos.md) · [Sobre](sobre.md) · [Contacto](contacto.md)

# Contacto

- **Email**: <robsonsiebel@gmail.com>
- **Redes**: Não, obrigado

## Newsletter

<div class="newsletter-embed" style="max-width:520px">
  <iframe
    id="ss-embed"
    title="Subscrição da newsletter"
    src="https://robsonsiebel.substack.com/embed"
    loading="lazy"
    style="width:100%; height:320px; border:1px solid #EEE; background:#fff;"
    frameborder="0" scrolling="no"></iframe>

  <!-- Fallback (aparece se a iframe não carregar, p.ex. com adblock) -->
  <div id="ss-alt" style="display:none; margin-top:.75rem;">
    <a href="https://robsonsiebel.substack.com/subscribe"
       class="button" target="_blank" rel="noopener"
       style="display:inline-block;padding:.6rem 1rem;border:1px solid #222;border-radius:10px;text-decoration:none">
      Subscrever no Substack
    </a>
  </div>

  <noscript>
    <p style="margin-top:.75rem">
      Com o JavaScript desligado, use este link:
      <a href="https://robsonsiebel.substack.com/subscribe" target="_blank" rel="noopener">abrir Substack</a>.
    </p>
  </noscript>
</div>

<script>
  (function () {
    var alt = document.getElementById('ss-alt');
    var frame = document.getElementById('ss-embed');
    // mostra o fallback se a iframe não carregar em ~1,2s (ex.: bloqueada por adblock)
    var timer = setTimeout(function () { alt.style.display = 'block'; }, 1200);
    frame.addEventListener('load', function () {
      clearTimeout(timer);
      alt.style.display = 'none';
    });
  })();
</script>
