<script context="module">
    export const load = ({url, params}) => {

        const id = params.id;

        return {
            props: {
                id,
            }
        }
    }
</script>

<script>
    export let id;
</script>

{id}
<h1>Blog post</h1>