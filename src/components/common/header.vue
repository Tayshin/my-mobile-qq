<template>
    <header class="ui-header ui-header-positive ui-border-b">
        <div class="ui-avatar-s">
            <span style="background-image:url(http://placeholder.qiniudn.com/80x80)"></span>
        </div>
        <h1>{{message}}</h1>
        <i class="ui-icon-add pull-right"></i>
    </header>
</template>

<script>
    export default {
        props:['message'],
    }
    ////dawdawdawdawdawd
</script>

<style>
    header .ui-avatar-s {
        display:inline-block;
        float:left;

        width:35px;
        height:35px;
        margin-top:4px;
    }
    header h1 {
        position:absolute;
        top:0;
        text-align:center;
        height:45px;
        width:100%;
        margin-left:-10px;
    }
    .pull-right {
        float:right;
    }
</style>