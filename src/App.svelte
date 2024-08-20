<script lang="ts">
    import { Button } from 'flowbite-svelte';
</script>

<form on:submit={() => console.log('submitted')}>
    <Button type="submit" disabled={true}>Submit</Button>
</form>
