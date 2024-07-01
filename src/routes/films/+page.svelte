<script>
    let films = [
        {id: 1, name: 'The Godfather', director: 'Francis Capolla'},
        {id: 1, name: 'The Godfather', director: 'Francis Capolla'}
    ]
</script>

<ul>
    {#each films as film}
    <li>
        <a href="films/{film.id}">{film.name}</a>
    </li>
    {/each}
</ul>