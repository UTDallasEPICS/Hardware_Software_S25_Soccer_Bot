<template>
    <div class="border rounded-lg p-2.5 content-center text-center border-4 border-black" style="width: 100%; height: 83px; padding: 5px; margin-bottom: 113%; margin-top: 13%;"> 
        <p style="font-style: italic">Up Next </p>
        <div class="flex place-content-evenly flex-no-wrap" style="font-style: italic; padding-right:0px">
            <p class="basis-0 grow truncate text-center"><strong>{{user1}}</strong></p>
            <p class="text-center w-min"><strong>vs</strong></p>
            <p class="basis-0 truncate grow text-center"><strong>{{user2}}</strong></p>
        </div>
    </div>
    </template>
    
    <script setup lang="ts">
    const user1 = ref("megha66634324545")
    const user2 = ref("crazouteriv")
    </script>
    
    