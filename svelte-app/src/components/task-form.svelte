<script lang="ts">
    let newTask = $state("");

    function formSubmitted(e: SubmitEvent) {
        e.preventDefault();
        console.log(newTask);   
    }
</script>

<form onsubmit={formSubmitted}>
    <label>
        Task
        <input name="newTask" bind:value={newTask}/>
    </label>
    <div class="button-container">
        <button>Add Task</button>
    </div>
</form>

<style lang="scss">
.button-container {
    display: flex;
    justify-content: end;
}
</style>

