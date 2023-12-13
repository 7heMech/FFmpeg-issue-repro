<div>
  {#if typeof SharedArrayBuffer != 'undefined'}
    <p>Headers passed</p>
  {:else}
    <p>Headers not passed</p>
  {/if}
</div>