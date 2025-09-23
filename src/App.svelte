<script lang="ts">
  let files: FileList | null = $state(null);

  $effect(() => {
    console.log(files, "files");
  });
</script>

<main>
  <div>
    <p>Upload File</p>
  </div>
  <div class="card">
    <input bind:files type="file" />
  </div>
</main>

<style>
</style>
