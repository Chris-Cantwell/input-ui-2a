<script>
    export let days = [0,0,0,0,0,0,0]
    export let hours = [days, days, days]
</script>

<center>
    <table>
        <tr>
            <th>Sunday</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        {#each hours as hour}
            <tr>
            {#each days as day}
                <td>{day}</td>
            {/each}
            </tr>
        {/each}
    </table>
</center>
