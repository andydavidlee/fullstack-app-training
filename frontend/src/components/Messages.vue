<template>
    <div>
        <h1>hello world</h1>
        <ul v-for="message in messages":key="array">
            <li>{{message}}</li>
        </ul>
    </div>
</template>

<script>
export default {
    // name: messages,
    data: function() {
        return {
            messages: ["hello", "hi"]
    };

}
}
</script>