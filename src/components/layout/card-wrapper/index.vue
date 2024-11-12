<template>
    <div class="wrapper">
        <slot title="User cards"/>
    </div>
</template>

<style scoped>
    .wrapper{
    display: flex;
    gap: 12px;
    flex-wrap: wrap;

  }
</style>