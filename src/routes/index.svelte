<script>
    import TodoItem from '$lib/todo-item.svelte';

    const pageTitle = "Todos"
</script>

<svelte:head>
    <title>{pageTitle}</title>
</svelte:head>

<h1>{pageTitle}</h1>
<form action="" method="">
    <input type="text" name="text" aria-label="add a todo" placeholder="+ type to add a todo">
</form>

<TodoItem />