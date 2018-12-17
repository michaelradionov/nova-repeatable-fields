<template>
    <div>
        <input
                :id="subField.name"
                :name="subField.name"
                type="file"
        />
        <p>{{subField}}</p>
        <p>{{value}}</p>
    </div>
</template>

<script>
    export default {
        props: ['value', 'subField'],
    };
</script>

