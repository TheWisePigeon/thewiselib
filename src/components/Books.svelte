<script lang="ts">
    import Book from "./Book.svelte";

  const books = [
    {
      title: "It is okay not to know...Or is it??",
      link: "iiontkoii"
    },
  ];
</script>


<div class=" flex justify-center m-auto w-full " >
    {#each books as book}
        <Book link={book.link}  />
    {/each}
</div>
