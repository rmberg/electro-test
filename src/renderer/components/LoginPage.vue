<template>

    <div class="ui middle aligned center aligned grid">
        <div class="column left aligned">
            <form class="ui form">
                <div class="field">
                    <label>E-Mail Address</label>
                    <input type="text" name="email">
                </div>
                <div class="field">
                    <label>Password</label>
                    <input type="password" name="password">
                </div>
                <button class="ui button" type="submit">Login</button>
            </form>
        </div>
    </div>
</template>


<script>
  export default {
    name: 'login-page',
    methods: {}
  }
</script>

<style>

    .column {
        max-width: 350px;
    }

</style>
