<script>
  import NavItem from "./NavItem.svelte";

  const itemList = [
    { text: "home", link: "/" },
    { text: "blog", link: "/blog" },
    { text: "resume", link: "/resume" },
  ];
</script>

<header>
  <nav class="container mx-auto py-8">
    <ul class="sm:flex justify-between text-xl uppercase">
      {#each itemList as item}
        <NavItem {...item} />
      {/each}
    </ul>
  </nav>
</header>
