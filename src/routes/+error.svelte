<script>
	import { page } from '$app/state';
</script>
<main>
  <div id="text"><div id="text">
    <div class="line">
      <p class="word">error</p>
    </div>
  
    <div class="line">
      <p class="word">{page.status}</p>
    </div>
  
    <div class="line">
      <p class="word">{page.error.message}</p>
    </div>
  </div>
</main>