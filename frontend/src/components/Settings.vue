<template>
    <div class="room-settings">
        <input
            type="text"
            class="input"
            placeholder="Paste a link or search"
        />
    </div>
</template>

<script>
export default {};
</script>

<style lang="less">
@import url("../assets/theme.less");

.room-settings {
    display:flex;
    flex-direction: column;
    width: 100%;
    border-bottom: 1px solid @primary;
}

</style>
