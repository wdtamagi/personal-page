<script lang="ts">
  export let link: string;
  export let text: string;
</script>

<li>
  <a href={link} class="hover:text-purple-900 font-bold">
    {text}
  </a>
</li>
